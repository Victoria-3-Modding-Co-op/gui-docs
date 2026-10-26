# Appearance

This chapter is about turning a rectangle into something that looks like part of
the interface: images, backgrounds, frames, colour, and the draw types that
connect a widget to the engine's renderer.

## The drawing stack

A widget can draw, from back to front:

1. its **background** — a texture placed behind the widget;
2. its **main texture** — the widget's own image, if the kind draws one
   (`icon`, `button`, `progressbar`, ...);
3. zero or more **modify textures** — additional layers composited over it;
4. its **children**, in declaration order.

```text
icon = {
    texture = "gfx/interface/icons/example.dds"

    background = {
        using = tooltip_background
        margin = { 10 10 }
    }

    modify_texture = {
        name = "highlight"
        texture = "gfx/interface/buttons/white.dds"
        blend_mode = add
        alpha = 0.4
    }
}
```

## Textures

`texture` takes a path below `gfx/`. It also accepts a data-binding expression,
which is how icons are chosen at runtime:

```text
texture = "[Goods.GetTexture]"
```

`texture_density` tells the engine how dense the image is relative to the
interface scale. A texture authored at twice the target resolution sets
`texture_density = 2` so it is drawn at half its pixel size and stays crisp when
the interface is scaled up.

## Sprite types

`spriteType` decides how an image is mapped onto a rectangle whose aspect ratio
differs from the image's:

| Value | Effect |
|---|---|
| `Stretched` | Stretch to fill; corners distort |
| `Tiled` | Repeat the image |
| `Centered` | Draw at natural size, centred |
| `Corneredstretched` | Nine-slice: keep corners, stretch edges and centre |
| `Corneredtiled` | Nine-slice: keep corners, tile edges and centre |

The token is case-insensitive; the shipped files use `Corneredstretched`,
`CorneredStretched` and `corneredstretched` interchangeably.

Nine-slice modes need `spriteborder` to say how large the corners are:

```text
spriteType = Corneredtiled
spriteborder = { 3 5 }      # 3 px horizontally, 5 px vertically
```

Per-edge values are available when the border is not symmetric:
`spriteborder_left`, `spriteborder_right`, `spriteborder_top`,
`spriteborder_bottom`.

## Sprite sheets and frames

An image can hold several frames laid out in a row or grid. `framesize` gives
the size of one frame, and `frame` selects which to draw:

```text
texture = "gfx/interface/buttons/button_states.dds"
framesize = { 96 96 }
frame = 2
```

Buttons use named frame slots instead of a single `frame`:

| Property | State |
|---|---|
| `upframe` | Idle |
| `overframe` | Pointer over |
| `downframe` | Pressed |
| `disableframe` | Disabled |
| `activeframe` | Active / toggled |
| `uphoverframe` | Idle and hovered |
| `uppressedframe` | Idle and pressed |
| `downhoverframe` | Pressed and hovered |
| `downpressedframe` | Pressed |

Keeping all states in one sheet is why a button is one image and nine numbers
rather than nine images.

## Colour

Colour properties take four numbers in 0..1: red, green, blue, alpha.

```text
tintcolor = { 0 0 0 0.6 }       # darken by 60 %
color     = { 1 1 1 1 }         # no tint
fontcolor = { 0.9 0.8 0.6 1 }   # warm text
```

| Property | Applies to |
|---|---|
| `color` | The widget's own draw |
| `tintcolor` | The drawn texture |
| `fontcolor` | Text |
| `fonttintcolor` | Text glyphs, multiplied |
| `cursorcolor` | Edit box caret |

All of them accept expressions, which is how dynamic colour is done:

```text
color = "[Country.GetMapColor]"
fonttintcolor = "[TooltipInfo.GetTintColor]"
```

## Blending

`blend_mode` on a texture decides how it composites with what is already on
screen:

| Value | Effect |
|---|---|
| `normal` | Straight source-over |
| `add` | Additive; brightens |
| `subtract` | Subtractive; darkens |
| `multiply` | Multiplies; darkens |
| `overlay` | Contrast-preserving blend |
| `screen` | Brightens while preserving highlights |

Additive white textures are the standard trick for highlights and glows: draw
the same shape again with `blend_mode = add` and a low `alpha`, and animate the
alpha.

## Modify textures

A `modify_texture` is a second (or third, or fourth) image composited over the
widget. Each one has its own texture, transform and blending, and is addressed
by `name` so animations can target it.

```text
modify_texture = {
    name = "mouse_enter"
    texture = "gfx/interface/buttons/highlight.dds"
    spriteType = Corneredstretched
    spriteborder = { 0 0 }
    blend_mode = add
    alpha = 0
    rotate_uv = 0
}
```

Because the layer has a `name`, an animation state can fade it in:

```text
state = {
    name = mouse_enter
    duration = 0.1

    modify_texture = {
        name = mouse_enter
        alpha = 1
    }
}
```

That pattern — a transparent overlay plus a named state — is how essentially all
hover and press effects in the game are built.

## Backgrounds

`background` is a child widget of kind `background`: a texture drawn behind its
parent, automatically sized to it.

```text
background = {
    using = default_background
    margin = { 15 15 }
}
```

`margin` insets the background from the parent's edges, which keeps a drop shadow
or border from being clipped.

## Draw types: `gfxtype`, `shaderfile`, `effectname`

Ordinary textures cover most cases. When a widget needs a specialised draw path
— a window frame, a framed push button, a progress bar with a fill texture — the
type sets three properties:

```text
gfxtype    = framedbuttongfx
shaderfile = "gfx/FX/pdxgui_pushbutton.shader"
effectname = "NoHighlight"
```

- `gfxtype` selects the engine draw type (`buttongfx`, `checkbuttongfx`,
  `editboxgfx`, `progressbargfx`, `framedprogressbargfx`, `windowgfx`,
  `icongfx`, `piechartgfx`, ...).
- `shaderfile` points at the shader that implementation uses.
- `effectname` picks a named technique inside that shader.

You rarely need to set these: game types in `gui/shared/` already do. Set them
when you build a new visual from scratch.

## Glow, masks and fitting

| Property | Effect |
|---|---|
| `mask` | Texture whose alpha limits where the widget draws |
| `intersectionmask` | Use the texture as a hit-test mask, so clicks only land on opaque pixels |
| `fittype` | `fill`, `center`, `centercrop`, `start`, `end` — how an image is fitted into a rectangle |
| `mipmaplodbias` | Bias when sampling the mip chain |
| `enable_frame_blend` | Blend between sprite-sheet frames instead of switching |

## A complete visual definition

Putting it together, this is a self-contained button visual:

```text
type fancy_button = button {
    size = { 220 48 }
    gfxtype = framedbuttongfx
    shaderfile = "gfx/FX/pdxgui_pushbutton.shader"

    texture = "gfx/interface/buttons/fancy.dds"
    framesize = { 220 48 }
    upframe = 0
    overframe = 1
    downframe = 2
    disableframe = 3

    modify_texture = {
        name = "glow"
        texture = "gfx/interface/buttons/fancy_glow.dds"
        blend_mode = add
        alpha = 0
    }

    state = {
        name = mouse_enter
        duration = 0.08
        modify_texture = { name = glow alpha = 1 }
    }

    state = {
        name = mouse_leave
        duration = 0.12
        modify_texture = { name = glow alpha = 0 }
    }
}
```

## Next

- [Text](05-text.md)
- [Reference: common properties](reference/common-properties.md)
- [Reference: enumerations](reference/enums.md)
