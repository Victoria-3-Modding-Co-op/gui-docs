# tabwidget

A tabbed container: a tab bar plus a stacked widget.

## At a glance

- **Kind:** `tabwidget`
- **Category:** Layout
- **Children:** engine-managed slots
- **Used in the shipped interface:** 0 times (available to mods, not used by the base game)

## When to use it

A tab bar plus a stacked widget, kept in sync by the engine.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `tabbar_widget` | The tab button strip. |
| `tabcontent` | The stacked content area. |

## Notes

Used by the engine's tool screens; available to mods. Most game interfaces build tabs by hand from buttons plus `GetVariableSystem`, because that gives more control over styling.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
