# line

A polyline or spline drawn between points.

## At a glance

- **Kind:** `line`
- **Category:** Visual
- **Children:** none
- **Used in the shipped interface:** 2 times

## When to use it

Draws a polyline, B-spline or Catmull-Rom curve through the points in `points`.

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `gfxtype` | token | Name of the engine draw type used for the widget, for example `buttongfx`, `windowgfx` or `progressbargfx`. | `gfxtype = linegfx` |
| `line_type` | token | Interpolation used to draw the line. | `line_type = BSpline` |
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. | `texture = "gfx/interface/tech_tree/tech_line_border_research_locked.dds"` |
| `mask` | texture | Mask texture; where the mask is opaque the widget is drawn. | `mask = "gfx/interface/tech_tree/tech_line_mask.dds"` |
| `width` | float | Stroke width for a line or plot line. | `width = 8` |
| `points` | block | List of points for a line, as repeated `{ x y }` entries. | `points = "[TechTreeLine.GetPointsInContainer]"` |

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
