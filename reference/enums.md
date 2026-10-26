# Enumerated values

Several properties take one of a fixed set of tokens. The tables below list every accepted token and what it does.

## Anchor flags

Used by: parentanchor, widgetanchor, tooltip_*anchor

Two independent axes, each optional. Combine values with `|`. `center` is accepted as shorthand for `hcenter|vcenter`.

| Token | Meaning |
|---|---|
| `left` | Anchor to the parent's left edge. |
| `right` | Anchor to the parent's right edge. |
| `hcenter` | Centre horizontally. |
| `top` | Anchor to the parent's top edge. |
| `bottom` | Anchor to the parent's bottom edge. |
| `vcenter` | Centre vertically. |
| `center` | Shorthand for `hcenter\|vcenter`. |

## Layout policy

Used by: layoutpolicy_horizontal, layoutpolicy_vertical

How a widget behaves when a layout container distributes space. `preferred` is the default.

| Token | Meaning |
|---|---|
| `preferred` | Keep the requested size; do not absorb slack. |
| `fixed` | Never change size, even in a tight container. |
| `growing` | May take more than the requested size. |
| `shrinking` | May take less than the requested size. |
| `expanding` | Grow and shrink to fill, and force the parent to grow with it. |

## Text alignment

Used by: align

Alignment of text inside its box. Combine values with `|`. `center` is accepted as shorthand for `hcenter|vcenter`.

| Token | Meaning |
|---|---|
| `left` | Align to the left edge. |
| `right` | Align to the right edge. |
| `hcenter` | Centre horizontally. |
| `top` | Align to the top edge. |
| `bottom` | Align to the bottom edge. |
| `vcenter` | Centre vertically. |
| `center` | Shorthand for `hcenter\|vcenter`. |
| `baseline` | Align to the text baseline (the default). |
| `nobaseline` | Ignore the baseline offset. |

## Elide

Used by: elide

Where a string is truncated when it does not fit.

| Token | Meaning |
|---|---|
| `none` | Do not truncate. |
| `right` | Cut the right end. |
| `left` | Cut the left end. |
| `middle` | Cut the middle. |

## Direction

Used by: direction

Main axis of a layout container or bar.

| Token | Meaning |
|---|---|
| `horizontal` | Left to right (or right to left). |
| `vertical` | Top to bottom. |

## Reorder on mouse

Used by: reorder_on_mouse

When a window is raised above its siblings.

| Token | Meaning |
|---|---|
| `never` | Never raise automatically. |
| `press_top` | Raise on mouse press. |
| `press_bottom` | Lower on mouse press. |
| `release_top` | Raise on mouse release. |
| `release_bottom` | Lower on mouse release. |

## Scroll bar policy

Used by: scrollbarpolicy_horizontal, scrollbarpolicy_vertical

When a scroll area shows its scrollbar.

| Token | Meaning |
|---|---|
| `as_needed` | Show only when the content overflows. |
| `always_off` | Never show. |
| `always_on` | Always show. |

## Scroll bar alignment

Used by: scrollbaralign_horizontal, scrollbaralign_vertical

Where the scrollbar sits inside the scroll area.

| Token | Meaning |
|---|---|
| `no_align` | Default position. |
| `top` | Top edge. |
| `bottom` | Bottom edge. |
| `left` | Left edge. |
| `right` | Right edge. |

## Auto-resize axis

Used by: autoresize_axis

Which axes a widget may grow on when auto-resizing.

| Token | Meaning |
|---|---|
| `all` | Both axes. |
| `horizontal` | Width only. |
| `vertical` | Height only. |

## Fit type

Used by: fittype

How a texture is fitted into a rectangle when the aspect ratios differ.

| Token | Meaning |
|---|---|
| `fill` | Stretch to fill, ignoring aspect ratio. |
| `center` | Centre at natural size. |
| `centercrop` | Scale to cover, cropping the overflow. |
| `start` | Align to the start of the long axis. |
| `end` | Align to the end of the long axis. |

## Font weight

Used by: fontweight

| Token | Meaning |
|---|---|
| `regular` | Normal weight. |
| `light` | Light. |
| `semibold` | Semi-bold. |
| `bold` | Bold. |
| `extrabold` | Extra bold. |

## Modality

Used by: modality

What a modal window blocks.

| Token | Meaning |
|---|---|
| `all` | Blocks all input. |
| `gui` | Blocks interface input only. |

## Focus policy

Used by: focuspolicy

How a widget can acquire keyboard focus.

| Token | Meaning |
|---|---|
| `none` | Never focusable. |
| `click` | Focus on click. |
| `tab` | Reachable with Tab. |
| `all` | Both `click` and `tab`. |

## Mirror flags

Used by: mirror

Mirror the texture on one or both axes.

| Token | Meaning |
|---|---|
| `horizontal` | Mirror left to right. |
| `vertical` | Mirror top to bottom. |

## Anchor behaviour

Used by: tooltip_horizontalbehavior, tooltip_verticalbehavior

What a floating element does when it would leave the screen.

| Token | Meaning |
|---|---|
| `none` | Do nothing. |
| `flip` | Flip to the opposite anchor. |
| `mirror` | Mirror the anchor without moving content. |
| `slide` | Slide back onto the screen. |

## Layout anchor

Used by: layoutanchor

Corner that a grid box fills from.

| Token | Meaning |
|---|---|
| `top_left` | Fill from the top left. |
| `top_right` | Fill from the top right. |
| `bottom_left` | Fill from the bottom left. |
| `bottom_right` | Fill from the bottom right. |

## Track navigation

Used by: tracknavigation

What clicking the scrollbar track does.

| Token | Meaning |
|---|---|
| `paged` | Move by one page. |
| `direct` | Jump to the clicked position. |

## Button trigger

Used by: button_trigger

Which mouse gesture activates a button.

| Token | Meaning |
|---|---|
| `none` | No automatic trigger. |
| `press` | Activate on press. |
| `release` | Activate on release. |
| `double_click` | Activate on double click. |

## Tooltip type

Used by: tooltip_type

How a tooltip locks in place.

| Token | Meaning |
|---|---|
| `no_lock` | Follows the pointer, never locks. |
| `mouse_tendency` | Follows the pointer with a bias. |
| `lock_on_action` | Locks when the player acts. |
| `lock_on_timer` | Locks after a delay. |
| `lock_on_timer_or_action` | Locks on either. |
| `lock_on_action_mouse_anchor` | Locks on action at the mouse. |
| `lock_on_timer_mouse_anchor` | Locks on timer at the mouse. |

## Line type

Used by: line_type

Interpolation used to draw a line.

| Token | Meaning |
|---|---|
| `line` | Straight segments. |
| `bspline` | B-spline. |
| `catmullrom` | Catmull-Rom spline. |
| `nodeline` | Node-graph line. |

## Blend modes

`blend_mode` accepts the compositing modes below on `modify_texture` and on textures generally.

| Token | Meaning |
|---|---|
| `normal` | Opaque source-over compositing. |
| `add` | Additive, brightening. |
| `subtract` | Subtractive, darkening. |
| `multiply` | Multiplicative, darkening. |
| `overlay` | Contrast-preserving multiply/screen. |
| `screen` | Inverse multiply, brightening. |
| `soft_light` | Gentle lighting blend. |
| `hard_light` | Strong lighting blend. |
| `color_dodge` | Brightens the destination. |
| `color_burn` | Darkens the destination. |
