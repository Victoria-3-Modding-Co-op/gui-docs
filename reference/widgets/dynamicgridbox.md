# dynamicgridbox

A grid driven by a data model, building one child per entry.

## At a glance

- **Kind:** `dynamicgridbox`
- **Category:** Layout
- **Children:** accepted, placed into cells
- **Used in the shipped interface:** 165 times

## When to use it

A grid whose cells come from a `datamodel`; the widget block inside `item` is instantiated once per entry.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `item` | Instantiated once per data model entry. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `datamodel` | expression | Feeds a collection into a data-driven container, which then creates one `item` child per entry. | `datamodel = "[AddWarGoalPanel.AccessShownWarGoals]"` |
| `flipdirection` | bool | Reverse the order in which children are laid out. | `flipdirection = yes` |
| `datamodel_wrap` | int | Number of columns the data model is wrapped into. | `datamodel_wrap = 10` |
| `layoutanchor` | token | Which corner of a grid box new cells are filled from. | `layoutanchor = topright` |
| `datamodel_reuse_widgets` | bool | Reuse item widgets between data model refreshes instead of recreating them. | `datamodel_reuse_widgets = yes` |
| `maxhorizontalslots` | int | Number of columns in a grid box. | `maxhorizontalslots = 3` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. |

## Notes

`datamodel_wrap` sets the number of columns when the grid should be filled column by column.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
