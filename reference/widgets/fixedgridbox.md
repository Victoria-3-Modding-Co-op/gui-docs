# fixedgridbox

A grid whose cell sizes come from the declared column and row sizes.

## At a glance

- **Kind:** `fixedgridbox`
- **Category:** Layout
- **Children:** accepted, placed into cells
- **Used in the shipped interface:** 77 times

## When to use it

A grid whose column and row tracks are declared up front with `addcolumn` and `addrow`.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `item` | Instantiated once per data model entry. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `addrow` | number | Append a row of the given height to a grid box. | `addrow = @spreadsheet_height` |
| `addcolumn` | number | Append a column of the given width to a grid box. | `addcolumn = @spreadsheet_width` |
| `datamodel` | expression | Feeds a collection into a data-driven container, which then creates one `item` child per entry. | `datamodel = "[BuildingBrowserPanel.GetSortedAndFilteredBuildings]"` |
| `flipdirection` | bool | Reverse the order in which children are laid out. | `flipdirection = yes` |
| `datamodel_wrap` | int | Number of columns the data model is wrapped into. | `datamodel_wrap = 2` |
| `datamodel_reuse_widgets` | bool | Reuse item widgets between data model refreshes instead of recreating them. | `datamodel_reuse_widgets = yes` |
| `maxhorizontalslots` | int | Number of columns in a grid box. | `maxhorizontalslots = 2` |
| `layoutanchor` | token | Which corner of a grid box new cells are filled from. | `layoutanchor = topleft` |
| `setitemsizefromcell` | bool | Size each child from the grid cell rather than from the child's own `size`. | `setitemsizefromcell = yes` |
| `maxverticalslots` | int | Number of rows in a grid box. | `maxverticalslots = 3` |

## Notes

Children are placed in declaration order, left to right and top to bottom.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
