# overlappingitembox

Lays children out in sequence, letting them overlap.

## At a glance

- **Kind:** `overlappingitembox`
- **Category:** Layout
- **Children:** accepted, stacked by the container
- **Used in the shipped interface:** 43 times

## When to use it

Places children in sequence but lets them overlap, which is how stacked bars and layered markers are built.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `item` | Instantiated once per data model entry. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `datamodel` | expression | Feeds a collection into a data-driven container, which then creates one `item` child per entry. | `datamodel = "[MilitaryFormation.GetMobilizationOptions]"` |
| `spacing` | number | Gap in pixels between the children of a layout container. | `spacing = 5` |
| `righttoleft` | bool | Lay the container out right to left. | `righttoleft = yes` |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Key | Meaning | Example |
|---|---|---|
| `name` | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. | `name = _show` |
| `start_sound` | Sound played when the state starts. |  |

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
