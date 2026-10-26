# File format

## The shape of a file

A `.gui` file is a sequence of top-level entries. Each entry is one of four
things:

| Entry | Meaning |
|---|---|
| `type NAME = BASE { ... }` | Declare a widget type |
| `template NAME { ... }` | Declare a reusable fragment |
| `types NAME { ... }` | Group related `type` declarations |
| `KIND = { ... }` | Create a widget tree at file scope (a window definition) |

Inside a block, an entry is either a **property** (`key = value`) or a **child
widget** (`kind = { ... }`).

```text
# A template: a bag of entries, pulled in with `using`.         (1)
template panel_title {
    using = fontsize_large
    fontcolor = { 0.9 0.8 0.6 1 }
}

types panels {                                                  (2)
    type my_panel = window {                                    (3)
        name = "my_panel"
        size = { 600 400 }

        vbox = {                                                (4)
            spacing = 6

            textbox = {
                using = panel_title                            (5)
                text = "MY_PANEL_TITLE"
            }
        }
    }
}
```

1. `template` declares a fragment, not a widget.
2. `types` is a named group. The name is documentation only.
3. `type NAME = BASE` declares a type; `BASE` is another type or an engine kind.
4. `vbox = { ... }` creates a child widget.
5. `using = panel_title` copies the template's entries in place.

## Syntax rules

- **Whitespace is free.** Line breaks and indentation mean nothing. They are
  the only reason the examples are readable.
- **Comments start with `#`** and run to the end of the line.
- **`=` before a block is optional.** `vbox = { }` and `vbox { }` are the same.
  Widget children are usually written with `=`, declarations and `block` slots
  without it, but both spellings occur in the shipped files
  (`block "content" { }` and `block = "content" { }` are both accepted).
- **Values are bare or quoted.** `direction = vertical` and
  `texture = "gfx/..."` are both single values. Quotes are needed when the
  value contains spaces or starts with a bracket.
- **A block can hold bare numbers.** `size = { 280 132 }` is a vector value, not
  a nested widget. The distinction is whether the braces contain entries or only
  values.
- **Keywords are case-insensitive.** `Types` and `types` both work.

### Macros

A file may define numeric macros at the top and use them anywhere below:

```text
@panel_width = 540
@panel_width_half = 270

type my_panel = window {
    size = { @panel_width 400 }
    vbox = { size = { @panel_width_half 0 } }
}
```

Macros are textual replacements, defined near the top of a file and usable below
their definition. They are a readability tool, not a configuration system:
prefer them over repeating magic numbers inside one file.

## Declaring types

```text
type NAME = BASE {
    # properties and children
}
```

- `NAME` must be unique across all loaded files. Two files declaring the same
  type name produces a load warning, and only one of them wins.
- `BASE` must already exist: either an engine kind or another declared type.
- A type with the same name as its base is legal and common. `type button =
  button { ... }` is how the game sets defaults for an engine kind:

```text
type button = button {
    gfxtype = buttongfx
    shaderfile = "gfx/FX/pdxgui_pushbutton.shader"
}
```

That declaration does not create a new kind. It attaches defaults to the
existing `button` kind, and every button in the game inherits them.

### Inheritance

A derived type starts as a copy of its base and then applies its own entries:

```text
type panel = window {
    size = { 400 300 }
    movable = yes
}

type big_panel = panel {
    size = { 800 600 }     # overrides the base
    resizable = yes         # adds to the base
}
```

Overriding a property replaces it. Overriding a child widget is not possible by
re-declaring it — use a `block` in the base and a `blockoverride` in the derived
type (see below).

## Declaring templates

```text
template NAME {
    # entries to copy
}
```

A template is inserted with `using = NAME` and behaves as if its entries had
been typed at that point:

```text
template tooltip_font {
    font = "OpenSans"
    fontsize = 15
}

textbox = {
    using = tooltip_font
    text = "HELLO"
}
```

Templates can use other templates, and can contain `block` slots so a user can
fill them in. They cannot be instantiated as widgets, inherited from, or
overridden by name.

## Named slots: `block` and `blockoverride`

A reusable type often has parts that each user should be able to replace. That
is what `block` and `blockoverride` are for.

**The base** declares a named hole with `block`:

```text
type my_card = container {
    size = { 300 120 }

    block "header" {
        textbox = { text = "DEFAULT_HEADER" }
    }

    block "body" { }
}
```

**The derived type** replaces the hole's contents with `blockoverride`:

```text
type special_card = my_card {
    blockoverride "header" {
        textbox = { text = "SPECIAL_HEADER" fontsize = 22 }
    }

    blockoverride "body" {
        icon = { texture = "gfx/interface/icons/star.dds" size = { 32 32 } }
    }
}
```

Rules that matter in practice:

- A `blockoverride` replaces the entire contents of the matching `block`. It
  does not merge.
- The contents of `blockoverride` are evaluated in the *derived* type's context,
  so they can use anything the derived type can see.
- A `block` that is never overridden simply keeps its default contents. An empty
  `block "x" { }` is an optional extension point that costs nothing.
- Slot names are per type chain, not global. Two unrelated types may both have a
  `"header"` block.

## Load order and overriding game files

All `.gui` files below a `gui/` directory are loaded; the engine merges the
game's files with those of every active mod.

- **Override a file** by shipping a file at the same relative path. That is the
  normal way to change a whole screen.
- **Add to a screen** by declaring a type that derives from one of the game's
  types and overriding its blocks, instead of editing the game file.
- **Avoid duplicate type names.** If two *different* paths declare the same
  type, the engine logs a warning and one declaration shadows the other. The
  shipped game itself has a few such collisions, but they are bugs, not a
  pattern to copy.

The safe pattern for a mod is:

```text
type my_extra_row = some_game_type {
    blockoverride "text" {
        text = "MY_OWN_TEXT"
    }
}
```

## What a top-level widget is

A `.gui` file may also contain a bare widget tree at file scope:

```text
minimap_window = {
    name = "minimap"
    visible = "[IsInGame]"
    size = { 280 132 }
}
```

This creates a named top-level widget that the game can show. It is how the
minimap, the top bar, and the various tool windows are defined. Everything you
have read about types applies inside it.

## Conventions worth copying

The shipped files follow a few conventions that make an interface file readable:

- one file per screen, named after the screen;
- a `types` group at the top holding the screen's own types;
- templates first, then types, then the top-level widget;
- `using =` for typography and colours rather than repeating numbers;
- `block "name"` around anything a mod is likely to want to replace;
- two blank lines between top-level declarations.

## Next

- [Widgets and layout](03-widgets-and-layout.md)
- [Templates and reuse](09-templates.md)
