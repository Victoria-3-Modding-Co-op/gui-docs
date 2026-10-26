# Common properties

These properties are accepted by every widget kind. They are the same names everywhere; a kind may add constraints on top, noted on its own page.

## Geometry

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `size` | vector2 | Width and height of the widget. Terms may be absolute pixels, a percentage of the parent, or `-1` in one axis to mean "use the widget's natural size on that axis". Fractional values are accepted. | `size = { 0 30 }` |
| `position` | vector2 | Offset of the widget from the anchor point given by `parentanchor`. | `position = { 23 0 }` |
| `minimumsize` | vector2 | Lower bound applied by layout containers. | `minimumsize = { -1 35 }` |
| `maximumsize` | vector2 | Upper bound applied by layout containers. `-1` means unbounded on that axis. | `maximumsize = { @spreadsheet_width -1 }` |
| `preferredsize` | vector2 | Size the widget asks for when a layout container is distributing space. |  |
| `min_width` | number | Minimum width in pixels. Shorthand for the x component of `minimumsize`, and takes precedence in flow layouts. | `min_width = 300` |
| `max_width` | number | Maximum width in pixels. | `max_width = 680` |
| `min_height` | number | Minimum height in pixels. |  |
| `max_height` | number | Maximum height in pixels. | `max_height = 44` |
| `scale` | float | Uniform scale factor applied to the widget and its children. | `scale = "[CharacterPanelViewer.GetBackgroundScale]"` |

## Anchoring

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `parentanchor` | flags | The point of the parent that `position` is measured from, and the point the widget is aligned to. | `parentanchor = center` |
| `widgetanchor` | flags | The point *of this widget* that is placed at the position derived from `parentanchor`. | `widgetanchor = top\|right` |

## Layout participation

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `layoutpolicy_horizontal` | token | How the widget competes for horizontal space inside a layout container. | `layoutpolicy_horizontal = expanding` |
| `layoutpolicy_vertical` | token | Vertical counterpart of `layoutpolicy_horizontal`. | `layoutpolicy_vertical = expanding` |
| `layoutstretchfactor_horizontal` | int | Share of the leftover horizontal space, relative to sibling widgets with the same layout policy. | `layoutstretchfactor_horizontal = 4` |
| `layoutstretchfactor_vertical` | int | Vertical counterpart of `layoutstretchfactor_horizontal`. |  |
| `margin` | vector2 | Horizontal and vertical margin applied inside the widget's own rectangle. | `margin = { 10 0 }` |
| `margin_left` | number | Left margin in pixels. | `margin_left = 30` |
| `margin_right` | number | Right margin in pixels. | `margin_right = 5` |
| `margin_top` | number | Top margin in pixels. | `margin_top = 5` |
| `margin_bottom` | number | Bottom margin in pixels. | `margin_bottom = 8` |
| `autoresize` | bool | Let the widget size itself from its content instead of from `size`. | `autoresize = yes` |
| `resizeparent` | bool | Let the widget push its own size onto its parent. | `resizeparent = yes` |
| `ignoreinvisible` | bool | Ignore hidden children when computing layout, so they take no space. | `ignoreinvisible = yes` |
| `ignore_layout` | bool | Exclude the widget from its parent's layout entirely. |  |

## Identity and visibility

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `name` | string | Widget name, used by `PdxGuiWidget.AccessChild('name')` and by `blockoverride` targeting. | `name = "tabs"` |
| `widgetid` | string | Stable identifier used by data bindings and by the debug widget inspector. | `widgetid = "[Law.GetGroup.GetKey]"` |
| `visible` | bool | Whether the widget is drawn. Accepts a data-binding expression. | `visible = "[Not(Battle.HasEnded)]"` |
| `visible_at_creation` | bool | Initial visibility before the first data update runs. | `visible_at_creation = no` |
| `enabled` | bool | Whether the widget accepts input. A disabled widget is drawn in its disabled state. | `enabled = "[NationalizeBuildingGroup.IsNationalizable]"` |
| `alwaystransparent` | bool | Let mouse input pass through the widget. The usual way to make a decoration non-interactive. | `alwaystransparent = yes` |
| `allow_outside` | bool | Allow children to be drawn outside the widget's rectangle. | `allow_outside = yes` |
| `scissor` | bool | Clip children to the widget's rectangle. | `scissor = yes` |
| `layer` | token | Named draw layer. Higher layers draw on top of lower ones. | `layer = layer_error_deer` |
| `ignore_in_debug_draw` | bool | Hide the widget in the debug draw overlay, so guides and markers do not clutter the debug view. | `ignore_in_debug_draw = yes` |

## Input and focus

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `input_action` | string | Named input action that activates the widget, for gamepad and keyboard navigation. | `input_action = "construction_queue"` |
| `shortcut` | string | Name of a shortcut from the `.shortcuts` file that activates the widget. | `shortcut = "close_window"` |
| `filter_mouse` | flags | Restrict which mouse buttons the widget reacts to. | `filter_mouse = right` |
| `focuspolicy` | token | How the widget can receive keyboard focus. | `focuspolicy = all` |
| `focus_on_visible` | bool | Give the widget focus when it becomes visible. | `focus_on_visible = yes` |
| `taborder` | int | Order in which Tab moves focus. |  |
| `tabfocusroot` | bool | Start a new Tab cycle at this widget. |  |
| `modal` | bool | Block input to everything underneath while this widget is visible. | `modal = yes` |
| `modality` | token | What a modal widget blocks: `all` input, or interface input only. | `modality = all` |

## Tooltips

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `tooltip` | loc | Tooltip text: a localisation key or a data-binding expression returning one. | `tooltip = "BATTLE_OFFENSE_TOOLTIP"` |
| `raw_tooltip` | string | Tooltip text used verbatim, without localisation lookup. | `raw_tooltip = "todo"` |
| `tooltipwidget` | slot | Custom widget shown as the tooltip. |  |
| `tooltip_type` | token | How the tooltip locks and where it anchors. |  |
| `tooltip_offset` | vector2 | Offset of the tooltip from its anchor. |  |
| `tooltip_widgetanchor` | flags | Anchor point of the tooltip itself. | `tooltip_widgetanchor = top\|right` |
| `tooltip_parentanchor` | flags | Anchor point of the widget the tooltip is attached to. | `tooltip_parentanchor = top\|left` |
| `tooltip_horizontalbehavior` | token | What the tooltip does when it would leave the screen horizontally. |  |
| `tooltip_verticalbehavior` | token | What the tooltip does when it would leave the screen vertically. |  |
| `tooltip_enabled` | bool | Turn the tooltip on or off without removing it. | `tooltip_enabled = "[Not(JominiServer.IsSameVersion)]"` |
| `tooltip_delayed` | bool | Use the delayed tooltip timer. |  |

## Data binding

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `datacontext` | expression | Sets the object that `[...]` expressions in this widget and its children are evaluated against. | `datacontext = "[ShipConstruction.GetShipType]"` |
| `max_update_rate` | int | Minimum number of frames between data refreshes for this widget. | `max_update_rate = 10` |
| `force_data_properties_update` | bool | Refresh data properties even when the data context has not changed. | `force_data_properties_update = yes` |
| `inherit_data_context` | bool | Reuse the parent's data context instead of pushing a new one. |  |

## Sub-objects

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `state` | block | Declares one animation state. A widget may declare many; each is addressed by `name` from script with `TriggerAnimation`. See the `state` sub-object in the reference for every key. |  |
| `modify_texture` | block | Second texture drawn over the main one, with its own `texture`, `spriteType`, `blend_mode`, offset and alpha. Several may be declared; they are addressed by `name` from animations. |  |

## Drawing

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `alpha` | float | Opacity from 0 to 1. | `alpha = "[TransparentIfTrue(CharacterTrait.IsDisabled)]"` |
| `color` | colour | Colour tint applied to the widget. | `color = "[MilitaryFormation.GetCountry.GetMapColor]"` |

## Events

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `onclick` | expression | Called when the widget is clicked. | `onclick = "[InformationPanel.SelectTab('default')]"` |
| `onrightclick` | expression | Called on a right click. | `onrightclick = "[RightClickMenuManager.ShowForState(State.AccessSelf)]"` |
| `ondoubleclick` | expression | Called on a double click. | `ondoubleclick = "[SaveGameItem.SelectAndLoad]"` |
| `onpressed` | expression | Called when the mouse button goes down over the widget. |  |
| `onreleased` | expression | Called when the mouse button comes up. |  |
| `onmouseenter` | expression | Called when the pointer enters the widget. |  |
| `onmouseleave` | expression | Called when the pointer leaves the widget. |  |
| `onmousehierarchyenter` | expression | Called when the pointer enters the widget or any of its children. | `onmousehierarchyenter = "[SetTempMapModeByKey('mm_literacy')]"` |
| `onmousehierarchyleave` | expression | Called when the pointer leaves the widget and all of its children. | `onmousehierarchyleave = "[RemoveTempMapMode]"` |
