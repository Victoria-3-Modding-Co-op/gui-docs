# Widget kinds

Every block in a `.gui` file that creates a widget uses one of the engine kinds below, or a game type that ultimately derives from one. The kind is written as the key of the block:

```text
vbox = {             # vbox is the kind
    spacing = 4
    textbox = { }    # textbox is the kind
}
```

## Index

- [Interaction](#interaction)
  - [`button`](widgets/button.md)
  - [`button_group`](widgets/button_group.md)
  - [`checkbutton`](widgets/checkbutton.md)
  - [`colorpicker`](widgets/colorpicker.md)
  - [`dropDown`](widgets/dropDown.md)
  - [`scrollbar`](widgets/scrollbar.md)
- [Layout](#layout)
  - [`container`](widgets/container.md)
  - [`dynamicgridbox`](widgets/dynamicgridbox.md)
  - [`fixedgridbox`](widgets/fixedgridbox.md)
  - [`flowcontainer`](widgets/flowcontainer.md)
  - [`hbox`](widgets/hbox.md)
  - [`margin_widget`](widgets/margin_widget.md)
  - [`overlappingitembox`](widgets/overlappingitembox.md)
  - [`scrollarea`](widgets/scrollarea.md)
  - [`stackedwidget`](widgets/stackedwidget.md)
  - [`tabbar`](widgets/tabbar.md)
  - [`tabwidget`](widgets/tabwidget.md)
  - [`vbox`](widgets/vbox.md)
  - [`widget`](widgets/widget.md)
  - [`window`](widgets/window.md)
- [Text](#text)
  - [`editbox`](widgets/editbox.md)
  - [`textbox`](widgets/textbox.md)
  - [`texticon`](widgets/texticon.md)
- [Visual](#visual)
  - [`background`](widgets/background.md)
  - [`icon`](widgets/icon.md)
  - [`line`](widgets/line.md)
  - [`minimap`](widgets/minimap.md)
  - [`minimap_window`](widgets/minimap_window.md)
  - [`piechart`](widgets/piechart.md)
  - [`pieslice`](widgets/pieslice.md)
  - [`plotline`](widgets/plotline.md)
  - [`progressbar`](widgets/progressbar.md)
  - [`treemapchart`](widgets/treemapchart.md)
  - [`treemapslice`](widgets/treemapslice.md)

## Interaction

| Kind | Purpose | Uses |
|---|---|---|
| [`button`](widgets/button.md) | A clickable widget with over/down/disabled visual states. | 2,722 |
| [`button_group`](widgets/button_group.md) | Keeps a set of checkbuttons mutually exclusive. | 21 |
| [`checkbutton`](widgets/checkbutton.md) | A toggle button with a checked state. | 49 |
| [`colorpicker`](widgets/colorpicker.md) | An HSV/RGB colour selection popup. | 0 |
| [`dropDown`](widgets/dropDown.md) | A collapsing list of selectable items. | 12 |
| [`scrollbar`](widgets/scrollbar.md) | A draggable bar with decrement/increment buttons. | 17 |

## Layout

| Kind | Purpose | Uses |
|---|---|---|
| [`container`](widgets/container.md) | A widget whose children keep their own absolute positions. | 1,494 |
| [`dynamicgridbox`](widgets/dynamicgridbox.md) | A grid driven by a data model, building one child per entry. | 165 |
| [`fixedgridbox`](widgets/fixedgridbox.md) | A grid whose cell sizes come from the declared column and row sizes. | 77 |
| [`flowcontainer`](widgets/flowcontainer.md) | Wraps its children onto new rows or columns when it runs out of room. | 3,517 |
| [`hbox`](widgets/hbox.md) | Lays its children out horizontally. | 871 |
| [`margin_widget`](widgets/margin_widget.md) | Reserves a margin around a single child. | 49 |
| [`overlappingitembox`](widgets/overlappingitembox.md) | Lays children out in sequence, letting them overlap. | 43 |
| [`scrollarea`](widgets/scrollarea.md) | A viewport that scrolls its scrollwidget, with automatic scrollbars. | 74 |
| [`stackedwidget`](widgets/stackedwidget.md) | Shows one of its children at a time, selected by index. | 0 |
| [`tabbar`](widgets/tabbar.md) | The button strip used by a tabwidget. | 0 |
| [`tabwidget`](widgets/tabwidget.md) | A tabbed container: a tab bar plus a stacked widget. | 0 |
| [`vbox`](widgets/vbox.md) | Stacks its children vertically. | 806 |
| [`widget`](widgets/widget.md) | The base widget. A bare rectangle that can be positioned, textured and shown or hidden, with no layout behaviour of its own. | 4,414 |
| [`window`](widgets/window.md) | A draggable, resizable top-level panel. | 94 |

## Text

| Kind | Purpose | Uses |
|---|---|---|
| [`editbox`](widgets/editbox.md) | An editable single-line text field. | 35 |
| [`textbox`](widgets/textbox.md) | A non-editable block of text, with optional inline icons and text formatting. | 4,319 |
| [`texticon`](widgets/texticon.md) | A textbox whose string may embed icon tokens. | 446 |

## Visual

| Kind | Purpose | Uses |
|---|---|---|
| [`background`](widgets/background.md) | A texture drawn behind its parent widget. | 1,252 |
| [`icon`](widgets/icon.md) | Draws a texture (optionally a sprite sheet) with an optional modify texture and glow. | 2,517 |
| [`line`](widgets/line.md) | A polyline or spline drawn between points. | 2 |
| [`minimap`](widgets/minimap.md) | Renders the map minimap texture. | 1 |
| [`minimap_window`](widgets/minimap_window.md) | The window that hosts the minimap. | 1 |
| [`piechart`](widgets/piechart.md) | A pie chart container. | 4 |
| [`pieslice`](widgets/pieslice.md) | One slice of a piechart. | 4 |
| [`plotline`](widgets/plotline.md) | A line chart over a series of points. | 16 |
| [`progressbar`](widgets/progressbar.md) | A horizontal or vertical bar showing a value in a range. | 58 |
| [`treemapchart`](widgets/treemapchart.md) | A treemap chart container. | 2 |
| [`treemapslice`](widgets/treemapslice.md) | One slice of a treemapchart. | 2 |
