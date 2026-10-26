# icon

Draws a texture (optionally a sprite sheet) with an optional modify texture and glow.

## At a glance

- **Kind:** `icon`
- **Category:** Visual
- **Children:** none
- **Used in the shipped interface:** 2,517 times

## When to use it

Draws a texture. This is the kind used for almost every image in the interface, including sprite-sheet frames and glow effects.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `tooltipwidget` | Custom tooltip body. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. | `texture = "[GUIAchievement.AccessTexture]"` |
| `texture_density` | number | Pixel density of the texture relative to the interface scale. `2` means the image is drawn at half its pixel size. | `texture_density = 2` |
| `spriteType` | token | How the texture is mapped onto the widget rectangle. | `spriteType = Corneredtiled` |
| `framesize` | vector2 | Size of one frame in a sprite sheet. | `framesize = { 400 80 }` |
| `frame` | int | Index of the sprite-sheet frame to draw. | `frame = "[BattleSide.GetIconFrame]"` |
| `spriteborder` | vector2 | Horizontal and vertical inset of the nine-slice border. | `spriteborder = { 0 0 }` |
| `mirror` | flags | Mirror the widget's texture. | `mirror = horizontal` |
| `spriteborder_bottom` | number | Bottom border inset. | `spriteborder_bottom = 0` |
| `gfxtype` | token | Name of the engine draw type used for the widget, for example `buttongfx`, `windowgfx` or `progressbargfx`. | `gfxtype = propstretchedicongfx` |
| `spriteborder_right` | number | Right border inset. | `spriteborder_right = 610` |
| `shaderfile` | texture | Path of the shader used by the draw type. | `shaderfile = "gfx/FX/pdxgui_colorpicker.shader"` |
| `effectname` | string | Name of a named effect inside `shaderfile`. | `effectname = "PdxGuiColorButton"` |
| `spriteborder_top` | number | Top border inset. | `spriteborder_top = 600` |
| `delay` | float | Delay before the animation state starts, in seconds. | `delay = 1.3` |
| `tintcolor` | colour | Tint applied to the drawn texture. | `tintcolor = "[TooltipInfo.GetTintColor]"` |
| `spriteborder_left` | number | Left border inset. | `spriteborder_left = 200` |
| `mipmaplodbias` | float | Bias applied when sampling the texture mip chain. | `mipmaplodbias = -1` |
| `duration` | float | Length of an animation state in seconds. | `duration = 0` |
| `datacontext_from_model` | block | Push a data model entry into the data context of a child. |  |
| `start_sound` | block | Sound played when the state starts. |  |
| `align` | flags | Horizontal and vertical alignment of the text inside its box. | `align = center` |
| `entity_instance` | expression | Entity instance drawn by a 3D widget. | `entity_instance = "[PowerBlocStatue.GetEntity(PdxGuiWidget.AccessSelf)]"` |
| `render_pass` | expression | Render pass the entity widget is drawn in. | `render_pass = "[GetGuiEntityShaderRenderpass]"` |
| `gfx_environment_file` | texture | Lighting environment used when rendering an entity widget. | `gfx_environment_file = "gfx/map/environment/ui_power_bloc_statues_environment.txt"` |
| `enabled_post_effects` | flags | Post effects enabled for the entity widget. | `enabled_post_effects = luminance` |
| `camera_position` | vector3 | Camera position for a widget that renders an entity. | `camera_position = "[PowerBlocCustomizationPopup.GetCameraPosition]"` |
| `camera_look_at` | vector3 | Point the widget's camera looks at. | `camera_look_at = { 0.0 1.6 0.0 }` |
| `camera_fov_y_degrees` | float | Vertical field of view of the widget's camera. | `camera_fov_y_degrees = 12` |
| `camera_near_far` | vector2 | Near and far clip planes of the widget's camera. | `camera_near_far = { 0.1 300.0 }` |
| `trigger_on_create` | bool | Play the animation state as soon as the widget is created. | `trigger_on_create = yes` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. |
| `fittype` | token | How the texture is fitted into its rectangle. |
| `video` | texture | Video file played by the widget. |
| `entity_enable_sound` | bool | Play the entity's configured sounds. |
| `realtime` | bool | Advance the animation in real time rather than game time. |
| `coat_of_arms_slot` | expression | Coat-of-arms slot whose texture the widget should display. |
| `loop` | bool | Loop the video or animation. |
| `fade_from_point` | vector2 | Start point of a fade gradient. |
| `fade_to_point` | vector2 | End point of a fade gradient. |

## `modify_texture` sub-object

A second texture composited over the widget's main texture, with its own transform and blending. Declare several and address them by `name` from animations.

| Key | Meaning | Example |
|---|---|---|
| `alpha` | Opacity, 0..1. | `alpha = 0` |
| `blend_mode` | Compositing mode. | `blend_mode = alphamultiply` |
| `color` | Colour multiplier, `{ r g b a }`. | `color = "[PowerBloc.GetPrimaryColor]"` |
| `mirror` | Mirror flags. | `mirror = horizontal` |
| `name` | Name used by animation states to target this layer. | `name = "mask"` |
| `rotate_uv` | Texture-coordinate rotation in degrees. | `rotate_uv = 0` |
| `spriteType` | How the image is mapped onto the rectangle. | `spriteType = Corneredstretched` |
| `spriteborder` | Nine-slice border inset. | `spriteborder = { 0 0 }` |
| `spriteborder_bottom` | Bottom border inset. | `spriteborder_bottom = 0` |
| `texture` | Image path. | `texture = "gfx/interface/masks/fade_vertical_top.dds"` |
| `texture_density` | Pixel density relative to interface scale. | `texture_density = 2` |
| `translate_uv` | Texture-coordinate offset. | `translate_uv = { 0 0 }` |
| `visible` | Whether this layer is drawn. | `visible = no` |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Key | Meaning | Example |
|---|---|---|
| `alpha` | Target opacity, 0..1. | `alpha = 1` |
| `animation` | Named animation curve description. |  |
| `delay` | Delay before the state starts, in seconds. | `delay = 0.35` |
| `duration` | Length of the animation in seconds. | `duration = 0` |
| `modify_texture` | Per-state overrides for a modify texture, matched by `name`. |  |
| `name` | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. | `name = _show` |
| `next` | State to play when this one finishes. | `next = show_2` |
| `on_finish` | Expression run when the state finishes. | `on_finish = "[PdxGuiTriggerAllAnimations('menu_logo_i_start')]"` |
| `on_start` | Expression run when the state starts. | `on_start = "[PdxGuiTriggerAllAnimations('menu_logo_v')]"` |
| `position` | Target position, `{ x y }`. | `position = { 0 0 }` |
| `position_x` | Target position on the x axis only. | `position_x = 0` |
| `position_y` | Target position on the y axis only. | `position_y = 0` |
| `scale` | Target uniform scale. | `scale = 25` |
| `size` | Target size, `{ w h }`. | `size = { 100 100 }` |
| `start_sound` | Sound played when the state starts. |  |
| `trigger_on_create` | Play the state when the widget is created. | `trigger_on_create = yes` |
| `trigger_when` | Expression that starts the state automatically. | `trigger_when = "[Article.ExceedsMaxContraventions(Country.Self)]"` |

## Notes

`texture` is the image; `spriteType` decides how it is stretched or tiled; `spriteborder` insets the nine-slice border.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
