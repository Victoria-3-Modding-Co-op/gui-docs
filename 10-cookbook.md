# Cookbook

Short, complete answers to the tasks that come up most often. Each recipe is
standalone.

---

## Restyle an existing element

**Goal:** change how a game widget looks without touching game files.

Find the type that produces the visual, then derive from it and override the
parts you want changed.

```text
# 1. locate the visuals, e.g. in gui/shared/buttons.gui
#    template default_button { ... }
#    type button = button { ... }          <- engine kind defaults

# 2. derive from the engine kind and pull in the shared template
type my_button = button {
    using = default_button

    texture = "gfx/interface/buttons/my_button.dds"
    framesize = { 100 40 }

    blockoverride "text" {
        fontsize = 14
        fontcolor = { 1 1 1 1 }
    }
}
```

If the element is created by a game type you cannot derive from in place, replace
the file at the same relative path.

---

## Add a button to an existing window

**Goal:** put an extra button into a panel the game owns.

Never edit the game file if you can avoid it. Instead, re-declare the panel type
and override the block that holds the buttons.

```text
type my_extra_button = button {
    using = default_button
    size = { 40 40 }
    text = "MY_BUTTON"
    tooltip = "MY_BUTTON_TOOLTIP"
    onclick = "[GetScriptedGui('my_action_sgui').Execute(GuiScope.SetRoot(GetPlayer.MakeScope).End)]"
}
```

```text
type some_game_panel = some_game_panel {
    blockoverride "footer_buttons" {
        my_extra_button = { }
    }
}
```

The `blockoverride` replaces the footer's contents, so re-add the buttons that
were there if you still want them — copy their declaration from the game file.

---

## Show a value with an icon

**Goal:** render "£1.2K" with a coin in front.

```text
textbox = {
    raw_text = "@money![GetPlayer.GetWeeklyIncome|D]"
    autoresize = yes
}
```

For a value that changes size, use a `texticon` and declare the icon once:

```text
texticon = {
    raw_text = "@money![GetPlayer.GetWeeklyIncome|D]"
    icon = money
    iconsize = {
        texture = "gfx/interface/icons/generic_icons/money.dds"
        size = { 25 25 }
        offset = { 0 7 }
        fontsize = 18
    }
}
```

`offset` aligns the icon with the baseline; tweak it by eye.

---

## List every item of a collection

**Goal:** one row per state owned by the player.

```text
scrollarea = {
    size = { 400 300 }

    scrollwidget = {
        dynamicgridbox = {
            datamodel = "[GetPlayer.GetStates]"
            datamodel_wrap = 1

            item = {
                button = {
                    size = { 0 32 }
                    block "row" { }

                    textbox = {
                        parentanchor = left|vcenter
                        text = "[State.GetName]"
                    }

                    onclick = "[SomePanel.Select(State.Self)]"
                }
            }
        }
    }
}
```

- `datamodel` supplies the collection.
- `item` is instantiated once per entry.
- Inside `item`, the entry is available under its scope name (`State`).

If the list is long and rebuilt often, add `datamodel_reuse_widgets = yes` and
`max_update_rate = N` on the container.

---

## Add a hover effect

**Goal:** a soft highlight when the pointer enters.

```text
icon = {
    texture = "gfx/interface/icons/action.dds"
    size = { 40 40 }

    modify_texture = {
        name = "hover"
        texture = "gfx/interface/icons/action_glow.dds"
        blend_mode = add
        alpha = 0
    }

    state = {
        name = enter
        duration = 0.08
        modify_texture = { name = hover alpha = 1 }
    }

    state = {
        name = leave
        duration = 0.14
        modify_texture = { name = hover alpha = 0 }
    }

    onmouseenter = "[PdxGuiWidget.TriggerAnimation('enter')]"
    onmouseleave = "[PdxGuiWidget.TriggerAnimation('leave')]"
}
```

Use `onmousehierarchyenter` / `onmousehierarchyleave` if the widget has children,
so moving onto a child does not count as leaving.

---

## Make a panel draggable and resizable

```text
type my_window = window {
    size = { 640 480 }
    parentanchor = center
    widgetanchor = center

    movable = yes
    resizable = yes
    reorder_on_mouse = press_top
}
```

`reorder_on_mouse` decides whether the window is raised when clicked.

---

## Close a window from a button

```text
close_button = {
    size = { 32 32 }
    texture = "gfx/interface/buttons/close.dds"

    # the button sits inside a vbox inside the window
    onclick = "[PdxGuiWidget.AccessParent.AccessParent.Hide]"
}
```

`AccessParent` walks up one level, so two levels reach the window from a button
placed directly inside its main `vbox`. If your tree is deeper, add another
`AccessParent`.

---

## Bind a tab or filter

**Goal:** several views toggled by a row of buttons, without touching game state.

```text
hbox = {
    button = {
        text = "TAB_ONE"
        down    = "[GetVariableSystem.HasValue('my_tab', 'one')]"
        onclick = "[GetVariableSystem.Set('my_tab', 'one')]"
    }

    button = {
        text = "TAB_TWO"
        down    = "[GetVariableSystem.HasValue('my_tab', 'two')]"
        onclick = "[GetVariableSystem.Set('my_tab', 'two')]"
    }
}

vbox = {
    visible = "[GetVariableSystem.HasValue('my_tab', 'one')]"
}
```

Namespace the variable key (`my_tab`) to avoid colliding with the game's own
interface variables.

---

## Run a script effect from a button

```text
# common/scripted_guis/my_actions.txt
grant_money_sgui = {
    scope = country
    is_shown = { always = yes }
    is_valid = { treasury < 1000000 }
    effect   = { add_treasury = 5000 }
}
```

```text
button = {
    text = "GRANT_MONEY"
    enabled = "[GetScriptedGui('grant_money_sgui').IsValid(GuiScope.SetRoot(GetPlayer.MakeScope).End)]"
    tooltip = "[GetScriptedGui('grant_money_sgui').IsValidTooltip(GuiScope.SetRoot(GetPlayer.MakeScope).End)]"
    onclick = "[GetScriptedGui('grant_money_sgui').Execute(GuiScope.SetRoot(GetPlayer.MakeScope).End)]"
}
```

`IsValidTooltip` returns the failure explanation, which is much better UX than a
disabled button with no reason.

---

## Add a keyboard shortcut

```text
window = {
    shortcut = "my_panel_close"
    onclick  = "[PdxGuiWidget.Hide]"
}
```

```text
# gui/my_panel.shortcuts
my_panel_close = {
    key = "escape"
}
```

The shortcut name must be unique. Give mod shortcuts a prefixed name.

---

## Make a list row react to the right click

```text
item = {
    button = {
        # left click selects, right click opens a menu
        onclick      = "[SomePanel.Select(Goods.Self)]"
        onrightclick = "[RightClickMenuManager.Open('goods_menu', Goods.Self)]"
    }
}
```

Modifier-aware variants use `click_modifiers`:

```text
click_modifiers = {
    ondefault = "[SomePanel.Select(Goods.Self)]"
    onshift   = "[SomePanel.SelectRange(Goods.Self)]"
}
```

---

## Debug an expression that does nothing

1. Check the newest `error.log` — evaluation failures are logged with the file
   and line.
2. Confirm the scope: put `text = "[PdxGuiWidget.HasContext(...)]"` or print the
   context's type through a debug tooltip.
3. Guard nulls with `IsValid` before dereferencing.
4. Simplify: replace the expression with a literal to prove the property path
   works, then reintroduce one call at a time.

A property that silently keeps its default is almost always a failed evaluation,
not a layout problem.

---

## Find which type produces a widget on screen

1. Turn on the widget inspector in the console and click the element.
2. The inspector shows the widget's type name and its source file and line.
3. Search for that type name in `gui/` — you will find the declaration, and from
   there its base chain.

That is the fastest route from "I want to change this" to "this is the file to
change".

---

## Open a panel while testing

A top-level widget definition can be created directly from the console:

```text
GUI.CreateWidget gui/my_panel.gui my_panel
```

The first argument is the file, the second the `name` of the root widget. This
is also how the shipped debug menus open their own windows, with
`ExecuteConsoleCommand` bound to a button:

```text
onclick = "[ExecuteConsoleCommand('GUI.CreateWidget gui/my_panel.gui my_panel')]"
```

---

## Next

- [Reference](reference/README.md) — every property, event and function.
