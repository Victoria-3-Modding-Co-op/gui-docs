# margin_widget

Reserves a margin around a single child.

## At a glance

- **Kind:** `margin_widget`
- **Category:** Layout
- **Children:** one child
- **Used in the shipped interface:** 49 times

## When to use it

Wraps a single child and reserves `margin` around it.

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `onreturnpressed` | expression | Called when Enter is pressed in an edit box. |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Key | Meaning | Example |
|---|---|---|
| `alpha` | Target opacity, 0..1. | `alpha = 0.5` |
| `delay` | Delay before the state starts, in seconds. | `delay = 1` |
| `duration` | Length of the animation in seconds. | `duration = 0.2` |
| `name` | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. | `name = _show` |
| `next` | State to play when this one finishes. | `next = "auto_scrollbar"` |
| `on_finish` | Expression run when the state finishes. | `on_finish = "[CreditsWindow.OnTogglePause]"` |
| `on_start` | Expression run when the state starts. | `on_start = "[CreditsWindow.OnSlower]"` |
| `size` | Target size, `{ w h }`. | `size = { 530 50 }` |

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
