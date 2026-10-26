> [!WARNING]  
> This documentation has been AI generated and is based on the game files as well as the binary.

# Victoria 3 GUI scripting

This is a guide to the interface system used by Victoria 3. It explains how
`.gui` files are written, what the widgets and their properties do, how a
window gets its data, and how to change the interface safely.

It is written for people who want to **read and modify an existing interface**,
and for people who want to **build their own panels** on top of the game's
widgets. No engine programming is required.

## How this documentation is organised

| Part | What it covers |
|---|---|
| [Overview](01-overview.md) | The mental model: files, widgets, types, data binding |
| [File format](02-file-format.md) | Syntax, declarations, `using`, `block`, load order |
| [Widgets and layout](03-widgets-and-layout.md) | The widget tree, sizing, anchoring, containers |
| [Appearance](04-appearance.md) | Textures, sprites, frames, colour, effects |
| [Text](05-text.md) | Strings, localisation, formatting tags, inline icons |
| [Interaction](06-interaction.md) | Events, tooltips, focus, shortcuts, drag and drop |
| [Animation](07-animation.md) | States, transitions, curves, sound cues |
| [Data binding](08-data-binding.md) | `[ ... ]` expressions, data contexts, lists |
| [Templates and reuse](09-templates.md) | Templates, inheritance, `blockoverride` |
| [Cookbook](10-cookbook.md) | Short worked answers to common tasks |

The **reference** section is the lookup companion. Every widget kind, every
property with its value type, every callback, every enumeration token, and the
full data-binding API are listed there:

- [Widget kinds](reference/widgets.md)
- [Common properties](reference/common-properties.md)
- [Properties by kind](reference/properties.md)
- [Events](reference/events.md)
- [Enumerations](reference/enums.md)
- [Game types](reference/types.md)
- [Templates](reference/templates.md)
- [Data-binding functions](reference/functions.md)
- [Data-binding types](reference/data-types/README.md)

## A first look

A `.gui` file is a tree of blocks. Each block either creates a widget or sets a
property on the widget that encloses it.

```text
window = {
    name = "my_panel"
    parentanchor = center
    widgetanchor = center
    size = { 500 300 }

    background = {
        using = default_background
    }

    vbox = {
        spacing = 8
        margin = { 16 16 }

        textbox = {
            text = "MY_PANEL_TITLE"
            fontsize = 22
        }

        textbox = {
            text = "MY_PANEL_BODY"
            autoresize = yes
            multiline = yes
        }

        button = {
            using = default_button
            size = { 0 40 }
            text = "MY_PANEL_CLOSE"
            onclick = "[PdxGuiWidget.AccessParent.AccessParent.Hide]"
        }
    }
}
```

Read it as a sentence: a `window` called `my_panel`, centred on its parent, 500
by 300 pixels, with a background, containing a vertical box with 8 pixels of
spacing that holds a title, a body, and a close button.

Three things are worth noticing immediately:

- **Keys are either widget kinds or properties.** `vbox`, `textbox`, `button`
  and `background` create widgets. `size`, `spacing`, `text` and `onclick` set
  properties on the enclosing widget.
- **Text is a localisation key by default.** `"MY_PANEL_TITLE"` is looked up in
  the localisation files, not printed literally.
- **Behaviour is data binding.** Anything inside `[ ... ]` is an expression
  evaluated against the widget's data context.

## Where files live

```text
game/
  gui/                 all interface files (*.gui)
    shared/            reusable templates and default types
    frontend/          main-menu interface
    scripted_widgets/  widgets created at startup from a list
  common/
    scripted_guis/     triggers and effects attached to interface elements
  data_binding/
    gui_macros.txt     named shortcuts for data-binding expressions
```

Every `.gui` file below `gui/` is loaded automatically; there is no list to
register a file in. A mod overrides a game file by shipping a file at the same
relative path. See [File format](02-file-format.md) for the details and for the
rules on redefining types.

## What the system is good at, and where it stops

The interface layer handles **layout, styling, input and animation**. It does
not decide what a panel means. Anything that reads or changes the game state is
expressed as a **data-binding expression** that calls into the game's script
API, or as a **scripted GUI** that runs a trigger/effect pair.

That split is why the same widget tree can be reused for dozens of different
panels: the structure lives in the `.gui` file, and the content arrives through
`datacontext` and `[ ... ]`.

A useful rule of thumb:

- If it is about *where things are and how they look*, it is a property.
- If it is about *what things say*, it is data binding.
- If it is about *what happens when the player clicks*, it is a callback that
  either calls a data-binding function or runs a scripted GUI.
