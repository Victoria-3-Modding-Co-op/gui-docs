# Data binding

Data binding is how a `.gui` file reads the game state. Any property value that
is wrapped in `[ ... ]` is an **expression**: the game evaluates it and converts
the result to whatever the property needs.

```text
visible = "[Character.IsValid]"
text    = "[Character.GetName]"
color   = "[Country.GetMapColor]"
onclick = "[CharacterPanel.SelectCharacter(Character.Self)]"
```

An expression is evaluated in a context — a **data context** — that decides what
a bare name refers to.

## Where expressions can appear

- As the whole value of a property: `visible = "[IsInGame]"`.
- Inside a longer string, mixed with literals: `raw_text = "[X] of [Y]"`.
- As an argument to another expression.

A quoted value that does not start with `[` is never evaluated, even if it
contains brackets later.

## Expression syntax

| Form | Meaning | Example |
|---|---|---|
| `Name` | A value or object in scope | `GetPlayer` |
| `Name(...)` | A function call | `GetScriptedGui('key')` |
| `A.B` | Member access on the result of `A` | `Character.GetName` |
| `'text'` | String literal | `'event:/SFX/UI/click'` |
| `123`, `1.5` | Number literal | `100` |
| `(int32)`, `(float)`, `(CFixedPoint)` | Typed literal / cast | `'(int32)0'` |

Arguments are comma-separated. Calls nest freely:

```text
[Not(Character.IsValid)]
[GetScriptedGui('my_sgui').Execute(GuiScope.SetRoot(GetPlayer.MakeScope).End)]
```

Notice `Character.Self` and `Character.IsValid`: `Character` here is a **scope
name**, not a variable. The game's expression language exposes each scope type
(`Country`, `Character`, `State`, `Goods`, ...) as a set of members you can chain
from a value of that type.

## The data context

The data context is the object an expression starts from. There are three ways it
gets set:

**1. The screen's context.** A top-level window is opened with a context by the
game. Inside it, expressions start from that object.

**2. `datacontext`.** Pushes a new context for the widget and its children:

```text
vbox = {
    datacontext = "[Company.GetBuilding]"

    textbox = { text = "[Building.GetName]" }       # Building is the context
    textbox = { text = "[Building.GetOwner.GetName]" }
}
```

`datacontext` is evaluated against the *outer* context, so it reads naturally:
"take this company's building, and from here on talk about the building".

**3. `datamodel` + `item`.** Feeds a collection into a container, which creates
one child per entry:

```text
dynamicgridbox = {
    datamodel = "[GetPlayer.GetStates]"

    item = {
        datacontext = "[State]"        # the current entry
        textbox = { text = "[State.GetName]" }
    }
}
```

Inside `item`, the loop variable is available as the scope name of the entry
(`State` in this example), and the item's own data context is that entry.

The index of the entry is available through the widget:

```text
visible = "[EqualTo_int32(PdxGuiWidget.GetIndexInDataModel, '(int32)0')]"
```

## Talking to the widget

`PdxGuiWidget` is the widget currently being evaluated. It exposes:

| Member | Result |
|---|---|
| `PdxGuiWidget.Self` / `AccessSelf` | The widget itself |
| `PdxGuiWidget.AccessParent` / `Parent` | The parent widget |
| `PdxGuiWidget.AccessChild('name')` | A named child |
| `PdxGuiWidget.FindChild('name')` | A named child, searched recursively |
| `PdxGuiWidget.IsVisible` / `Show` / `Hide` | Visibility |
| `PdxGuiWidget.TriggerAnimation('n')` | Play a state |
| `PdxGuiWidget.InterruptAnimation('n')` | Stop a state |
| `PdxGuiWidget.GetIndexInDataModel` | Loop index inside a data model |
| `PdxGuiWidget.StackTop` / `StackBottom` | Raise or lower in the stack |

This is what makes it possible to write behaviour without a controller object:

```text
onmouseenter = "[PdxGuiWidget.AccessChild('highlight').TriggerAnimation('show')]"
```

## Calling the game's API

Every function listed in the [function reference](reference/functions.md) is
available. The most useful groups for interface work:

| Group | Examples |
|---|---|
| Widget control | `PdxGuiWidget.*`, `PdxGuiInterruptThenTriggerAllAnimations` |
| Variables | `GetVariableSystem.Set`, `.HasValue`, `.Toggle` |
| Scripted GUIs | `GetScriptedGui('key').Execute`, `.IsShown`, `.IsValid` |
| Values | `Select_int32`, `Select_float`, `Not`, `And`, `Or`, arithmetic helpers |
| Collections | `GetDataModelSize`, `DataModelFirst`, `DataModelSkipFirst`, `IsEmpty` |
| Console (debug) | `ExecuteConsoleCommand` |

### Scripted GUIs

A scripted GUI is a named trigger/effect pair defined in
`common/scripted_guis/`. That is how a `.gui` file performs a real action:

```text
# gui
enabled = "[GetScriptedGui('increase_tax_sgui').IsValid(GuiScope.SetRoot(GetPlayer.MakeScope).End)]"
onclick = "[GetScriptedGui('increase_tax_sgui').Execute(GuiScope.SetRoot(GetPlayer.MakeScope).End)]"
```

```text
# common/scripted_guis/taxes.txt
increase_tax_sgui = {
    scope = country
    is_valid = { always = yes }
    effect = { add_treasury = 100 }
}
```

`GuiScope.SetRoot(...).End` builds the scope argument. The `.End` is not
decoration: it closes the scope builder and returns the value the function
expects.

### Variables

The UI can keep its own state in the variable system, which is how tabs and
filters are implemented without touching game state:

```text
button = {
    down    = "[GetVariableSystem.HasValue('tab', 'military')]"
    onclick = "[GetVariableSystem.Set('tab', 'military')]"
}

vbox = {
    visible = "[GetVariableSystem.HasValue('tab', 'military')]"
    # ...
}
```

`Set`, `SetIf`, `SetOrToggle`, `Toggle`, `Clear`, `Exists`, `Get` and `HasValue`
are the whole API. Variables are global to the interface session, so give them
namespaced keys.

## Macros

`data_binding/gui_macros.txt` defines named shorthands that the expression parser
expands before evaluation:

```text
macro = {
    definition = "IsZero(Value)"
    replace_with = "EqualTo_int32(Value, '(int32)0')"
}
```

So `IsZero(X)` is `EqualTo_int32(X, '(int32)0')`. The shipped set covers
zero/greater/less tests, sign flips, and a couple of localisation helpers. Read
that file before writing yet another comparison chain.

## Formatting the result

A `|` suffix formats the value before it is displayed. See
[Text](05-text.md#value-formatting-the--suffix) for the pieces; in brief:

```text
[GetPlayer.GetWeeklyIncome|D]      # currency
[BattleMilitaryFormation.GetAverageOffense|0v]   # compact, no decimals
```

Formatting is only meaningful for display properties (`text`, `raw_text`,
`tooltip`). A boolean property ignores it.

## Failure behaviour

An expression that cannot be evaluated does not crash the interface. The
property keeps its previous or default value and an error is written to
`error.log` with the file and line.

That makes debugging straightforward:

1. reproduce the screen;
2. look at the newest `error.log` entries;
3. the message names the expression and the reason (unknown function, wrong
   scope, null value).

The commonest causes are a wrong scope (`Character` where the context is a
`Country`) and a missing `IsValid` guard on an object that may be null.

### Guarding null values

Many objects can be empty. Guard before dereferencing:

```text
visible = "[Character.IsValid]"
text    = "[Character.GetName]"
```

`IsValid` exists on most scoped object types. For a value that may be missing,
`Select_*` and `If`-style helpers let you supply a fallback:

```text
text = "[Select_float(Character.IsValid, Character.GetPrestige, '(float)0')]"
```

## Performance

Expressions run whenever the widget is refreshed — potentially every frame while
the screen is visible. A few rules keep that cheap:

- **`max_update_rate`** on a widget caps how often its data is refreshed.
- **Scope the update** by putting `datacontext` as deep in the tree as possible,
  so unrelated widgets are not re-evaluated when the context changes.
- **Avoid expensive chains** in properties that are always visible; compute the
  value once in script and put it in a variable, or in a scripted GUI tooltip.
- **`datamodel_reuse_widgets`** avoids rebuilding item widgets on refresh, which
  matters for long lists.

## Debug helpers

- `PdxGuiWidget.HasContext(...)`, `IsVisible`, `GetShortcut` — introspection from
  expressions.
- The console has a widget inspector that shows the live tree, each widget's
  properties and its current data context.
- `ExecuteConsoleCommand(...)` in an `onclick` is a quick way to test an
  expression path.

## Next

- [Templates and reuse](09-templates.md)
- [Reference: functions](reference/functions.md)
- [Reference: data-binding types](reference/data-types/README.md)
