# Properties by widget kind

Everything outside the [common set](common-properties.md): the properties that belong to a particular kind, to a family of kinds, or to a sub-object.

The **Where** column lists the kinds that accept the property in the shipped interface. A property may be accepted by more kinds without being used there.

## Widget properties

| Property | Value type | Where | Uses | Meaning |
|---|---|---|---|---|
| `active_item` | slot | `dropDown` | 4 | Reserved child slot; the engine supplies the widget. |
| `addcolumn` | number | `container`, `fixedgridbox`, `flowcontainer` | 87 | Append a column of the given width to a grid box. |
| `addrow` | number | `container`, `fixedgridbox`, `flowcontainer` | 85 | Append a row of the given height to a grid box. |
| `align` | flags | 11 kinds | 3,426 | Horizontal and vertical alignment of the text inside its box. |
| `animate_negative_changes` | bool | `progressbar`, `widget` | 16 | Animate a decrease as well as an increase. |
| `autoresizescrollarea` | bool | `scrollarea` | 1 | Let the scroll area resize itself to its content. |
| `axis` | slot | `widget` | 4 | Reserved child slot; the engine supplies the widget. |
| `bottomtotop` | bool | `flowcontainer` | 1 | Lay the container out bottom to top. |
| `buttonText` | block | `button` | 11 | Configures the label of a `button`. The block takes the text properties (`text`, `fontsize`, `align`, ...) plus a `block "text"` slot so a derived type can replace the label. |
| `button_trigger` | token | `button` | 10 | Which gesture fires `onclick`. |
| `camera_fov_y_degrees` | float | `button`, `icon`, `widget` | 7 | Vertical field of view of the widget's camera. |
| `camera_look_at` | vector3 | `button`, `icon`, `widget` | 7 | Point the widget's camera looks at. |
| `camera_near_far` | vector2 | `button`, `icon`, `widget` | 7 | Near and far clip planes of the widget's camera. |
| `camera_position` | vector3 | `button`, `icon`, `widget` | 14 | Camera position for a widget that renders an entity. |
| `cameracontrolwidget` | block | `widget` | 1 | Block-valued property. |
| `checked` | bool | `button_group`, `checkbutton`, `hbox`, `widget` | 63 | State of a checkbutton. |
| `click_modifiers` | block | `button`, `widget` | 16 | Click handlers selected by the modifier keys held down. The block keys are `ondefault`, `onshift`, `onctrl` and `onalt`, plus the matching `*_input_action` variants. |
| `clicksound` | string | `button` | 31 | Sound played on click. Accepts a data-binding expression. |
| `close_sound` | string | `dropDown` | 1 | Sound played when the widget closes. |
| `coat_of_arms_slot` | expression | `icon` | 3 | Coat-of-arms slot whose texture the widget should display. |
| `cursorcolor` | colour | `editbox` | 1 | Colour of the text cursor. |
| `datacontext_from_model` | block | `button`, `flowcontainer`, `icon`, `widget` | 5 | Push a data model entry into the data context of a child. |
| `datamodel` | expression | 13 kinds | 956 | Feeds a collection into a data-driven container, which then creates one `item` child per entry. |
| `datamodel_reuse_widgets` | bool | `dynamicgridbox`, `fixedgridbox`, `flowcontainer`, `widget` | 14 | Reuse item widgets between data model refreshes instead of recreating them. |
| `datamodel_wrap` | int | `dynamicgridbox`, `fixedgridbox`, `flowcontainer` | 116 | Number of columns the data model is wrapped into. |
| `dec_button` | slot | `scrollbar` | 16 | Reserved child slot; the engine supplies the widget. |
| `default_format` | string | `button`, `container`, `editbox`, `flowcontainer`, `hbox`, `textbox`, `widget` | 639 | Formatting string applied to the whole text, for example `"#b"` for bold. |
| `delay` | float | `container`, `icon`, `widget` | 8 | Delay before the animation state starts, in seconds. |
| `direction` | token | `flowcontainer`, `progressbar`, `scrollbar`, `widget` | 1,712 | Main axis of a layout container, a progress bar or a scrollbar. |
| `disableframe` | int | `button` | 3 | Frame index for the disabled state. |
| `distribute_visual_state` | bool | `button`, `widget` | 19 | Pass the button's hover/press state down to child widgets. |
| `down` | bool | `button` | 42 | Force the button into its pressed visual state, typically bound to whether a tab is selected. |
| `downframe` | int | `button` | 10 | Frame index for the pressed state. |
| `downhoverframe` | int | `button` | 4 | Sprite-sheet frame for the pressed-and-hovered state. |
| `downpressedframe` | int | `button` | 4 | Sprite-sheet frame for the pressed state of a down button. |
| `duration` | float | `icon` | 7 | Length of an animation state in seconds. |
| `effectname` | string | `background`, `button`, `icon`, `piechart`, `widget` | 53 | Name of a named effect inside `shaderfile`. |
| `elide` | token | `button`, `flowcontainer`, `textbox`, `widget`, `window` | 982 | Where to cut the string when it does not fit. |
| `enabled_post_effects` | flags | `button`, `icon` | 3 | Post effects enabled for the entity widget. |
| `endangle` | float | `piechart` | 1 | End angle of a pie slice. |
| `entity_enable_sound` | bool | `icon` | 3 | Play the entity's configured sounds. |
| `entity_instance` | expression | `button`, `icon`, `widget` | 47 | Entity instance drawn by a 3D widget. |
| `fade_from_point` | vector2 | `icon` | 1 | Start point of a fade gradient. |
| `fade_to_point` | vector2 | `icon` | 1 | End point of a fade gradient. |
| `fittype` | token | `background`, `icon`, `widget` | 57 | How the texture is fitted into its rectangle. |
| `flipdirection` | bool | `dynamicgridbox`, `fixedgridbox`, `flowcontainer` | 138 | Reverse the order in which children are laid out. |
| `font` | string | `button`, `textbox` | 48 | Font family name, as declared in the game's font files. |
| `fontcolor` | colour | `textbox` | 5 | Text colour. |
| `fontsize` | int | `button`, `editbox`, `textbox`, `widget` | 142 | Font size in interface pixels. |
| `fontsize_min` | int | `button`, `flowcontainer`, `textbox`, `widget`, `window` | 689 | Smallest size the text may shrink to when the box is too small. |
| `fonttintcolor` | colour | `flowcontainer`, `textbox`, `widget` | 68 | Tint applied to the text glyphs. |
| `frame` | int | `background`, `button`, `container`, `flowcontainer`, `icon`, `piechart`, `progressbar`, `widget` | 146 | Index of the sprite-sheet frame to draw. |
| `framesize` | vector2 | 9 kinds | 146 | Size of one frame in a sprite sheet. |
| `gfx_environment_file` | texture | `button`, `icon` | 6 | Lighting environment used when rendering an entity widget. |
| `gfxtype` | token | 12 kinds | 59 | Name of the engine draw type used for the widget, for example `buttongfx`, `windowgfx` or `progressbargfx`. |
| `icon` | token | `texticon` | 446 | Name of the icon embedded in a `texticon` string. |
| `ignore_unset_buttons` | flags | `button` | 1 | Mouse buttons treated as "not pressed" for the visual state. |
| `inc_button` | slot | `scrollbar` | 16 | Reserved child slot; the engine supplies the widget. |
| `inherit_visual_state` | bool | `button`, `widget` | 16 | Take the visual state from the parent button instead of tracking the pointer directly. |
| `intersectionmask` | bool | `button` | 2 | Use the widget's texture as a hit-test mask. |
| `invertprogress` | bool | `button`, `widget` | 10 | Fill the bar from the other end. |
| `item` | slot | 10 kinds | 815 | The widget instantiated once per data model entry. |
| `layoutanchor` | token | `dynamicgridbox`, `fixedgridbox`, `flowcontainer` | 11 | Which corner of a grid box new cells are filled from. |
| `line_type` | token | `line` | 2 | Interpolation used to draw the line. |
| `list` | block | `dropDown` | 4 | List configuration block. |
| `loop` | bool | `icon` | 2 | Loop the video or animation. |
| `marker` | block | `progressbar`, `widget` | 13 | Widget used as the marker on a progress bar. |
| `mask` | texture | `line`, `piechart`, `treemapslice`, `widget` | 33 | Mask texture; where the mask is opaque the widget is drawn. |
| `max` | number | `flowcontainer`, `progressbar`, `scrollbar`, `widget` | 254 | Upper bound of a progress bar or scrollbar. |
| `maxcharacters` | int | `editbox`, `hbox`, `textbox`, `vbox` | 34 | Maximum number of characters accepted in an edit box. |
| `maxhorizontalslots` | int | `dynamicgridbox`, `fixedgridbox` | 4 | Number of columns in a grid box. |
| `maxverticalslots` | int | `container`, `fixedgridbox` | 6 | Number of rows in a grid box. |
| `min` | number | `flowcontainer`, `progressbar`, `scrollbar`, `widget` | 247 | Lower bound of a progress bar or scrollbar. |
| `mipmaplodbias` | float | `background`, `icon` | 4 | Bias applied when sampling the texture mip chain. |
| `mirror` | flags | `background`, `button`, `flowcontainer`, `icon`, `widget` | 67 | Mirror the widget's texture. |
| `movable` | bool | `minimap_window`, `widget`, `window` | 25 | Allow the player to drag the window. |
| `multiline` | bool | `editbox`, `textbox`, `vbox` | 540 | Allow the text to wrap onto several lines. |
| `noprogresstexture` | texture | `progressbar`, `widget` | 25 | Texture used for the empty part of a progress bar. |
| `onClick` | expression | `button` | 1 | One-off camel-cased spelling that appears in the shipped files; the engine name is `onclick`. |
| `on_finish` | expression | `container`, `widget` | 5 | Called when the animation state finishes. |
| `on_start` | expression | `button` | 4 | Called when the animation state starts. |
| `oneditingfinished` | expression | `editbox` | 1 | Older name for the edit-finished callback. |
| `onreturnpressed` | expression | `editbox`, `hbox`, `margin_widget`, `vbox` | 11 | Called when Enter is pressed in an edit box. |
| `onselectionchanged` | expression | `dropDown` | 12 | Called when the selection in a dropdown or list changes. |
| `ontextchanged` | expression | `editbox`, `hbox` | 5 | Called after the text of an edit box has changed. |
| `ontextedited` | expression | `editbox`, `hbox`, `vbox` | 28 | Called while the contents of an edit box change. |
| `onvaluechanged` | expression | `scrollbar` | 14 | Called when a scrollbar or slider value changes. |
| `open_sound` | string | `dropDown` | 1 | Sound played when the widget opens. |
| `overframe` | int | `button` | 6 | Frame index for the hover state. |
| `oversound` | string | `button` | 2 | Sound played on hover. |
| `page` | number | `scrollbar` | 1 | Increment applied by a page action on a scrollbar. |
| `password` | bool | `hbox` | 1 | Mask the contents of an edit box. |
| `plotpoints` | expression | `flowcontainer`, `plotline`, `vbox` | 85 | Series of points for a plot line. |
| `points` | block | `line` | 2 | List of points for a line, as repeated `{ x y }` entries. |
| `portrait_button` | block | `widget` | 2 | Button configuration wrapped around a portrait. |
| `portrait_texture` | expression | `widget` | 42 | Texture of a rendered character portrait. |
| `position_x` | number | `widget` | 2 |  |
| `preferscrollwidgetsize` | bool | `scrollarea` | 1 | Prefer the scroll widget's own size over the viewport's. |
| `progresstexture` | texture | `progressbar`, `widget` | 30 | Texture used for the filled part of a progress bar. |
| `raw_text` | string | 10 kinds | 2,232 | Text displayed without localisation lookup, usually to mix literals with data bindings. |
| `realtime` | bool | `icon` | 3 | Advance the animation in real time rather than game time. |
| `render_pass` | expression | `button`, `icon` | 3 | Render pass the entity widget is drawn in. |
| `reorder_on_mouse` | token | `minimap_window` | 1 | When a window should be brought to the front. |
| `resizable` | bool | `minimap_window`, `window` | 7 | Allow the player to resize the window. |
| `restrictparent_min` | bool | `hbox`, `vbox` | 4 | Do not let the parent shrink below this widget's minimum. |
| `rightclick_modifiers` | block | `button` | 3 | Modifier-keyed right-click handlers. |
| `rightclicksound` | string | `button` | 16 | Sound played on right click. |
| `righttoleft` | bool | `flowcontainer`, `hbox`, `overlappingitembox` | 16 | Lay the container out right to left. |
| `scrollbar_horizontal` | block | `scrollarea` | 16 | Block-valued property. |
| `scrollbar_vertical` | block | `scrollarea` | 43 | Block-valued property. |
| `scrollbaralign_horizontal` | token | `scrollarea` | 5 | Alignment of the horizontal scrollbar inside the area. |
| `scrollbaralign_vertical` | token | `scrollarea` | 10 | Alignment of the vertical scrollbar inside the area. |
| `scrollbarpolicy_horizontal` | token | `scrollarea` | 35 | When the horizontal scrollbar of a scroll area is shown. |
| `scrollbarpolicy_vertical` | token | `scrollarea` | 4 | When the vertical scrollbar of a scroll area is shown. |
| `scrollwidget` | slot | `scrollarea` | 45 | The widget that is scrolled; the actual content of a scroll area. |
| `selectedindex` | expression | `dropDown` | 5 | Bound index of the selected entry. |
| `set_parent_size_to_minimum` | bool | `hbox`, `vbox` | 6 | Size the parent from this widget's minimum size. |
| `setitemsizefromcell` | bool | `fixedgridbox` | 2 | Size each child from the grid cell rather than from the child's own `size`. |
| `shaderfile` | texture | 13 kinds | 47 | Path of the shader used by the draw type. |
| `skip_initial_animation` | bool | `progressbar` | 19 | Do not animate the first value change. |
| `slider` | slot | `scrollbar` | 17 | Reserved child slot; the engine supplies the widget. |
| `spacing` | number | `button`, `container`, `flowcontainer`, `hbox`, `overlappingitembox`, `vbox`, `widget` | 2,200 | Gap in pixels between the children of a layout container. |
| `spriteType` | token | `background`, `button`, `icon`, `progressbar`, `window` | 134 | How the texture is mapped onto the widget rectangle. |
| `spriteborder` | vector2 | `background`, `button`, `icon`, `progressbar`, `window` | 126 | Horizontal and vertical inset of the nine-slice border. |
| `spriteborder_bottom` | number | `background`, `button`, `icon` | 16 | Bottom border inset. |
| `spriteborder_left` | number | `background`, `icon` | 5 | Left border inset. |
| `spriteborder_right` | number | `background`, `icon` | 13 | Right border inset. |
| `spriteborder_top` | number | `background`, `icon`, `window` | 9 | Top border inset. |
| `start_sound` | block | `icon` | 1 | Sound played when the state starts. |
| `startangle` | float | `piechart` | 1 | Start angle of a pie slice. |
| `step` | number | `scrollbar` | 17 | Increment applied by the scrollbar's step action. |
| `text` | loc | 14 kinds | 6,243 | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. |
| `text_selectable` | bool | `textbox` | 2 | Allow the player to select and copy the text. |
| `text_validator` | token | `editbox` | 3 | Name of the validator applied to an edit box, for example `int`, `float` or `hex_color`. |
| `texture` | texture | 15 kinds | 3,055 | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. |
| `texture_density` | number | `background`, `icon`, `progressbar`, `widget` | 158 | Pixel density of the texture relative to the interface scale. `2` means the image is drawn at half its pixel size. |
| `tintcolor` | colour | `background`, `button`, `icon`, `progressbar` | 41 | Tint applied to the drawn texture. |
| `track` | slot | `scrollbar` | 16 | Reserved child slot; the engine supplies the widget. |
| `translate_uv` | vector2 | `widget` | 2 | Offset applied to the texture coordinates. |
| `trigger_on_create` | bool | `icon` | 1 | Play the animation state as soon as the widget is created. |
| `trigger_when` | expression | `widget` | 1 | Condition that starts or stops an animation state. |
| `upframe` | int | `button` | 19 | Frame index for the idle state. |
| `uphoverframe` | int | `button` | 11 | Sprite-sheet frame for the idle-but-hovered state. |
| `uppressedframe` | int | `button` | 11 | Sprite-sheet frame for the idle-but-pressed state. |
| `value` | number | 9 kinds | 366 | Current value of a progress bar or scrollbar. |
| `video` | texture | `icon` | 5 | Video file played by the widget. |
| `wheelstep` | number | `scrollbar` | 12 | Increment applied by one mouse-wheel notch. |
| `width` | float | `line`, `plotline` | 17 | Stroke width for a line or plot line. |
| `wrap_count` | int | `flowcontainer` | 61 | Fixed number of children per row in a flow container. |

## `draggable_behavior` sub-object

Marks the widget as a drag source and describes the widget that follows the pointer.

| Property | Value type | Meaning |
|---|---|---|
| `drag_widget` | block | Widget tree that follows the cursor during the drag. |
| `draggable_id` | string | String id matched against `accept_draggable_id` on drop targets. |

## `drop_target` sub-object

Marks the widget as a drop target for drags with a matching id.

| Property | Value type | Meaning |
|---|---|---|
| `accept_draggable_id` | string | String id this target accepts. |
| `on_receive_drop` | expression | Expression run when a matching drag is dropped. |

## `iconsize` sub-object

Presentation of the icons embedded in a `texticon` string.

| Property | Value type | Meaning |
|---|---|---|
| `fontsize` | int | Font size the icon is sized against. |
| `offset` | vector2 | Offset from the text baseline, `{ x y }`. |
| `size` | vector2 | Drawn size, `{ w h }`. |
| `texture` | texture | Image path of the icon. |

## `modify_texture` sub-object

A second texture composited over the widget's main texture, with its own transform and blending. Declare several and address them by `name` from animations.

| Property | Value type | Meaning |
|---|---|---|
| `alpha` | float | Opacity, 0..1. |
| `blend_mode` | token | Compositing mode. |
| `color` | colour | Colour multiplier, `{ r g b a }`. |
| `frame` | int | Sprite-sheet frame index. |
| `framesize` | vector2 | Size of one sprite-sheet frame. |
| `mirror` | flags | Mirror flags. |
| `name` | string | Name used by animation states to target this layer. |
| `rotate_uv` | float | Texture-coordinate rotation in degrees. |
| `spriteType` | token | How the image is mapped onto the rectangle. |
| `spriteborder` | vector2 | Nine-slice border inset. |
| `spriteborder_bottom` | number | Bottom border inset. |
| `spriteborder_left` | number | Left border inset. |
| `spriteborder_right` | number | Right border inset. |
| `spriteborder_top` | number | Top border inset. |
| `texture` | texture | Image path. |
| `texture_density` | number | Pixel density relative to interface scale. |
| `translate_uv` | vector2 | Texture-coordinate offset. |
| `visible` | bool | Whether this layer is drawn. |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Property | Value type | Meaning |
|---|---|---|
| `alpha` | float | Target opacity, 0..1. |
| `animation` | token | Named animation curve description. |
| `bezier` | colour | Bézier control points, `{ x1 y1 x2 y2 }`. |
| `delay` | float | Delay before the state starts, in seconds. |
| `duration` | float | Length of the animation in seconds. |
| `frame` | int | Target sprite-sheet frame index. |
| `modify_texture` | block | Per-state overrides for a modify texture, matched by `name`. |
| `name` | string | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. |
| `next` | token | State to play when this one finishes. |
| `on_finish` | expression | Expression run when the state finishes. |
| `on_start` | expression | Expression run when the state starts. |
| `position` | vector2 | Target position, `{ x y }`. |
| `position_x` | number | Target position on the x axis only. |
| `position_y` | number | Target position on the y axis only. |
| `scale` | float | Target uniform scale. |
| `size` | vector2 | Target size, `{ w h }`. |
| `start_sound` | block | Sound played when the state starts. |
| `trigger_on_create` | bool | Play the state when the widget is created. |
| `trigger_when` | expression | Expression that starts the state automatically. |

## Engine properties not used by the shipped interface

The engine accepts these, but no shipped `.gui` file sets them. They are listed for completeness and for mods.

| Property | Value type | Meaning |
|---|---|---|
| `accept_tabs` | bool | Let the Tab key insert a tab character instead of moving focus. |
| `activeframe` | int | Frame index for the active/toggled state. |
| `animation` | token | Named animation curve type used by the state. |
| `autoresize_axis` | token | Which axes an auto-resizing text widget may grow on. |
| `autoresizeviewport` | bool | Let the viewport resize to its content. |
| `background` | widget | A texture drawn behind the widget. Declared as a child block. |
| `blend_mode` | token | Blend mode used when compositing the texture. |
| `clamp_pan_position` | bool | Keep the pan position inside the content bounds. |
| `draggable_by` | flags | Mouse buttons that pan a zoom area. |
| `enable_frame_blend` | bool | Blend between sprite-sheet frames instead of switching instantly. |
| `end_sound` | block | Sound played when the state ends. |
| `fontsize_range_end` | int | Upper bound of an automatically scaled size range. |
| `fontsize_range_start` | int | Lower bound of an automatically scaled size range. |
| `format_override` | block | Override one named text format for this widget. |
| `ignore_gui_scale` | bool | Opt the widget out of the interface scale factor. |
| `ignore_gui_scale_position` | bool | Keep the widget's position unscaled while its size still scales. |
| `indent` | number | Indentation applied per tree level. |
| `line_breaking_characters` | string | Extra characters treated as line-break opportunities. |
| `next` | token | Name of the state to play when this one finishes. |
| `on_expanded` | expression | Called when a collapsing section opens or closes. |
| `oncolorchanged` | expression | Called while the colour picker selection changes. |
| `oncoloredited` | expression | Called when a colour picker edit is committed. |
| `pan_position` | vector2 | Current pan offset of a zoom area. |
| `progress_change_to_duration_curve` | block | Curve mapping the size of a change to the animation duration. |
| `rotate_uv` | float | Rotation applied to the texture coordinates, in degrees. |
| `sticky` | bool | Keep the scrollbar at its value when the content changes. |
| `thickness` | float | Stroke width of a line, in pixels. |
| `tracknavigation` | token | Whether clicking the scrollbar track pages or jumps. |
| `zoom` | float | Current zoom factor of a zoom area. |
| `zoom_max` | float | Largest allowed zoom factor. |
| `zoom_min` | float | Smallest allowed zoom factor. |
| `zoom_step` | float | Zoom increment per notch. |
