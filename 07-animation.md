# Animation

Animation is built from **states**. A state describes a target appearance and how
long it takes to get there; the engine interpolates from the widget's current
appearance to the target.

```text
state = {
    name = open
    duration = 0.15
    position = { 0 0 }
    alpha = 1
}
```

The state is played by name:

```text
onclick = "[PdxGuiWidget.TriggerAnimation('open')]"
```

## The state block

| Key | Meaning |
|---|---|
| `name` | Identifier used by `TriggerAnimation`, `next`, and scripts |
| `duration` | Length in seconds |
| `delay` | Wait before starting |
| `bezier` | Easing curve, `{ x1 y1 x2 y2 }` |
| `next` | State to play when this one finishes |
| `trigger_when` | Expression that starts the state automatically |
| `trigger_on_create` | Play immediately when the widget is created |
| `on_start` | Expression run when the state starts |
| `on_finish` | Expression run when it finishes |
| `start_sound` / `end_sound` | Sounds at the state boundaries |

State names may be numbers as well as identifiers, which is convenient for
sequenced animations:

```text
state = {
    name = 2
    next = 3
    scale = 1.4
    alpha = 1
    duration = 0.2
}

state = {
    name = 3
    scale = 1
    duration = 0.1
}
```

## What can be animated

| Key | Type |
|---|---|
| `position`, `position_x`, `position_y` | Vector / number |
| `size` | Vector |
| `scale` | Number |
| `alpha` | Number |
| `frame` | Integer |
| `bezier` | Vector of four numbers |
| `animation` | Named curve description |
| `modify_texture` | Per-layer overrides, matched by `name` |

Anything not listed is set instantly and does not interpolate.

## Animating a modify texture

This is the workhorse pattern for hover and press effects. Declare a transparent
layer on the widget, then change its alpha in a state:

```text
icon = {
    texture = "gfx/interface/icons/action.dds"

    modify_texture = {
        name = "glow"
        texture = "gfx/interface/icons/action_glow.dds"
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

    onmouseenter = "[PdxGuiWidget.TriggerAnimation('mouse_enter')]"
    onmouseleave = "[PdxGuiWidget.TriggerAnimation('mouse_leave')]"
}
```

Because the layer has a `name`, the state can address it. Several layers can be
animated independently in the same state.

## Reusing animation fragments

The game ships templates that bundle the common cases, so a state can be a few
lines:

```text
state = {
    name = show
    alpha = 1
    duration = 0.2
    using = Animation_Curve_Default
}

state = {
    name = hide
    alpha = 0
    duration = 0.15
    using = Animation_Curve_Default
}
```

Common fragments live in `gui/shared/animations.gui` and
`gui/shared/animations_special.gui`:

| Template | Purpose |
|---|---|
| `Animation_Curve_Default` | Standard easing |
| `default_fade_in` / `default_fade_out` | Alpha transitions |
| `default_show_properties` / `default_hide_properties` | The standard show/hide pair |
| `default_mouse_states_animation` | Hover in / out |
| `default_button_animation` | Button press feedback |
| `shimmer` / `hud_shiny_effect` | Repeating highlight |

Always prefer `using` over copying the numbers: it keeps timing consistent across
the interface and makes a global retuning possible.

## Playing states from script

States are addressed through the widget API:

| Expression | Effect |
|---|---|
| `PdxGuiWidget.TriggerAnimation('name')` | Play a state |
| `PdxGuiWidget.InterruptAnimation('name')` | Stop a state |
| `PdxGuiWidget.InterruptThenTriggerAnimation('a','b')` | Stop one and start another |
| `PdxGuiInterruptThenTriggerAllAnimations('a','b')` | Same, for a whole hierarchy |
| `PdxGuiTriggerAllAnimations('name')` | Play on every widget with that state |

Typical uses:

```text
# the widget you are on
onclick = "[PdxGuiWidget.TriggerAnimation('press')]"

# a child by name
on_start = "[PdxGuiWidget.FindChild('arrow').TriggerAnimation('rotate')]"

# a whole window
onclick = "[PdxGuiInterruptThenTriggerAllAnimations('hide','show')]"
```

## Animation asset types

`gui/shared/animations.gui` also declares whole **animation types** — a widget
tree with its states already wired up — which can be instantiated like any other
type:

```text
type checkmark_animation = widget {
    size = { 50 50 }

    icon = {
        parentanchor = center
        size = { 100% 100% }
        texture = "gfx/interface/icons/generic_icons/checkmark.dds"

        state = { name = _show next = 2 scale = 0.1 alpha = 0 }
        state = { name = 2 next = 3 scale = 1.4 alpha = 1 duration = 0.2 }
        state = { name = 3 scale = 1 duration = 0.1 }
        state = { name = _hide scale = 1 alpha = 0 duration = 0 }
    }
}
```

```text
checkmark_animation = { }
```

Use this when the same flourish is needed in several panels.

## Triggering animation from state

`trigger_when` starts a state when an expression becomes true, which is how
elements animate in response to game state rather than input:

```text
state = {
    name = expand
    trigger_when = "[Article.IsExpanded]"
    duration = 0.15
    size = { 300 200 }
}
```

`trigger_on_create` is the simpler variant for "always play this on first draw",
typically paired with a zero-duration state that sets the starting appearance:

```text
state = {
    name = initial
    alpha = 0
    duration = 0
    trigger_on_create = yes
    next = fade_in
}
```

## Timing conventions in the game

- Hover in/out: 0.08–0.15 s.
- Panel show/hide: 0.15–0.25 s.
- Deliberate flourishes (checkmarks, notifications): 0.2–0.5 s.
- Anything above ~0.6 s starts to feel like a loading screen.

Match the neighbouring widgets rather than inventing timings; the interface reads
as coherent mostly because the durations agree.

## Next

- [Data binding](08-data-binding.md)
- [Cookbook](10-cookbook.md)
