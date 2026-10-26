# vbox

Stacks its children vertically.

## At a glance

- **Kind:** `vbox`
- **Category:** Layout
- **Children:** accepted, stacked by the container
- **Used in the shipped interface:** 806 times

## When to use it

Stacks children top to bottom (or bottom to top with `direction = bottom_to_top`).

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `item` | Instantiated once per data model entry. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `spacing` | number | Gap in pixels between the children of a layout container. | `spacing = 10` |
| `datamodel` | expression | Feeds a collection into a data-driven container, which then creates one `item` child per entry. | `datamodel = "[Group.AccessVisibleAchievements]"` |
| `set_parent_size_to_minimum` | bool | Size the parent from this widget's minimum size. | `set_parent_size_to_minimum = yes` |
| `restrictparent_min` | bool | Do not let the parent shrink below this widget's minimum. | `restrictparent_min = yes` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `raw_text` | string | Text displayed without localisation lookup, usually to mix literals with data bindings. |
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. |
| `ontextedited` | expression | Called while the contents of an edit box change. |
| `maxcharacters` | int | Maximum number of characters accepted in an edit box. |
| `onreturnpressed` | expression | Called when Enter is pressed in an edit box. |
| `plotpoints` | expression | Series of points for a plot line. |
| `align` | flags | Horizontal and vertical alignment of the text inside its box. |
| `multiline` | bool | Allow the text to wrap onto several lines. |
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Key | Meaning | Example |
|---|---|---|
| `alpha` | Target opacity, 0..1. | `alpha = 1` |
| `duration` | Length of the animation in seconds. | `duration = 0.2` |
| `name` | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. | `name = show` |
| `next` | State to play when this one finishes. | `next = a` |
| `on_finish` | Expression run when the state finishes. | `on_finish = "[FeedMessageItem.EndAnimation]"` |
| `on_start` | Expression run when the state starts. | `on_start = "[FeedMessageItem.StartAnimation]"` |
| `trigger_when` | Expression that starts the state automatically. | `trigger_when = "[FeedMessageItem.IsSetToDelete]"` |

## Notes

Children are sized by their own `size` and by the layout policies, not by the box.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
