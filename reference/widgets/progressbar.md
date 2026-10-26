# progressbar

A horizontal or vertical bar showing a value in a range.

## At a glance

- **Kind:** `progressbar`
- **Category:** Visual
- **Children:** none
- **Used in the shipped interface:** 58 times

## When to use it

Shows a value between `min` and `max` as a filled bar.

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `noprogresstexture` | texture | Texture used for the empty part of a progress bar. | `noprogresstexture = "gfx/interface/icons/generic_icons/transparent.dds"` |
| `progresstexture` | texture | Texture used for the filled part of a progress bar. | `progresstexture = "gfx/interface/icons/generic_icons/transparent.dds"` |
| `direction` | token | Main axis of a layout container, a progress bar or a scrollbar. | `direction = vertical` |
| `texture_density` | number | Pixel density of the texture relative to the interface scale. `2` means the image is drawn at half its pixel size. | `texture_density = 2` |
| `skip_initial_animation` | bool | Do not animate the first value change. | `skip_initial_animation = yes` |
| `spriteType` | token | How the texture is mapped onto the widget rectangle. | `spriteType = Corneredtiled` |
| `spriteborder` | vector2 | Horizontal and vertical inset of the nine-slice border. | `spriteborder = { 4 4 }` |
| `min` | number | Lower bound of a progress bar or scrollbar. | `min = 0` |
| `max` | number | Upper bound of a progress bar or scrollbar. | `max = 1` |
| `marker` | block | Widget used as the marker on a progress bar. |  |
| `animate_negative_changes` | bool | Animate a decrease as well as an increase. | `animate_negative_changes = yes` |
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. | `texture = "gfx/interface/progressbar/progressbar_green_glow.dds"` |
| `value` | number | Current value of a progress bar or scrollbar. | `value = "[Country.GetRankProgress]"` |
| `gfxtype` | token | Name of the engine draw type used for the widget, for example `buttongfx`, `windowgfx` or `progressbargfx`. | `gfxtype = progressbargfx` |
| `shaderfile` | texture | Path of the shader used by the draw type. | `shaderfile = "gfx/FX/pdxgui_progressbar.shader"` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `framesize` | vector2 | Size of one frame in a sprite sheet. |
| `frame` | int | Index of the sprite-sheet frame to draw. |
| `tintcolor` | colour | Tint applied to the drawn texture. |

## Notes

`progressbar` is horizontal by default; `direction = vertical` turns it on its side.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
