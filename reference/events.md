# Events

Callbacks are ordinary properties whose value is a data-binding expression. They run when the corresponding event reaches the widget. The expression is evaluated with the widget as `PdxGuiWidget` and the widget's data context as the top scope.

## Widget events

Callbacks used by the shipped interface. The **Available on** column lists the kinds they appear on.

| Callback | Available on | Fires when | Example |
|---|---|---|---|
| `onclick` | 12 kinds | Called when the widget is clicked. | `onclick = "[InformationPanel.SelectTab('default')]"` |
| `ondoubleclick` | `button` | Called on a double click. | `ondoubleclick = "[SaveGameItem.SelectAndLoad]"` |
| `oneditingfinished` | `editbox` | Older name for the edit-finished callback. | `oneditingfinished = "[ArticleDraft.OnQuantityChanged]"` |
| `onmousehierarchyenter` | 10 kinds | Called when the pointer enters the widget or any of its children. | `onmousehierarchyenter = "[SetTempMapModeByKey('mm_literacy')]"` |
| `onmousehierarchyleave` | 9 kinds | Called when the pointer leaves the widget and all of its children. | `onmousehierarchyleave = "[RemoveTempMapMode]"` |
| `onreturnpressed` | `editbox`, `hbox`, `margin_widget`, `vbox` | Called when Enter is pressed in an edit box. | `onreturnpressed = "[EncyclopediaPage.FilterFromText]"` |
| `onrightclick` | `button`, `container`, `widget` | Called on a right click. | `onrightclick = "[RightClickMenuManager.ShowForState(State.AccessSelf)]"` |
| `onselectionchanged` | `dropDown` | Called when the selection in a dropdown or list changes. | `onselectionchanged = "[SetDefaultMapMode]"` |
| `ontextchanged` | `editbox`, `hbox` | Called after the text of an edit box has changed. | `ontextchanged = "[LoginView.SetEmail]"` |
| `ontextedited` | `editbox`, `hbox`, `vbox` | Called while the contents of an edit box change. | `ontextedited = "[JominiServerBrowserGui.OnFilterTextEdit]"` |
| `onvaluechanged` | `scrollbar` | Called when a scrollbar or slider value changes. | `onvaluechanged = "[MusicPlayer.SetVolume]"` |

## Engine callbacks not used by the shipped interface

The engine routes these, but no shipped `.gui` file subscribes to them. They are available to mods and are safe to use.

| Callback | Fires when |
|---|---|
| `oncolorchanged` | Called while the colour picker selection changes. |
| `oncoloredited` | Called when a colour picker edit is committed. |
| `onmouseenter` | Called when the pointer enters the widget. |
| `onmouseleave` | Called when the pointer leaves the widget. |
| `onpressed` | Called when the mouse button goes down over the widget. |
| `onreleased` | Called when the mouse button comes up. |

## Animation state callbacks

These are written inside a `state` block rather than on the widget; they belong to the animation state, not to the widget.

| Callback | Fires when | Example |
|---|---|---|
| `on_finish` | Called when the animation state finishes. | `on_finish = "[PdxGuiTriggerAllAnimations('character_panel_stat')]"` |
| `on_start` | Called when the animation state starts. | `on_start = "[PdxGuiWidget.FindChild('expand_arrow').TriggerAnimation('mouse_enter')]"` |
