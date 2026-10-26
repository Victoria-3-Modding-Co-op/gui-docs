# window

A draggable, resizable top-level panel.

## At a glance

- **Kind:** `window`
- **Category:** Layout
- **Children:** accepted, positioned by their own anchors
- **Used in the shipped interface:** 94 times

## When to use it

A top-level panel that the player can drag and resize.

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `movable` | bool | Allow the player to drag the window. | `movable = no` |
| `resizable` | bool | Allow the player to resize the window. | `resizable = no` |
| `gfxtype` | token | Name of the engine draw type used for the widget, for example `buttongfx`, `windowgfx` or `progressbargfx`. | `gfxtype = windowgfx` |
| `shaderfile` | texture | Path of the shader used by the draw type. | `shaderfile = "gfx/FX/pdxgui_default.shader"` |
| `spriteType` | token | How the texture is mapped onto the widget rectangle. | `spriteType = corneredstretched` |
| `spriteborder` | vector2 | Horizontal and vertical inset of the nine-slice border. | `spriteborder = { 19 19 }` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. |
| `datamodel` | expression | Feeds a collection into a data-driven container, which then creates one `item` child per entry. |
| `raw_text` | string | Text displayed without localisation lookup, usually to mix literals with data bindings. |
| `texture` | texture | Path of the image to draw, below the game's `gfx/` directory. Accepts a data-binding expression. |
| `spriteborder_top` | number | Top border inset. |
| `align` | flags | Horizontal and vertical alignment of the text inside its box. |
| `fontsize_min` | int | Smallest size the text may shrink to when the box is too small. |
| `elide` | token | Where to cut the string when it does not fit. |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Key | Meaning | Example |
|---|---|---|
| `name` | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. | `name = _show` |
| `on_start` | Expression run when the state starts. | `on_start = "[PdxGuiTriggerAllAnimations('menu_logo_v_start')]"` |
| `position` | Target position, `{ x y }`. | `position = { 0 0 }` |
| `position_y` | Target position on the y axis only. | `position_y = 10` |
| `start_sound` | Sound played when the state starts. |  |
| `trigger_on_create` | Play the state when the widget is created. | `trigger_on_create = yes` |

## Notes

The drag/resize behaviour is controlled by `movable`, `resizable` and `reorder_on_mouse`.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
