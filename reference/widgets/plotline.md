# plotline

A line chart over a series of points.

## At a glance

- **Kind:** `plotline`
- **Category:** Visual
- **Children:** none
- **Used in the shipped interface:** 16 times

## When to use it

A line chart. `plotpoints` supplies the series.

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `width` | float | Stroke width for a line or plot line. | `width = 2.5` |
| `plotpoints` | expression | Series of points for a plot line. | `plotpoints = "[GetTrendPlotPointsNormalized(Building.GetEarningsPerEmployeeTrend, GetMinPadded(Building.GetEarningsPerEmployeeTrend), GetMaxPadded(Building.GetEarningsPerEmployeeTrend))]"` |

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
