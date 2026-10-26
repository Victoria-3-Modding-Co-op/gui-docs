# Templates and reuse

There are two reuse mechanisms, and they solve different problems.

| Mechanism | Declared with | Used with | Can be overridden |
|---|---|---|---|
| Template | `template NAME { }` | `using = NAME` | No |
| Type | `type NAME = BASE { }` | `NAME = { }` as a widget | Yes, by deriving |

## Templates: copy a set of entries

A template is a named bag of entries. `using = NAME` splices those entries in at
that point.

```text
template fontsize_medium {
    font = "OpenSans"
    fontsize = 14
}

textbox = {
    using = fontsize_medium
    text = "HELLO"
}
```

That is exactly equivalent to writing the template's entries inline. Templates
are best for:

- typography (`fontsize_small`, `header_font`);
- colours and tints;
- animation state fragments (`Animation_Curve_Default`);
- small bundles of geometry that always travel together.

Templates can contain:

- properties;
- child widgets;
- `block` declarations (so the user of the template can fill a hole);
- `using` of other templates.

```text
template framed_panel {
    block "frame" {
        background = {
            using = default_background
            margin = { 4 4 }
        }
    }

    block "content" { }
}
```

A template that declares `block "content" { }` expects the user to supply that
part with a `blockoverride` — but only types can override blocks, so this pattern
is normally wrapped in a type:

```text
type framed_panel_type = container {
    using = framed_panel
}

type framed_list = framed_panel_type {
    blockoverride "content" {
        dynamicgridbox = { /* ... */ }
    }
}
```

## Types: a widget with defaults

A type is a real widget you can instantiate:

```text
type section_header = textbox {
    font = "PlayfairDisplay"
    fontsize = 22
    fontcolor = { 0.9 0.8 0.6 1 }
    margin_bottom = 6
}
```

```text
section_header = { text = "SECTION_TITLE" }
```

Everything the base type defines is inherited. The derived type adds and
overrides.

### Naming

The shipped files use a few conventions worth following:

| Suffix / pattern | Meaning |
|---|---|
| `_button` | A clickable type |
| `_item` | One row of a list or grid (fed by `datamodel`) |
| `_header` | A heading row |
| `_panel` | A top-level screen |
| `_types` (in a `types` group name) | Holds the screen's private types |
| `default_*` / `_shared` | Shared building blocks in `gui/shared/` |

Types used only inside one screen are normally declared in a `types` group at
the top of that screen's file. Types that several screens use live in
`gui/shared/`.

## `types` groups

```text
types budget {
    type budget_row = flowcontainer { /* ... */ }
    type budget_total = textbox { /* ... */ }
}
```

The group name has no runtime meaning. It documents which screen the types
belong to and keeps the file navigable. Reusing a group name across files is
harmless.

## `block` and `blockoverride`

A `block` is a named hole in a type. A derived type replaces the hole's contents
with `blockoverride`.

```text
type card = container {
    size = { 320 160 }

    block "header" {
        textbox = { text = "DEFAULT_HEADER" fontsize = 20 }
    }

    block "body" { }

    block "footer" {
        textbox = { text = "DEFAULT_FOOTER" }
    }
}
```

```text
type warning_card = card {
    blockoverride "header" {
        textbox = {
            text = "WARNING_HEADER"
            fontsize = 20
            fontcolor = { 0.9 0.3 0.3 1 }
        }
    }

    blockoverride "body" {
        textbox = { text = "WARNING_BODY" multiline = yes }
    }
}
```

The `footer` block is not overridden, so `warning_card` keeps the default footer.

Rules:

- **Replacement, not merge.** The override's contents become the block's entire
  contents.
- **Scope.** Contents are evaluated as part of the derived type, so they can use
  anything the derived type declares.
- **Empty default.** `block "x" { }` is a free extension point: the type works
  without it and a derived type can fill it.
- **Nesting.** Blocks may contain other blocks; overrides address one level at a
  time.

This is the mechanism behind most of the game's reusable widgets. A button type
declares `block "icon"`, `block "text"`, `block "sound"`, and a hundred icon
buttons override only the parts they care about.

## Overriding game types without editing game files

The recommended mod pattern is to derive from a game type and override blocks:

```text
type my_compact_row = some_game_row {
    size = { 0 24 }

    blockoverride "text" {
        textbox = { text = "[Item.GetName]" fontsize = 12 }
    }
}
```

If the game type does not expose a block where you need one, the alternative is
to replace the whole file at the same relative path. That is heavier: it forks
the file and you inherit the maintenance cost on every game update.

A middle path that is often enough: keep the game type, derive from it, and
splice in a template of your own values.

```text
template my_theme_colors {
    fontcolor = { 0.9 0.8 0.6 1 }
    tintcolor = { 1 1 1 1 }
}

type themed_row = some_game_row {
    using = my_theme_colors
}
```

Note the asymmetry: `using` takes a **template**, inheritance takes a **type**.
Writing `type x = my_template` is an error, and writing `using = some_game_type`
is an error too.

## Template versus type: choosing

Use a **template** when:

- the fragment has no identity — it is a set of numbers or a colour;
- it should be splashed into several unrelated types;
- it is not something you would ever write as `something = { }`.

Use a **type** when:

- it is a widget you instantiate;
- it should be inheritable;
- it has parts a caller might replace.

A useful test: if you would write `using = x` inside three different widgets, it
is a template. If you would write `x = { ... }`, it is a type.

## Inheritance depth

Chains of five or six types are normal in the game (`button` →
`default_button` → `toolbar_button` → `toolbar_button_compact`). Two habits keep
them manageable:

- **Inherit for defaults, not for behaviour.** A chain that only changes numbers
  and textures stays readable; one that restructures the tree does not.
- **Override blocks, not children.** Re-declaring a child name in a derived type
  adds a second child rather than replacing the first.

## Next

- [Cookbook](10-cookbook.md)
- [Reference: game types](reference/types.md)
- [Reference: templates](reference/templates.md)
