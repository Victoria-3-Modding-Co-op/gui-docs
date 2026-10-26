# textbox

A non-editable block of text, with optional inline icons and text formatting.

## At a glance

- **Kind:** `textbox`
- **Category:** Text
- **Children:** text content with inline icons
- **Derives from:** `widget`
- **Used in the shipped interface:** 4,319 times

## When to use it

Displays text. Text may contain formatting tags and inline data-binding expressions.

## Slots

These children are not ordinary widgets: the engine places a widget there, or instantiates the block once per data model entry.

| Slot | Purpose |
|---|---|
| `tooltipwidget` | Custom tooltip body. |

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `align` | flags | Horizontal and vertical alignment of the text inside its box. | `align = center\|nobaseline` |
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. | `text = "ACHIEVEMENT_UNLOCKED"` |
| `elide` | token | Where to cut the string when it does not fit. | `elide = right` |
| `raw_text` | string | Text displayed without localisation lookup, usually to mix literals with data bindings. | `raw_text = "#BOLD [WarGoal.GetNameNoIcon]#!"` |
| `fontsize_min` | int | Smallest size the text may shrink to when the box is too small. | `fontsize_min = 14` |
| `multiline` | bool | Allow the text to wrap onto several lines. | `multiline = yes` |
| `default_format` | string | Formatting string applied to the whole text, for example `"#b"` for bold. | `default_format = "#v"` |
| `fontsize` | int | Font size in interface pixels. | `fontsize = 36` |
| `fonttintcolor` | colour | Tint applied to the text glyphs. | `fonttintcolor = "[TooltipInfo.GetTintColor]"` |
| `fontcolor` | colour | Text colour. | `fontcolor = "[MusicPlayer.GetTrackTextColor( MusicTrack.Self )]"` |
| `gfxtype` | token | Name of the engine draw type used for the widget, for example `buttongfx`, `windowgfx` or `progressbargfx`. | `gfxtype = textboxgfx` |
| `shaderfile` | texture | Path of the shader used by the draw type. | `shaderfile = "gfx/FX/pdxgui_default.shader"` |
| `font` | string | Font family name, as declared in the game's font files. | `font = "PlayfairDisplay"` |
| `maxcharacters` | int | Maximum number of characters accepted in an edit box. | `maxcharacters = 3000` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `text_selectable` | bool | Allow the player to select and copy the text. |

## `state` sub-object

One animation state. A widget may declare several; each is addressed by `name` from script.

| Key | Meaning | Example |
|---|---|---|
| `alpha` | Target opacity, 0..1. | `alpha = 1` |
| `delay` | Delay before the state starts, in seconds. | `delay = 0.15` |
| `duration` | Length of the animation in seconds. | `duration = 0.15` |
| `name` | Identifier of the state, referenced by `TriggerAnimation('name')` and by `next`. | `name = show_cash_reserves_max` |
| `next` | State to play when this one finishes. | `next = game_over_screen_info1_b` |
| `position` | Target position, `{ x y }`. | `position = { 0 -20 }` |
| `position_x` | Target position on the x axis only. | `position_x = -10` |
| `position_y` | Target position on the y axis only. | `position_y = 0` |
| `start_sound` | Sound played when the state starts. |  |
| `trigger_on_create` | Play the state when the widget is created. | `trigger_on_create = yes` |

## Notes

`autoresize` makes the box grow to fit its string, which is the usual choice for labels.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
