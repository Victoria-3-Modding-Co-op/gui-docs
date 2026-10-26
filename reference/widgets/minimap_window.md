# minimap_window

The window that hosts the minimap.

## At a glance

- **Kind:** `minimap_window`
- **Category:** Visual
- **Children:** accepted, positioned by their own anchors
- **Used in the shipped interface:** 1 times

## When to use it

The window that hosts the minimap.

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `movable` | bool | Allow the player to drag the window. | `movable = no` |
| `resizable` | bool | Allow the player to resize the window. | `resizable = no` |
| `reorder_on_mouse` | token | When a window should be brought to the front. | `reorder_on_mouse = never` |
| `gfxtype` | token | Name of the engine draw type used for the widget, for example `buttongfx`, `windowgfx` or `progressbargfx`. | `gfxtype = windowgfx` |
| `shaderfile` | texture | Path of the shader used by the draw type. | `shaderfile = "gfx/FX/pdxgui_default.shader"` |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Key | Meaning | Example |
|---|---|---|
| `duration` | Length of the animation in seconds. | `duration = 0.05` |
| `name` | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. | `name = open` |
| `position` | Target position, `{ x y }`. | `position = { 400 0 }` |
| `trigger_on_create` | Play the state when the widget is created. | `trigger_on_create = yes` |

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
