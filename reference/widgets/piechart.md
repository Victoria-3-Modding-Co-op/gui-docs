# piechart

A pie chart container.

## At a glance

- **Kind:** `piechart`
- **Category:** Visual
- **Children:** engine-managed slots
- **Used in the shipped interface:** 4 times

## When to use it

A pie chart. Slice values are supplied through a data model or through `pieslice` children.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `item` | Instantiated once per data model entry. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. | `texture = "gfx/interface/progressbar/progress_round_default.dds"` |
| `datamodel` | expression | Feeds a collection into a data-driven container, which then creates one `item` child per entry. | `datamodel = "[FeedMessageItem.GetTimeoutTimer.GetSlicesInverted]"` |
| `framesize` | vector2 | Size of one frame in a sprite sheet. | `framesize = { 164 164 }` |
| `frame` | int | Index of the sprite-sheet frame to draw. | `frame = 2` |
| `startangle` | float | Start angle of a pie slice. | `startangle = 450` |
| `endangle` | float | End angle of a pie slice. | `endangle = 90` |
| `gfxtype` | token | Name of the engine draw type used for the widget, for example `buttongfx`, `windowgfx` or `progressbargfx`. | `gfxtype = piechartgfx` |
| `shaderfile` | texture | Path of the shader used by the draw type. | `shaderfile = "gfx/FX/pdxgui_piechart.shader"` |
| `effectname` | string | Name of a named effect inside `shaderfile`. | `effectname = "PieChart"` |
| `mask` | texture | Mask texture; where the mask is opaque the widget is drawn. | `mask = "gfx/interface/default_piechart_mask.dds"` |

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
