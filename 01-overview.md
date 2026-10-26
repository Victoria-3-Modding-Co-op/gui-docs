# Overview

## The three layers

A Victoria 3 screen is produced by three cooperating layers.

```text
   .gui file                      engine                      game script
┌──────────────────┐        ┌──────────────────┐        ┌──────────────────┐
│ widget tree      │  ───▶  │ layout, drawing, │  ◀───  │ triggers/effects │
│ + properties     │        │ input, animation │        │ scopes, values   │
│ + [ expressions ]│        │                  │        │ localisation     │
└──────────────────┘        └──────────────────┘        └──────────────────┘
```

1. **Structure.** The `.gui` file declares a tree of widgets and sets
   properties on them. This is the part you edit most often.
2. **Presentation.** The engine lays the tree out, draws it, routes mouse and
   keyboard input, and runs animations. You influence it through properties.
3. **Content.** Data-binding expressions, scripted GUIs and localisation supply
   the text, numbers, lists and actions. You influence it through `[ ... ]`.

## Widgets

A **widget** is a rectangle on screen with behaviour attached. Every widget has:

- a **kind** — what it is (`window`, `vbox`, `button`, `textbox`, `icon`, ...);
- **properties** — how it is positioned, drawn and interacted with;
- optional **children** — other widgets nested inside it.

The kind is written as the block key:

```text
vbox = {                    # kind: vbox
    spacing = 4             # property of the vbox
    textbox = {             # child of kind textbox
        text = "HELLO"      # property of the textbox
    }
}
```

A widget's children are drawn on top of it and move with it. There is no
separate "add child" call: nesting *is* the parent relationship.

The complete list of kinds is in [Widget kinds](reference/widgets.md). The
common ones:

| Kind | Purpose |
|---|---|
| `widget` | Blank rectangle; the base of everything |
| `container` | Holds children at absolute positions |
| `window` | Draggable, resizable panel |
| `vbox` / `hbox` | Stacks children vertically / horizontally |
| `flowcontainer` | A box that wraps onto new rows |
| `fixedgridbox` / `dynamicgridbox` | Grids, the latter fed by a data model |
| `textbox` | Displays text |
| `editbox` | Editable text |
| `icon` | Draws an image |
| `button` / `checkbutton` | Clickable |
| `progressbar` | Shows a value in a range |
| `scrollarea` | Scrollable viewport |

## Types

Most widgets in the game are not raw engine kinds. They are **game types**:
named combinations of a base widget and a set of predefined properties.

```text
type default_button = button {
    gfxtype = framedbuttongfx
    size = { 100 40 }
    using = fontsize_medium
}
```

`type default_button = button` means "a `button` with these defaults, called
`default_button`". Anywhere a `button` could be written, `default_button` can be
written instead:

```text
default_button = {
    text = "OK"
    onclick = "[Confirm]"
}
```

A type inherits everything from its base. Re-declaring a property in the
derived type overrides it. This is the main mechanism for keeping the interface
consistent: the game ships hundreds of types in `gui/shared/` and most panels
are built from them.

See [Templates and reuse](09-templates.md).

## Properties

Properties are plain `key = value` entries. Their value is one of a small number
of shapes:

| Shape | Written as | Example |
|---|---|---|
| Boolean | `yes` / `no` | `visible = no` |
| Number | digits, optionally fractional or with `%` | `spacing = 10`, `size = { 100% 40 }` |
| Vector | two or more numbers in braces | `position = { 8 30 }` |
| Colour | four numbers in 0..1 | `tintcolor = { 0 0 0 0.6 }` |
| Token | a bare identifier | `direction = vertical` |
| Flags | identifiers joined by `\|` | `parentanchor = bottom\|hcenter` |
| String | quoted | `texture = "gfx/..."` |
| Expression | quoted, starts with `[` | `visible = "[IsInGame]"` |
| Block | braces | `size = { 280 132 }` |

Which properties a widget accepts depends on its kind. Everything accepts the
[common properties](reference/common-properties.md); the rest are listed on the
kind's own page.

## Data binding

Anything inside `[ ... ]` is evaluated by the game's data-binding engine. It
starts from the widget's **data context** and chains function calls and
property accesses:

```text
visible  = "[Character.IsValid]"
text     = "[Character.GetName]"
tooltip  = "[Character.GetTooltip]"
onclick  = "[CharacterPanel.SelectCharacter(Character.Self)]"
```

The result is converted to whatever the property needs: a boolean for `visible`,
a string for `text`, a colour for `tintcolor`.

Two properties control what an expression sees:

- **`datacontext`** pushes a new object as the root of `[ ... ]` for the widget
  and all of its children.
- **`datamodel`** feeds a collection into a container, which instantiates its
  `item` block once per entry.

```text
dynamicgridbox = {
    datamodel = "[GetPlayer.GetStates]"
    item = {
        textbox = { text = "[State.GetName]" }
    }
}
```

See [Data binding](08-data-binding.md) and the
[function reference](reference/functions.md).

## Where behaviour comes from

The interface itself cannot change the game. It can:

- **call a data-binding function** that the game exposes, such as
  `PdxGuiWidget.Hide`, `GetVariableSystem.Set`, or an `Execute...` helper;
- **run a scripted GUI**, which is a named trigger/effect pair in
  `common/scripted_guis/`.

```text
# gui file
onclick = "[GetScriptedGui('my_effect_sgui').Execute(GuiScope.SetRoot(GetPlayer.MakeScope).End)]"
```

```text
# common/scripted_guis/my_sguis.txt
my_effect_sgui = {
    scope = country
    is_shown = { always = yes }
    effect  = { add_treasury = 100 }
}
```

## How a window appears

The game creates top-level windows from its own window manager. A `.gui` file
supplies the definition; something else decides when to show it.

Three routes cover most needs:

- **A top-level widget definition.** A root block such as
  `window = { name = "my_panel" ... }` defines a named widget that the game can
  create. For testing, the console command
  `GUI.CreateWidget gui/my_panel.gui my_panel` creates it on demand.
- **A scripted widget**, listed in `gui/scripted_widgets/`, which the game
  instantiates at startup so it exists before anything references it.
- **A scripted GUI** attached to an existing element, when what you need is an
  action rather than a screen.

Which route fits depends on whether the panel is opened by the player, by a
journal entry, or by a notification. [Cookbook](10-cookbook.md) has recipes.

## Next

- [File format](02-file-format.md) — the syntax in full.
- [Widgets and layout](03-widgets-and-layout.md) — positioning and sizing.
- [Data binding](08-data-binding.md) — the expression language.
