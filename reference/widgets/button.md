# button

A clickable widget with over/down/disabled visual states.

## At a glance

- **Kind:** `button`
- **Category:** Interaction
- **Children:** accepted, positioned by their own anchors
- **Derives from:** `widget`
- **Used in the shipped interface:** 2,722 times

## When to use it

A clickable widget. It has separate visual states for idle, hover, pressed and disabled, driven by `upframe`, `overframe`, `downframe` and `disableframe`.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `tooltipwidget` | Custom tooltip body. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. | `text = "PAUSE_ALL_CONSTRUCTION_BUTTON"` |
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. | `texture = "[Company.GetCompanyType.GetIcon]"` |
| `raw_text` | string | Text displayed without localisation lookup, usually to mix literals with data bindings. | `raw_text = "Theocracy"` |
| `framesize` | vector2 | Size of one frame in a sprite sheet. | `framesize = "[GetMediumFlagFrameSize]"` |
| `font` | string | Font family name, as declared in the game's font files. | `font = "standard_font"` |
| `fontsize` | int | Font size in interface pixels. | `fontsize = 13` |
| `frame` | int | Index of the sprite-sheet frame to draw. | `frame = "[CoatOfArmsPreviewWindow.GetRandomFlagFrame('(uint32)0')]"` |
| `tintcolor` | colour | Tint applied to the drawn texture. | `tintcolor = { 0.3 0.3 0.3 0.1 }` |
| `clicksound` | string | Sound played on click. Accepts a data-binding expression. | `clicksound = "[SelectSound(InvasionPlannerPopup.HasNavalInvasionContext, 'event:/SFX/UI/Military/formation_actions_naval_invasion', 'event:/SFX/UI/Military/formation_actions_land_invasion')]"` |
| `align` | flags | Horizontal and vertical alignment of the text inside its box. | `align = hcenter\|nobaseline` |
| `effectname` | string | Name of a named effect inside `shaderfile`. | `effectname = "NoHighlight"` |
| `distribute_visual_state` | bool | Pass the button's hover/press state down to child widgets. | `distribute_visual_state = no` |
| `inherit_visual_state` | bool | Take the visual state from the parent button instead of tracking the pointer directly. | `inherit_visual_state = no` |
| `default_format` | string | Formatting string applied to the whole text, for example `"#b"` for bold. | `default_format = "#weak"` |
| `down` | bool | Force the button into its pressed visual state, typically bound to whether a tab is selected. | `down = "[ObjectsEqual(CountryDefinition.AccessSelf, GameSetup.GetSelectedTag)]"` |
| `gfxtype` | token | Name of the engine draw type used for the widget, for example `buttongfx`, `windowgfx` or `progressbargfx`. | `gfxtype = buttongfx` |
| `rightclicksound` | string | Sound played on right click. | `rightclicksound = "event:/SFX/UI/Military/naval_mission_settings_confirm"` |
| `click_modifiers` | block | Click handlers selected by the modifier keys held down. The block keys are `ondefault`, `onshift`, `onctrl` and `onalt`, plus the matching `*_input_action` variants. |  |
| `button_trigger` | token | Which gesture fires `onclick`. | `button_trigger = none` |
| `elide` | token | Where to cut the string when it does not fit. | `elide = right` |
| `spriteType` | token | How the texture is mapped onto the widget rectangle. | `spriteType = Corneredtiled` |
| `spriteborder` | vector2 | Horizontal and vertical inset of the nine-slice border. | `spriteborder = { 10 10 }` |
| `mirror` | flags | Mirror the widget's texture. | `mirror = vertical` |
| `rightclick_modifiers` | block | Modifier-keyed right-click handlers. |  |
| `upframe` | int | Frame index for the idle state. | `upframe = 1` |
| `overframe` | int | Frame index for the hover state. | `overframe = 2` |
| `downframe` | int | Frame index for the pressed state. | `downframe = 3` |
| `datacontext_from_model` | block | Push a data model entry into the data context of a child. |  |
| `shaderfile` | texture | Path of the shader used by the draw type. | `shaderfile = "gfx/FX/pdxgui_pushbutton.shader"` |
| `ignore_unset_buttons` | flags | Mouse buttons treated as "not pressed" for the visual state. | `ignore_unset_buttons = right` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `fontsize_min` | int | Smallest size the text may shrink to when the box is too small. |
| `buttonText` | block | Configures the label of a `button`. The block takes the text properties (`text`, `fontsize`, `align`, ...) plus a `block "text"` slot so a derived type can replace the label. |
| `uphoverframe` | int | Sprite-sheet frame for the idle-but-hovered state. |
| `uppressedframe` | int | Sprite-sheet frame for the idle-but-pressed state. |
| `spacing` | number | Gap in pixels between the children of a layout container. |
| `downhoverframe` | int | Sprite-sheet frame for the pressed-and-hovered state. |
| `downpressedframe` | int | Sprite-sheet frame for the pressed state of a down button. |
| `on_start` | expression | Called when the animation state starts. |
| `disableframe` | int | Frame index for the disabled state. |
| `datamodel` | expression | Feeds a collection into a data-driven container, which then creates one `item` child per entry. |
| `spriteborder_bottom` | number | Bottom border inset. |
| `intersectionmask` | bool | Use the widget's texture as a hit-test mask. |
| `oversound` | string | Sound played on hover. |
| `onClick` | expression | One-off camel-cased spelling that appears in the shipped files; the engine name is `onclick`. |
| `entity_instance` | expression | Entity instance drawn by a 3D widget. |
| `render_pass` | expression | Render pass the entity widget is drawn in. |
| `gfx_environment_file` | texture | Lighting environment used when rendering an entity widget. |
| `enabled_post_effects` | flags | Post effects enabled for the entity widget. |
| `camera_position` | vector3 | Camera position for a widget that renders an entity. |
| `camera_look_at` | vector3 | Point the widget's camera looks at. |
| `camera_fov_y_degrees` | float | Vertical field of view of the widget's camera. |
| `camera_near_far` | vector2 | Near and far clip planes of the widget's camera. |
| `value` | number | Current value of a progress bar or scrollbar. |
| `invertprogress` | bool | Fill the bar from the other end. |

## `modify_texture` sub-object

A second texture composited over the widget's main texture, with its own transform and blending. Declare several and address them by `name` from animations.

| Key | Meaning | Example |
|---|---|---|
| `alpha` | Opacity, 0..1. | `alpha = 0` |
| `blend_mode` | Compositing mode. | `blend_mode = add` |
| `name` | Name used by animation states to target this layer. | `name = "mouse_enter"` |
| `rotate_uv` | Texture-coordinate rotation in degrees. | `rotate_uv = 0` |
| `spriteType` | How the image is mapped onto the rectangle. | `spriteType = Corneredstretched` |
| `spriteborder` | Nine-slice border inset. | `spriteborder = { 0 0 }` |
| `texture` | Image path. | `texture = "gfx/interface/buttons/default_button_frame_mouse_enter.dds"` |
| `visible` | Whether this layer is drawn. | `visible = "[LensOption.IsActive]"` |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Key | Meaning | Example |
|---|---|---|
| `alpha` | Target opacity, 0..1. | `alpha = 0` |
| `delay` | Delay before the state starts, in seconds. | `delay = 1.5` |
| `duration` | Length of the animation in seconds. | `duration = 5` |
| `frame` | Target sprite-sheet frame index. | `frame = 1` |
| `modify_texture` | Per-state overrides for a modify texture, matched by `name`. |  |
| `name` | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. | `name = show` |
| `next` | State to play when this one finishes. | `next = remove` |
| `on_finish` | Expression run when the state finishes. | `on_finish = "[GUIAchievement.Remove]"` |
| `on_start` | Expression run when the state starts. | `on_start = "[PdxGuiWidget.FindChild('achievements_popup_icon').TriggerAnimation('1')]"` |
| `position` | Target position, `{ x y }`. | `position = { 0 0 }` |
| `scale` | Target uniform scale. | `scale = 0.5` |
| `size` | Target size, `{ w h }`. | `size = { 190 45 }` |
| `trigger_on_create` | Play the state when the widget is created. | `trigger_on_create = yes` |
| `trigger_when` | Expression that starts the state automatically. | `trigger_when = "[GetVariableSystem.Exists(Concatenate('map_mode_name_', MapModeList.GetSelectedMapMode.GetName))]"` |

## Notes

`onclick` is the usual action; `pressed`, `released` and `double_click` style callbacks exist next to it.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
