# treemapslice

One slice of a treemapchart.

## At a glance

- **Kind:** `treemapslice`
- **Category:** Visual
- **Children:** none
- **Used in the shipped interface:** 2 times

## When to use it

One cell of a `treemapchart`.

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. | `texture = "gfx/interface/treemapchart/treemapchart.dds"` |
| `value` | number | Current value of a progress bar or scrollbar. | `value = "[LoyaltyType.GetCountryGraphicalRatio(Country.Self)]"` |
| `gfxtype` | token | Name of the engine draw type used for the widget, for example `buttongfx`, `windowgfx` or `progressbargfx`. | `gfxtype = treemapslicegfx` |
| `shaderfile` | texture | Path of the shader used by the draw type. | `shaderfile = "gfx/FX/pdxgui_treemapchart.shader"` |
| `mask` | texture | Mask texture; where the mask is opaque the widget is drawn. | `mask = "gfx/interface/default_treemapchart_mask.dds"` |

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
