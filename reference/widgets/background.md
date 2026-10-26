# background

A texture drawn behind its parent widget.

## At a glance

- **Kind:** `background`
- **Category:** Visual
- **Children:** none
- **Used in the shipped interface:** 1,252 times

## When to use it

A texture drawn behind its parent. Written as a child block called `background`.

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. | `texture = "gfx/interface/backgrounds/popup_bg.dds"` |
| `spriteType` | token | How the texture is mapped onto the widget rectangle. | `spriteType = Corneredstretched` |
| `spriteborder` | vector2 | Horizontal and vertical inset of the nine-slice border. | `spriteborder = { 90 90 }` |
| `texture_density` | number | Pixel density of the texture relative to the interface scale. `2` means the image is drawn at half its pixel size. | `texture_density = 2` |
| `fittype` | token | How the texture is fitted into its rectangle. | `fittype = centercrop` |
| `shaderfile` | texture | Path of the shader used by the draw type. | `shaderfile = "gfx/FX/pdxgui_default.shader"` |
| `mirror` | flags | Mirror the widget's texture. | `mirror = horizontal` |
| `spriteborder_right` | number | Right border inset. | `spriteborder_right = 100` |
| `spriteborder_bottom` | number | Bottom border inset. | `spriteborder_bottom = 180` |
| `spriteborder_top` | number | Top border inset. | `spriteborder_top = 170` |
| `mipmaplodbias` | float | Bias applied when sampling the texture mip chain. | `mipmaplodbias = 1.8` |
| `effectname` | string | Name of a named effect inside `shaderfile`. | `effectname = "GuiBlur"` |
| `spriteborder_left` | number | Left border inset. | `spriteborder_left = 200` |
| `framesize` | vector2 | Size of one frame in a sprite sheet. | `framesize = { 600 80 }` |
| `frame` | int | Index of the sprite-sheet frame to draw. | `frame = "[MapListOption.GetBackgroundStatusFrame]"` |
| `tintcolor` | colour | Tint applied to the drawn texture. | `tintcolor = "[TooltipInfo.GetTintColor]"` |

## `modify_texture` sub-object

A second texture composited over the widget's main texture, with its own transform and blending. Declare several and address them by `name` from animations.

| Key | Meaning | Example |
|---|---|---|
| `alpha` | Opacity, 0..1. | `alpha = 1` |
| `blend_mode` | Compositing mode. | `blend_mode = overlay` |
| `color` | Colour multiplier, `{ r g b a }`. | `color = { 0.45 0.45 0.45 1.0 }` |
| `mirror` | Mirror flags. | `mirror = vertical` |
| `name` | Name used by animation states to target this layer. | `name = "mask"` |
| `rotate_uv` | Texture-coordinate rotation in degrees. | `rotate_uv = 225` |
| `spriteType` | How the image is mapped onto the rectangle. | `spriteType = Corneredstretched` |
| `spriteborder` | Nine-slice border inset. | `spriteborder = { 0 0 }` |
| `spriteborder_bottom` | Bottom border inset. | `spriteborder_bottom = 0` |
| `spriteborder_left` | Left border inset. | `spriteborder_left = 600` |
| `spriteborder_right` | Right border inset. | `spriteborder_right = 50` |
| `spriteborder_top` | Top border inset. | `spriteborder_top = 230` |
| `texture` | Image path. | `texture = "gfx/interface/backgrounds/default_bg_shading.dds"` |
| `texture_density` | Pixel density relative to interface scale. | `texture_density = 2` |
| `visible` | Whether this layer is drawn. | `visible = "[CombatUnit.IsFullyMobilized]"` |

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
