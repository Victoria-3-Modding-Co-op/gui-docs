# dropDown

A collapsing list of selectable items.

## At a glance

- **Kind:** `dropDown`
- **Category:** Interaction
- **Children:** engine-managed slots
- **Used in the shipped interface:** 12 times

## When to use it

A collapsing list. The list itself is built from `datamodel` and the `item` block.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `item` | Instantiated once per data model entry. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `onselectionchanged` | expression | Called when the selection in a dropdown or list changes. | `onselectionchanged = "[SetDefaultMapMode]"` |
| `datamodel` | expression | Feeds a collection into a data-driven container, which then creates one `item` child per entry. | `datamodel = "[GetMapModeIndices]"` |
| `selectedindex` | expression | Bound index of the selected entry. | `selectedindex = "[GetSelectedMapMode]"` |
| `list` | block | List configuration block. |  |
| `open_sound` | string | Sound played when the widget opens. | `open_sound = "event:/SFX/UI/Global/decrement"` |
| `close_sound` | string | Sound played when the widget closes. | `close_sound = "event:/SFX/UI/Global/increment"` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Key | Meaning | Example |
|---|---|---|
| `alpha` | Target opacity, 0..1. | `alpha = 1` |
| `duration` | Length of the animation in seconds. | `duration = 0.2` |
| `name` | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. | `name = map_modes_show` |
| `start_sound` | Sound played when the state starts. |  |

## Notes

`selectedindex` binds the selection; `onselectionchanged` reacts to it.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
