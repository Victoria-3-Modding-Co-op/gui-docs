# flowcontainer

Wraps its children onto new rows or columns when it runs out of room.

## At a glance

- **Kind:** `flowcontainer`
- **Category:** Layout
- **Children:** accepted, wrapped into rows
- **Used in the shipped interface:** 3,517 times

## When to use it

A box that wraps: children are placed along `direction` until the container runs out of room, then a new row or column starts.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `item` | Instantiated once per data model entry. |
| `tooltipwidget` | Custom tooltip body. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `spacing` | number | Gap in pixels between the children of a layout container. | `spacing = 10` |
| `direction` | token | Main axis of a layout container, a progress bar or a scrollbar. | `direction = vertical` |
| `datamodel` | expression | Feeds a collection into a data-driven container, which then creates one `item` child per entry. | `datamodel = "[AchievementPopup.AccessJustUnlockedAchievements]"` |
| `wrap_count` | int | Fixed number of children per row in a flow container. | `wrap_count = 2` |
| `righttoleft` | bool | Lay the container out right to left. | `righttoleft = yes` |
| `datamodel_reuse_widgets` | bool | Reuse item widgets between data model refreshes instead of recreating them. | `datamodel_reuse_widgets = yes` |
| `datacontext_from_model` | block | Push a data model entry into the data context of a child. |  |
| `bottomtotop` | bool | Lay the container out bottom to top. | `bottomtotop = yes` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. |
| `plotpoints` | expression | Series of points for a plot line. |
| `raw_text` | string | Text displayed without localisation lookup, usually to mix literals with data bindings. |
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. |
| `value` | number | Current value of a progress bar or scrollbar. |
| `fontsize_min` | int | Smallest size the text may shrink to when the box is too small. |
| `elide` | token | Where to cut the string when it does not fit. |
| `addcolumn` | number | Append a column of the given width to a grid box. |
| `addrow` | number | Append a row of the given height to a grid box. |
| `mirror` | flags | Mirror the widget's texture. |
| `layoutanchor` | token | Which corner of a grid box new cells are filled from. |
| `min` | number | Lower bound of a progress bar or scrollbar. |
| `max` | number | Upper bound of a progress bar or scrollbar. |
| `default_format` | string | Formatting string applied to the whole text, for example `"#b"` for bold. |
| `fonttintcolor` | colour | Tint applied to the text glyphs. |
| `datamodel_wrap` | int | Number of columns the data model is wrapped into. |
| `flipdirection` | bool | Reverse the order in which children are laid out. |
| `align` | flags | Horizontal and vertical alignment of the text inside its box. |
| `frame` | int | Index of the sprite-sheet frame to draw. |
| `framesize` | vector2 | Size of one frame in a sprite sheet. |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Key | Meaning | Example |
|---|---|---|
| `alpha` | Target opacity, 0..1. | `alpha = 1` |
| `delay` | Delay before the state starts, in seconds. | `delay = 2` |
| `duration` | Length of the animation in seconds. | `duration = 0.5` |
| `name` | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. | `name = _show` |
| `next` | State to play when this one finishes. | `next = game_over_screen_info1_b` |
| `on_start` | Expression run when the state starts. | `on_start = "[BudgetPanel.GetMapModeList.SelectDefault]"` |
| `position` | Target position, `{ x y }`. | `position = { 180 -20 }` |
| `position_x` | Target position on the x axis only. | `position_x = -1500` |
| `position_y` | Target position on the y axis only. | `position_y = 10` |
| `trigger_when` | Expression that starts the state automatically. | `trigger_when = "[Not(Or(And(GreaterThan_CFixedPoint(Technology.GetProgress(GetPlayer.Self), '(CFixedPoint)0'), Not(Technology.HasResearchedTech(GetPlayer.Self))), GreaterThan_CFixedPoint(GetPlayer.GetMinWeeklyTechnologyProgressForTech(Technology.Self), '(CFixedPoint)0')))]"` |

## Notes

Use `wrap_count` to force a fixed number of items per row instead of letting the container decide.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
