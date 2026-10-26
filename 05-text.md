# Text

Text appears in `textbox`, `button`, `editbox` and inside tooltips. The system
has three jobs: find the string, format it, and lay it out.

## `text` versus `raw_text`

Both display a string. The difference is whether the game looks it up.

| Property | Behaviour |
|---|---|
| `text` | The value is a **localisation key**. It is looked up in the language files, so the same widget shows translated text. |
| `raw_text` | The value is shown **as written**. |

```text
textbox = { text = "CLOSE_TOOLTIP" }          # translated
textbox = { raw_text = "#bold Custom#!" }     # shown literally
```

Both accept a data-binding expression. If the expression returns a
localisation key, `text` translates it:

```text
text = "[concept_company_hq]"     # expression yields a key, then translated
```

Almost every user-visible string in a well-behaved interface is a key in `text`.
`raw_text` exists for values assembled from parts, for debug displays, and for
strings that mix literal punctuation with bindings:

```text
raw_text = "[Building.GetState.GetName] (3)"
```

## Mixing bindings into a string

A string value may contain any number of `[ ... ]` expressions. They are
evaluated and substituted before the text is laid out:

```text
raw_text = "[Character.GetName] - [Character.GetRole.GetName]"
```

That is often more convenient than concatenating inside the expression, because
the literal parts stay readable in the file.

## Formatting tags

Inside a string, `#name` opens a format and `#!` closes it. Formats nest and
combine:

```text
text = "#variable #BOLD £[GetPlayer.GetWeeklyIncome|D]#!#!"
```

### Where the names come from

A tag name resolves to one of two things:

- a **named format** declared in a `textformatting` block (see below);
- a **font style**: `bold`, `italic`, `strikethrough`, `extrabold`, and the
  other styles the fonts declare.

The game's own strings use both: `#BOLD` and `#b` are styles, `#variable`,
`#positive_value` and `#tooltip_header` are named formats. Tags are
case-insensitive in practice, but the shipped files are inconsistent about it
(`#BOLD` and `#bold` both occur).

### Declaring a named format

A `textformatting` block anywhere in a `.gui` file defines formats. Each one is
a `name` and a `format` string made of semicolon-separated style tokens:

```text
textformatting = {
    format = {
        name = positive_value
        format = "color:{0.39,0.67,0.33}"
    }

    format = {
        name = tooltip_header
        format = "bold;color:{0.8,0.73,0.5};glow_color:{0,0,0,1}"
    }

    format = {
        name = clickable_link_hover
        format = "clickable_link;italic"
    }
}
```

The tokens available in a definition:

| Token | Effect |
|---|---|
| `bold`, `italic`, `strikethrough`, `extrabold`, ... | Font style |
| `color:{ r, g, b }` | Text colour, components in 0..1 |
| `glow_color:{ r, g, b, a }` | Glow colour |
| `shadow` | Drop shadow |
| another format's name | Inherit that format, then continue |

Declaring your own is a normal modding move: add a `textformatting` block in any
`.gui` file and the tag becomes available everywhere.

### Formats you will meet constantly

| Tag | Typical meaning |
|---|---|
| `#variable` | Game values inside prose |
| `#positive_value` / `#negative_value` | Good / bad numbers |
| `#zero_value` | Neutral numbers |
| `#b`, `#BOLD`, `#i`, `#italic` | Emphasis |
| `#header`, `#title`, `#h1` | Headings |
| `#tooltip_header`, `#tooltip_sub_header` | Tooltip structure |
| `#concept`, `#tooltippable`, `#glossary` | Clickable encyclopedia links |
| `#flavor`, `#lore` | Narrative text |
| `#instruction`, `#help`, `#warning` | Player guidance |
| `#indent_newline` | Line break with indentation |
| `#X`, `#N`, `#P`, `#T`, `#v`, `#r` | Single-letter house styles |

The definitive list is the set of `name = ...` entries in the game's
`gui/textformatting.gui`, plus any format a mod declares.

### Remapping formats

`format_override` rewrites a format name for a subtree. It takes a block of
pairs: the name to replace, then the name to use instead.

```text
template light_background_overrides {
    format_override = { high light_background }
    format_override = { positive_value positive_value_on_light }
}
```

This is how the same text templates are reused on dark and light backgrounds
without duplicating every string.

## Inline icons

Two mechanisms put icons inside running text.

### Text icons

A `texticon` widget can embed icons by name. The string uses `@name!`:

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

Every `icon` declares one token; the next `iconsize` block says how it is drawn.
`offset` is the vertical nudge that aligns the icon with the text baseline, and
`fontsize` ties the icon size to the text size so that scaling the text scales
the icon.

### Icon sequences in plain text

An ordinary `textbox` can also contain `@name!` tokens, which the game resolves
against the icon table. That is why a value like

```text
raw_text = "@money! [GetPlayer.GetWeeklyIncome|D]"
```

renders a coin followed by a number.

## Value formatting: the `|` suffix

An expression may end with `|` and a format specification. This is how numbers
become "£1.2M" instead of "1200000.0".

```text
[GetPlayer.GetWeeklyIncome|D]
[BattleMilitaryFormation.GetAverageOffense|0v]
[Battle.GetDefenderTotalDead|D]
[GetPlayer.GetWeeklyExpenses|D-]
```

The specification is a small language of its own, made of combinable pieces:

| Piece | Meaning |
|---|---|
| `0`–`9` | Number of decimal places |
| `v` | Compact value: thousands, millions, ... |
| `D` | Currency, with the currency symbol |
| `%` | Percentage |
| `+` | Always show the sign |
| `-` | Show the sign only when negative |

Pieces combine left to right, which is why `0v`, `D+`, `D-`, `v0%` and `D+=` all
appear in the shipped files. The exact set is worth experimenting with: the
fastest way to get the format you want is to copy a similar line from an
existing file and change one piece at a time.

## Typography

```text
textbox = {
    text = "EXAMPLE"
    font = "EBGaramond"
    fontsize = 17
    fontcolor = { 0.9 0.87 0.8 1 }
    align = left|nobaseline
}
```

| Property | Effect |
|---|---|
| `font` | Font family, as declared by the game's font files |
| `fontsize` | Size in interface pixels |
| `fontsize_min` | Floor when the text is shrunk to fit |
| `elide` | Where to cut the string: `none`, `right`, `left`, `middle` |
| `align` | `left`, `right`, `hcenter`, `top`, `bottom`, `vcenter`, `center`, with optional `baseline` / `nobaseline` |
| `multiline` | Allow wrapping |
| `autoresize` | Grow the widget to fit the text |
| `maxcharacters` | Input limit on an edit box |
| `text_selectable` | Allow selecting and copying |
| `default_format` | Format applied to the whole string, e.g. `"#b"` |

`fontsize_min` is the usual companion of `autoresize` in tight layouts: the box
tries the requested size, then shrinks the text down to the minimum rather than
eliding it.

## Edit boxes

An `editbox` displays and edits text. It adds a few properties:

```text
editbox = {
    size = { 260 32 }
    multiline = no
    maxcharacters = 64
    text = "[SaveGameWindow.GetSaveName]"
    ontextedited = "[SaveGameWindow.UpdateSaveName]"
    onreturnpressed = "[SaveGameWindow.Confirm]"
}
```

- `multiline = yes` turns it into a text area.
- `accept_tabs` lets Tab insert a tab character instead of moving focus.
- `text_validator` restricts what may be typed.
- `focus_on_visible = yes` focuses the field as soon as it appears, which is what
  a rename dialog wants.

## Tooltips are text too

`tooltip` takes a localisation key or an expression returning one, and the same
tags apply:

```text
tooltip = "CLOSE_TOOLTIP"
tooltip = "[Character.GetTooltip]"
raw_tooltip = "#todo unfinished#!"
```

For longer content, `tooltipwidget` substitutes a whole widget tree; see
[Interaction](06-interaction.md).

## Next

- [Interaction](06-interaction.md)
- [Reference: templates](reference/templates.md)
