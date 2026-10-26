# checkbutton

A toggle button with a checked state.

## At a glance

- **Kind:** `checkbutton`
- **Category:** Interaction
- **Children:** none
- **Derives from:** `button`
- **Used in the shipped interface:** 49 times

## When to use it

A toggle. `checked` binds the state, `ontoggled` reacts to it.

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `checked` | bool | State of a checkbutton. | `checked = "[ShipSelection.IsSelected(Ship.Self)]"` |
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. | `texture = "gfx/editor_gui/editor_checkbox.dds"` |
| `framesize` | vector2 | Size of one frame in a sprite sheet. | `framesize = { 16 16 }` |
| `gfxtype` | token | Name of the engine draw type used for the widget, for example `buttongfx`, `windowgfx` or `progressbargfx`. | `gfxtype = checkbuttongfx` |
| `shaderfile` | texture | Path of the shader used by the draw type. | `shaderfile = "gfx/FX/pdxgui_pushbutton.shader"` |

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
