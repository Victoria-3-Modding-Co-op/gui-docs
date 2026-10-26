# treemapchart

A treemap chart container.

## At a glance

- **Kind:** `treemapchart`
- **Category:** Visual
- **Children:** engine-managed slots
- **Used in the shipped interface:** 2 times

## When to use it

A treemap chart.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `item` | Instantiated once per data model entry. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `datamodel` | expression | Feeds a collection into a data-driven container, which then creates one `item` child per entry. | `datamodel = "[GetLoyaltyTypes]"` |

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
