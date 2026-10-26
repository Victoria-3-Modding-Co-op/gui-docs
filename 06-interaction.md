# Interaction

Interaction covers four things: receiving input, looking interactive while doing
so, telling the player what will happen, and remaining reachable without a mouse.

## Click callbacks

A callback is a property whose value is a data-binding expression. It runs when
the widget receives the event.

```text
button = {
    text = "CONFIRM"
    onclick = "[Confirm]"
}
```

| Callback | Fires when |
|---|---|
| `onclick` | Left click completes |
| `onrightclick` | Right click completes |
| `ondoubleclick` | Double click |
| `onpressed` | A mouse button goes down over the widget |
| `onreleased` | A mouse button comes up |
| `onmouseenter` | The pointer enters the widget |
| `onmouseleave` | The pointer leaves the widget |
| `onmousehierarchyenter` | The pointer enters the widget **or any child** |
| `onmousehierarchyleave` | The pointer leaves the widget **and all children** |

The hierarchy variants are what you want for hover effects on a composite
widget, because moving from the widget onto its own icon does not count as
leaving.

The callback expression is evaluated with the widget as `PdxGuiWidget` and the
widget's data context as the root scope. See
[Data binding](08-data-binding.md).

### Modifier keys

A button can react differently depending on which modifier is held. Use
`click_modifiers`, whose keys name the modifier:

```text
button = {
    text = "BUILD"

    click_modifiers = {
        ondefault = "[Build(1)]"
        onshift   = "[Build(10)]"
        onctrl    = "[Build(100)]"
        onalt     = "[Build(1000)]"
    }
}
```

The same pattern exists for right clicks (`rightclick_modifiers`) and for
actions bound to input rather than clicks (`*_input_action` variants).

## Enabled, visible, and the difference

| Property | Input | Drawing |
|---|---|---|
| `visible = no` | Ignored | Not drawn |
| `enabled = no` | Ignored | Drawn disabled |
| `alwaystransparent = yes` | Passed to whatever is underneath | Drawn normally |

Use `enabled` when the player should see the control but understand it is not
available:

```text
button = {
    text = "DECLARE_WAR"
    enabled = "[CanDeclareWar(GetPlayer, Character.Self)]"
    onclick = "[DeclareWar(Character.Self)]"
}
```

A disabled button is still drawn, usually with `disableframe` and a tooltip
explaining why. Combine it with a `tooltip` that says what is missing — the
shipped interface does this consistently.

## Tooltips

The simple form is a key:

```text
tooltip = "DECLARE_WAR_TOOLTIP"
```

For a tooltip that depends on state, use an expression that returns a key:

```text
tooltip = "[Character.GetDiplomaticTooltip]"
```

Properties that shape the tooltip:

| Property | Effect |
|---|---|
| `tooltip_widgetanchor` / `tooltip_parentanchor` | Where the tooltip attaches |
| `tooltip_offset` | Nudge from that anchor |
| `tooltip_type` | When the tooltip locks in place |
| `tooltip_horizontalbehavior` / `tooltip_verticalbehavior` | What to do when it would leave the screen: `flip`, `mirror`, `slide` |
| `tooltip_enabled` | Turn it off without removing it |

For rich tooltips — tables, icons, multi-line layouts — supply a widget instead:

```text
tooltipwidget = {
    using = dockable_tooltip
    # any widget tree
}
```

The `tooltipwidget` slot is supported by every widget, so it is the escape hatch
when a string is not enough.

`raw_tooltip` shows its value verbatim, like `raw_text`:

```text
raw_tooltip = "#todo TODO: explain why this is disabled#!"
```

## Focus and keyboard

Keyboard navigation is opt-in per widget.

| Property | Effect |
|---|---|
| `focuspolicy` | `click`, `tab`, `all`, or `none` |
| `focus_on_visible` | Take focus when shown |
| `taborder` | Position in the Tab cycle |
| `tabfocusroot` | Start a new Tab cycle here |
| `shortcut` | Activate the widget from a named shortcut |
| `input_action` | Activate the widget from a named input action |

```text
editbox = {
    focuspolicy = tab
    focus_on_visible = yes
    text = "[Window.GetName]"
}
```

`shortcut` names an entry in a `.shortcuts` file next to the `.gui` files:

```text
window = {
    shortcut = "close_window"
    onclick = "[PdxGuiWidget.Hide]"
}
```

`input_action` names an action from the input profiles, which is how gamepad and
keyboard users reach a control that has no natural shortcut.

## Filtering mouse buttons

By default a widget reacts to the primary mouse button. `filter_mouse` restricts
which buttons it listens to, expressed as flags:

```text
filter_mouse = left|right
```

`ignore_unset_buttons` marks specific buttons as "not pressed" when deciding the
visual state, which matters for widgets driven by more than one button.

## Drag and drop

Dragging is configured with two blocks: one on the source, one on the target.
Both sides name the drag with a string id, which is how a source and its valid
targets are matched.

**The source** declares what follows the cursor while dragging:

```text
draggable_behavior = {
    draggable_id = "construction_queue_element"

    drag_widget = {
        widget = {
            size = { 1 1 }

            construction_queue_item = {
                position   = "[GuiCurrentDrag.CurrentPosition]"
                widgetanchor = center
            }
        }
    }
}
```

`GuiCurrentDrag.CurrentPosition` is the pointer position during the drag, so the
widget under `drag_widget` behaves like a floating preview.

**The target** declares which ids it accepts and what to do when one lands:

```text
drop_target = {
    accept_draggable_id = "construction_queue_element"
    on_receive_drop = "[Execute( GetDraggedDatacontext('ConstructionQueueElement').MoveToIndex(ConstructionQueueElement.GetIndex) )]"
}
```

`GetDraggedDatacontext('Type')` recovers the object that was being dragged, typed
so its members can be called.

On a pan-and-zoom widget, `draggable_by` says which buttons start the pan:

```text
zoomarea = {
    draggable_by = left|middle
    # ...
}
```

## Sounds

| Property | Played |
|---|---|
| `clicksound` | On click |
| `oversound` | On pointer over |
| `rightclicksound` | On right click |
| `open_sound` / `close_sound` | When a dropdown or window opens or closes |

```text
clicksound = "event:/SFX/UI/Global/select"
```

`clicksound` accepts an expression, which is how the game picks between two
sounds based on state:

```text
clicksound = "[SelectSound( HasNavalContext, 'event:/SFX/UI/Military/naval', 'event:/SFX/UI/Military/land' )]"
```

## Scroll wheel

Scrollbars and scroll areas consume the wheel automatically. A widget can also
declare its own wheel step:

```text
scrollbar = {
    wheelstep = 60
}
```

## Summary: making something feel clickable

The pattern the game uses everywhere:

1. a `button` type with `upframe` / `overframe` / `downframe` / `disableframe`;
2. a named `modify_texture` layer plus two `state` blocks for hover in and out;
3. `enabled` bound to a validity expression;
4. `tooltip` explaining the action, or an expression returning a key;
5. `clicksound`.

That is the whole recipe. [Animation](07-animation.md) covers step 2.

## Next

- [Animation](07-animation.md)
- [Reference: events](reference/events.md)
