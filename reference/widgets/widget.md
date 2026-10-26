# widget

The base widget. A bare rectangle that can be positioned, textured and shown or hidden, with no layout behaviour of its own.

## At a glance

- **Kind:** `widget`
- **Category:** Layout
- **Children:** accepted, positioned by their own anchors
- **Used in the shipped interface:** 4,414 times

## When to use it

A blank rectangle. Used as a spacer, a click target, a position anchor for children, or as the base for a game type that only needs geometry and the common properties.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `tooltipwidget` | Custom tooltip body. |
| `item` | Instantiated once per data model entry. |
| `axis` | Chart axis. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `movable` | bool | Allow the player to drag the window. | `movable = no` |
| `delay` | float | Delay before the animation state starts, in seconds. | `delay = 0.3` |
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. | `texture = "gfx/interface/buttons/button_icons/goto.dds"` |
| `datamodel` | expression | Feeds a collection into a data-driven container, which then creates one `item` child per entry. | `datamodel = "[ShipDesignerPopup.GetCostPoints]"` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. |
| `value` | number | Current value of a progress bar or scrollbar. |
| `raw_text` | string | Text displayed without localisation lookup, usually to mix literals with data bindings. |
| `max` | number | Upper bound of a progress bar or scrollbar. |
| `min` | number | Lower bound of a progress bar or scrollbar. |
| `texture_density` | number | Pixel density of the texture relative to the interface scale. `2` means the image is drawn at half its pixel size. |
| `portrait_texture` | expression | Texture of a rendered character portrait. |
| `entity_instance` | expression | Entity instance drawn by a 3D widget. |
| `mask` | texture | Mask texture; where the mask is opaque the widget is drawn. |
| `fonttintcolor` | colour | Tint applied to the text glyphs. |
| `invertprogress` | bool | Fill the bar from the other end. |
| `mirror` | flags | Mirror the widget's texture. |
| `frame` | int | Index of the sprite-sheet frame to draw. |
| `camera_position` | vector3 | Camera position for a widget that renders an entity. |
| `progresstexture` | texture | Texture used for the filled part of a progress bar. |
| `fontsize` | int | Font size in interface pixels. |
| `animate_negative_changes` | bool | Animate a decrease as well as an increase. |
| `default_format` | string | Formatting string applied to the whole text, for example `"#b"` for bold. |
| `on_finish` | expression | Called when the animation state finishes. |
| `elide` | token | Where to cut the string when it does not fit. |
| `draggable_behavior` | block | Drag-and-drop source configuration. |
| `drop_target` | block | Drag-and-drop target configuration. |
| `datamodel_reuse_widgets` | bool | Reuse item widgets between data model refreshes instead of recreating them. |
| `direction` | token | Main axis of a layout container, a progress bar or a scrollbar. |
| `align` | flags | Horizontal and vertical alignment of the text inside its box. |
| `portrait_button` | block | Button configuration wrapped around a portrait. |
| `noprogresstexture` | texture | Texture used for the empty part of a progress bar. |
| `translate_uv` | vector2 | Offset applied to the texture coordinates. |
| `position_x` | number |  |
| `cameracontrolwidget` | block | Block-valued property. |
| `fittype` | token | How the texture is fitted into its rectangle. |
| `camera_fov_y_degrees` | float | Vertical field of view of the widget's camera. |
| `camera_near_far` | vector2 | Near and far clip planes of the widget's camera. |
| `camera_look_at` | vector3 | Point the widget's camera looks at. |
| `shaderfile` | texture | Path of the shader used by the draw type. |
| `effectname` | string | Name of a named effect inside `shaderfile`. |
| `fontsize_min` | int | Smallest size the text may shrink to when the box is too small. |
| `checked` | bool | State of a checkbutton. |
| `spacing` | number | Gap in pixels between the children of a layout container. |
| `marker` | block | Widget used as the marker on a progress bar. |
| `datacontext_from_model` | block | Push a data model entry into the data context of a child. |
| `click_modifiers` | block | Click handlers selected by the modifier keys held down. The block keys are `ondefault`, `onshift`, `onctrl` and `onalt`, plus the matching `*_input_action` variants. |
| `framesize` | vector2 | Size of one frame in a sprite sheet. |
| `trigger_when` | expression | Condition that starts or stops an animation state. |
| `distribute_visual_state` | bool | Pass the button's hover/press state down to child widgets. |
| `inherit_visual_state` | bool | Take the visual state from the parent button instead of tracking the pointer directly. |

## `modify_texture` sub-object

A second texture composited over the widget's main texture, with its own transform and blending. Declare several and address them by `name` from animations.

| Key | Meaning | Example |
|---|---|---|
| `blend_mode` | Compositing mode. | `blend_mode = alphamultiply` |
| `spriteType` | How the image is mapped onto the rectangle. | `spriteType = Corneredstretched` |
| `spriteborder` | Nine-slice border inset. | `spriteborder = { 0 0 }` |
| `texture` | Image path. | `texture = "gfx/interface/masks/fade_horizontal_center.dds"` |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Key | Meaning | Example |
|---|---|---|
| `alpha` | Target opacity, 0..1. | `alpha = 1` |
| `bezier` | Bézier control points, `{ x1 y1 x2 y2 }`. | `bezier = { 0.8 0 1 1 }` |
| `delay` | Delay before the state starts, in seconds. | `delay = 1.45` |
| `duration` | Length of the animation in seconds. | `duration = 0.25` |
| `name` | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. | `name = 1` |
| `next` | State to play when this one finishes. | `next = 2` |
| `on_finish` | Expression run when the state finishes. | `on_finish = "[GameSetup.OnStart]"` |
| `on_start` | Expression run when the state starts. | `on_start = "[PdxGuiTriggerAllAnimations('main_menu_start')]"` |
| `position` | Target position, `{ x y }`. | `position = { 50 0 }` |
| `position_x` | Target position on the x axis only. | `position_x = -300` |
| `position_y` | Target position on the y axis only. | `position_y = 0` |
| `scale` | Target uniform scale. | `scale = 10` |
| `size` | Target size, `{ w h }`. | `size = { 55 55 }` |
| `start_sound` | Sound played when the state starts. |  |
| `trigger_on_create` | Play the state when the widget is created. | `trigger_on_create = yes` |
| `trigger_when` | Expression that starts the state automatically. | `trigger_when = "[GetPlayer.IsInvolvedInActiveConflict]"` |

## Notes

Every other kind inherits everything documented under **Common properties**.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
