# Widgets and layout

## The rectangle model

Every widget ends up with a rectangle on screen. Four things decide it:

1. **`size`** — how large it wants to be.
2. **`parentanchor`** — which point of the parent it hangs from.
3. **`widgetanchor`** — which point of itself is placed there.
4. **`position`** — an offset applied after the anchors line up.

If the widget is inside a layout container (`vbox`, `hbox`, `flowcontainer`,
`gridbox`), the container also positions it, and `position` becomes an offset
inside the cell the container gives it.

### Size

```text
size = { 280 132 }      # 280 px wide, 132 px tall
size = { 100% 40 }      # full parent width, 40 px tall
size = { -1 8 }         # natural width, 8 px tall
```

- A number is pixels, interpreted in the interface scale.
- `N%` is a percentage of the parent's size on that axis.
- `-1` means *natural*: use whatever the widget's content or texture wants.

`size`, `position` and the min/max/preferred sizes take fractional numbers as
well as whole ones — the shipped files contain values such as
`position = { 0.5 -0.2 }`. In practice whole numbers dominate, which is why
most examples look integer-only.

Natural size is what makes `icon`, `textbox` and `button` work without an
explicit size. A button with `text` and no `size` is as wide as its label.

### Anchors

`parentanchor` and `widgetanchor` take the same vocabulary:

| Token | Axis | Meaning |
|---|---|---|
| `left` / `right` | horizontal | Align to that edge |
| `hcenter` | horizontal | Centre horizontally |
| `top` / `bottom` | vertical | Align to that edge |
| `vcenter` | vertical | Centre vertically |
| `center` | both | `hcenter` + `vcenter` |

A common pattern is to centre a widget in its parent:

```text
parentanchor = center
widgetanchor = center
```

Or to pin something to the bottom-right corner, growing leftwards and upwards:

```text
parentanchor = bottom|right
widgetanchor = bottom|right
```

`position` then nudges from that alignment:

```text
parentanchor = bottom|hcenter
widgetanchor = bottom|hcenter
position = { 0 -12 }        # 12 px above the parent's bottom edge
```

Leaving an axis out of both anchors means "stay where the layout put me" on
that axis — which is why many widgets only specify `parentanchor = vcenter`.

## The widget tree

Children are declared inside their parent:

```text
container = {
    size = { 400 200 }

    icon = {
        parentanchor = left|vcenter
        position = { 10 0 }
        size = { 32 32 }
        texture = "gfx/interface/icons/example.dds"
    }

    textbox = {
        parentanchor = left|vcenter
        position = { 52 0 }
        text = "EXAMPLE"
    }
}
```

Three rules to remember:

- A child is **clipped** by its parent only if the parent sets
  `scissor = yes`. By default children may draw outside.
- A child **inherits** nothing about position; all coordinates are relative to
  the parent's rectangle.
- **Draw order** among siblings is declaration order, later on top. Windows
  additionally have `layer`.

## Layout containers

### `vbox` and `hbox`

Stack children along one axis.

```text
vbox = {
    spacing = 8
    margin = { 16 16 }

    textbox = { text = "ONE" }
    textbox = { text = "TWO" }
}
```

`direction` flips the axis (`direction = vertical` on an `hbox`). `spacing` is
the gap between adjacent children. `margin` insets all four sides.

A child that should absorb the leftover space uses a layout policy:

```text
vbox = {
    textbox = { text = "HEADER" }

    scrollarea = {
        layoutpolicy_vertical = expanding
        # ...
    }

    hbox = {
        layoutpolicy_vertical = preferred
        # ...
    }
}
```

### `flowcontainer`

Places children until the container runs out of room, then wraps.

```text
flowcontainer = {
    spacing = 6
    wrap_count = 4          # force four per row
    # ...
}
```

Without `wrap_count` the container decides how many fit. `flipdirection`
reverses the fill order.

### Grids

`fixedgridbox` takes explicit tracks:

```text
fixedgridbox = {
    addcolumn = 200
    addrow = 40
    addrow = 40
    # children fill cells left to right, top to bottom
}
```

`dynamicgridbox` takes its cells from a data model instead, and instantiates its
`item` block per entry:

```text
dynamicgridbox = {
    datamodel = "[GetPlayer.GetStates]"
    datamodel_wrap = 3

    item = {
        textbox = { text = "[State.GetName]" }
    }
}
```

`layoutanchor` chooses which corner the fill starts from.

### `scrollarea`

A viewport around a `scrollwidget`:

```text
scrollarea = {
    size = { 400 300 }
    scrollbarpolicy_vertical = as_needed
    scrollbarpolicy_horizontal = always_off

    scrollwidget = {
        vbox = {
            # tall content
        }
    }
}
```

The engine creates the scrollbars. Style them with `scrollbar_vertical` and
`scrollbar_horizontal` blocks, and control when they appear with
`scrollbarpolicy_*`.

### `overlappingitembox` and `margin_widget`

`overlappingitembox` lays children out in sequence but lets them overlap, which
is how stacked bars and layered markers are built. `margin_widget` reserves a
margin around a single child.

## Sizing rules in detail

| Property | Effect |
|---|---|
| `size` | Requested size |
| `minimumsize` | Floor applied by layout |
| `maximumsize` | Ceiling applied by layout |
| `preferredsize` | Size used when distributing space |
| `min_width` / `max_width` / `min_height` / `max_height` | Per-axis shorthands that take precedence in flow layouts |
| `autoresize` | Derive the size from content instead |
| `resizeparent` | Push the size onto the parent |
| `layoutpolicy_horizontal` / `_vertical` | Whether the widget may grow or shrink beyond its request |
| `layoutstretchfactor_horizontal` / `_vertical` | Relative share of leftover space |

The layout policy tokens seen in the shipped files:

| Token | Behaviour |
|---|---|
| `preferred` | Keep the requested size; do not absorb slack |
| `fixed` | Do not change size at all |
| `growing` | May take more than the requested size |
| `shrinking` | May take less than the requested size |
| `expanding` | Grows to fill and forces the parent to grow with it |

Two widgets with `layoutpolicy_horizontal = expanding` split the leftover width
in proportion to their `layoutstretchfactor_horizontal` values.

## Visibility and hit testing

- `visible = no` stops drawing and input, and (in layout containers) removes the
  widget from the flow unless the container sets `ignoreinvisible = no`.
- `enabled = no` keeps the widget visible but ignores input and draws it in its
  disabled state.
- `alwaystransparent = yes` lets clicks pass straight through. Use it on
  decorative overlays so they do not swallow the click meant for the widget
  underneath.
- `allow_outside = yes` on a parent permits children to be drawn outside its
  rectangle; combined with `scissor = yes` you get clipping.

## Layers

`layer` names a draw band. Windows use it to sit above or below other windows:

```text
layer = layer_minimap
layer = windows_layer
```

Sibling order within a layer still follows declaration order.

## Next

- [Appearance](04-appearance.md) — making the rectangle look like something.
- [Reference: common properties](reference/common-properties.md)
