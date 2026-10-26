# colorpicker

An HSV/RGB colour selection popup.

## At a glance

- **Kind:** `colorpicker`
- **Category:** Interaction
- **Children:** engine-managed slots
- **Used in the shipped interface:** 0 times (available to mods, not used by the base game)

## When to use it

An HSV/RGB colour selector.

## Notes

The engine builds the sliders, swatches and hex field itself and looks for a fixed set of child names (`colorpicker_close`, `colorpicker_preview`, `color_slider_red`, ...). A `.gui` file only supplies those named widgets, which is why the game's own `color_picker.gui` declares them in a hidden `widget`. You bind the colour with `oncolorchanged` and read the result from the caller.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
