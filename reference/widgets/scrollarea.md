# scrollarea

A viewport that scrolls its scrollwidget, with automatic scrollbars.

## At a glance

- **Kind:** `scrollarea`
- **Category:** Layout
- **Children:** engine-managed slots
- **Used in the shipped interface:** 74 times

## When to use it

A viewport with automatic scrollbars. The content lives in `scrollwidget`.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `scrollwidget` | The content that is scrolled. |
| `viewportwidget` | The visible window onto the content. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `scrollbar_vertical` | block | Block-valued property. |  |
| `scrollbarpolicy_horizontal` | token | When the horizontal scrollbar of a scroll area is shown. | `scrollbarpolicy_horizontal = always_off` |
| `scrollbar_horizontal` | block | Block-valued property. |  |
| `scrollbaralign_vertical` | token | Alignment of the vertical scrollbar inside the area. | `scrollbaralign_vertical = right` |
| `scrollbaralign_horizontal` | token | Alignment of the horizontal scrollbar inside the area. | `scrollbaralign_horizontal = bottom` |
| `scrollbarpolicy_vertical` | token | When the vertical scrollbar of a scroll area is shown. | `scrollbarpolicy_vertical = as_needed` |
| `preferscrollwidgetsize` | bool | Prefer the scroll widget's own size over the viewport's. | `preferscrollwidgetsize = yes` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. |
| `autoresizescrollarea` | bool | Let the scroll area resize itself to its content. |

## Notes

The scrollbars themselves are created by the engine; `scrollbar_vertical` and `scrollbar_horizontal` style them.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
