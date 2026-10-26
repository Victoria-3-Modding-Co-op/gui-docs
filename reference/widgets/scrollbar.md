# scrollbar

A draggable bar with decrement/increment buttons.

## At a glance

- **Kind:** `scrollbar`
- **Category:** Interaction
- **Children:** engine-managed slots
- **Used in the shipped interface:** 17 times

## When to use it

A draggable bar with optional decrement/increment buttons.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `track` | The groove the slider runs in. |
| `slider` | The draggable handle. |
| `dec_button` | Decrement button. |
| `inc_button` | Increment button. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `direction` | token | Main axis of a layout container, a progress bar or a scrollbar. | `direction = horizontal` |
| `value` | number | Current value of a progress bar or scrollbar. | `value = "[MusicPlayer.GetVolume]"` |
| `min` | number | Lower bound of a progress bar or scrollbar. | `min = 0.0` |
| `max` | number | Upper bound of a progress bar or scrollbar. | `max = 1.0` |
| `step` | number | Increment applied by the scrollbar's step action. | `step = 0.1` |
| `onvaluechanged` | expression | Called when a scrollbar or slider value changes. | `onvaluechanged = "[MusicPlayer.SetVolume]"` |
| `wheelstep` | number | Increment applied by one mouse-wheel notch. | `wheelstep = 0.1` |
| `page` | number | Increment applied by a page action on a scrollbar. | `page = 10` |

## Notes

Normally created by a `scrollarea`; declared directly only when a custom scroll bar is needed.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
