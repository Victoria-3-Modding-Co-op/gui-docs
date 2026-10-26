# container

A widget whose children keep their own absolute positions.

## At a glance

- **Kind:** `container`
- **Category:** Layout
- **Children:** accepted, positioned by their own anchors
- **Used in the shipped interface:** 1,494 times

## When to use it

Holds children at absolute positions. Unlike `widget`, a container participates in layout as a box and can be told to ignore hidden children when sizing itself.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `tooltipwidget` | Custom tooltip body. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `datamodel` | expression | Feeds a collection into a data-driven container, which then creates one `item` child per entry. | `datamodel = "[State.AccessCappedRuralBuildings]"` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. |
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. |
| `raw_text` | string | Text displayed without localisation lookup, usually to mix literals with data bindings. |
| `value` | number | Current value of a progress bar or scrollbar. |
| `default_format` | string | Formatting string applied to the whole text, for example `"#b"` for bold. |
| `align` | flags | Horizontal and vertical alignment of the text inside its box. |
| `maxverticalslots` | int | Number of rows in a grid box. |
| `addcolumn` | number | Append a column of the given width to a grid box. |
| `addrow` | number | Append a row of the given height to a grid box. |
| `delay` | float | Delay before the animation state starts, in seconds. |
| `on_finish` | expression | Called when the animation state finishes. |
| `spacing` | number | Gap in pixels between the children of a layout container. |
| `frame` | int | Index of the sprite-sheet frame to draw. |
| `framesize` | vector2 | Size of one frame in a sprite sheet. |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Key | Meaning | Example |
|---|---|---|
| `alpha` | Target opacity, 0..1. | `alpha = 1` |
| `delay` | Delay before the state starts, in seconds. | `delay = 1.5` |
| `duration` | Length of the animation in seconds. | `duration = 0.2` |
| `name` | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. | `name = show` |
| `next` | State to play when this one finishes. | `next = b` |
| `on_start` | Expression run when the state starts. | `on_start = "[BudgetPanel.GetMapModeList.SelectByKey('mm_state')]"` |
| `position_x` | Target position on the x axis only. | `position_x = 388` |
| `position_y` | Target position on the y axis only. | `position_y = -50` |
| `start_sound` | Sound played when the state starts. |  |
| `trigger_on_create` | Play the state when the widget is created. | `trigger_on_create = yes` |
| `trigger_when` | Expression that starts the state automatically. | `trigger_when = "[PoliticalMovement.IsInsurrectionary]"` |

## Notes

Because children are positioned rather than stacked, `container` is the usual base for hand-placed layouts.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
