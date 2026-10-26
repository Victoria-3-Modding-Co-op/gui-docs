# hbox

Lays its children out horizontally.

## At a glance

- **Kind:** `hbox`
- **Category:** Layout
- **Children:** accepted, stacked by the container
- **Used in the shipped interface:** 871 times

## When to use it

Lays children out left to right (or right to left).

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `tooltipwidget` | Custom tooltip body. |
| `item` | Instantiated once per data model entry. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `spacing` | number | Gap in pixels between the children of a layout container. | `spacing = 10` |
| `datamodel` | expression | Feeds a collection into a data-driven container, which then creates one `item` child per entry. | `datamodel = "[State.AccessStateRegion.AccessTraits]"` |
| `set_parent_size_to_minimum` | bool | Size the parent from this widget's minimum size. | `set_parent_size_to_minimum = yes` |
| `righttoleft` | bool | Lay the container out right to left. | `righttoleft = yes` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. |
| `raw_text` | string | Text displayed without localisation lookup, usually to mix literals with data bindings. |
| `value` | number | Current value of a progress bar or scrollbar. |
| `checked` | bool | State of a checkbutton. |
| `onreturnpressed` | expression | Called when Enter is pressed in an edit box. |
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. |
| `maxcharacters` | int | Maximum number of characters accepted in an edit box. |
| `align` | flags | Horizontal and vertical alignment of the text inside its box. |
| `ontextchanged` | expression | Called after the text of an edit box has changed. |
| `default_format` | string | Formatting string applied to the whole text, for example `"#b"` for bold. |
| `ontextedited` | expression | Called while the contents of an edit box change. |
| `restrictparent_min` | bool | Do not let the parent shrink below this widget's minimum. |
| `password` | bool | Mask the contents of an edit box. |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Key | Meaning | Example |
|---|---|---|
| `alpha` | Target opacity, 0..1. | `alpha = 1` |
| `delay` | Delay before the state starts, in seconds. | `delay = 0.45` |
| `duration` | Length of the animation in seconds. | `duration = 0.1` |
| `name` | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. | `name = show` |

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
