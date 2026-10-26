# minimap

Renders the map minimap texture.

## At a glance

- **Kind:** `minimap`
- **Category:** Visual
- **Children:** none
- **Used in the shipped interface:** 1 times

## When to use it

Renders the map minimap texture, usually inside `minimap_window`.

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. | `texture = "gfx/interface/minimap/minimap.dds"` |
| `gfxtype` | token | Name of the engine draw type used for the widget, for example `buttongfx`, `windowgfx` or `progressbargfx`. | `gfxtype = minimapgfx` |
| `shaderfile` | texture | Path of the shader used by the draw type. | `shaderfile = "gfx/FX/pdxgui_default.shader"` |

## Notes

A generic widget paired with the engine's `minimapgfx` draw type; the game's `type minimap = minimap` declaration attaches that draw type and the shader.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
