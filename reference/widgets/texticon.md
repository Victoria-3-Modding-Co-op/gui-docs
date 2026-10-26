# texticon

A textbox whose string may embed icon tokens.

## At a glance

- **Kind:** `texticon`
- **Category:** Text
- **Children:** text content with inline icons
- **Used in the shipped interface:** 446 times

## When to use it

A text widget that can embed named icons inside the string.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `iconsize` | Texture, size and offset of an inline text icon. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `icon` | token | Name of the icon embedded in a `texticon` string. | `icon = ammunition` |
| `iconsize` | block | Texture, size and offset used for the icon declared next to it in a `texticon`. |  |

## `iconsize` sub-object

Presentation of the icons embedded in a `texticon` string.

| Key | Meaning | Example |
|---|---|---|
| `fontsize` | Font size the icon is sized against. | `fontsize = 18` |
| `offset` | Offset from the text baseline, `{ x y }`. | `offset = { 0 7 }` |
| `size` | Drawn size, `{ w h }`. | `size = { 25 25 }` |
| `texture` | Image path of the icon. | `texture = "gfx/interface/icons/goods_icons/ammunition.dds"` |

## Notes

Each `icon` entry declares one token; `iconsize` gives the texture, size and vertical offset used when that token is drawn.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
