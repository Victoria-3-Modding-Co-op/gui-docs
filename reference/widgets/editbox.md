# editbox

An editable single-line text field.

## At a glance

- **Kind:** `editbox`
- **Category:** Text
- **Children:** text content with inline icons
- **Derives from:** `textbox`
- **Used in the shipped interface:** 35 times

## When to use it

An editable text field.

## Properties specific to this kind

Declared on the engine kind itself in the shipped interface. Every widget also accepts the [common properties](../common-properties.md).

| Property | Value type | Meaning | Example |
|---|---|---|---|
| `align` | flags | Horizontal and vertical alignment of the text inside its box. | `align = left\|nobaseline` |
| `maxcharacters` | int | Maximum number of characters accepted in an edit box. | `maxcharacters = 50` |
| `ontextedited` | expression | Called while the contents of an edit box change. | `ontextedited = "[CompanyChangeNamePopup.OnEditName]"` |
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. | `text = "CHANGE_RNG_SEED"` |
| `text_validator` | token | Name of the validator applied to an edit box, for example `int`, `float` or `hex_color`. | `text_validator = "[ArticleDraft.GetQuantityValidator]"` |
| `raw_text` | string | Text displayed without localisation lookup, usually to mix literals with data bindings. | `raw_text = "0"` |
| `default_format` | string | Formatting string applied to the whole text, for example `"#b"` for bold. | `default_format = "#variable"` |
| `ontextchanged` | expression | Called after the text of an edit box has changed. | `ontextchanged = "[ArticleDraft.OnQuantityChanged]"` |
| `gfxtype` | token | Name of the engine draw type used for the widget, for example `buttongfx`, `windowgfx` or `progressbargfx`. | `gfxtype = editboxgfx` |
| `shaderfile` | texture | Path of the shader used by the draw type. | `shaderfile = "gfx/FX/pdxgui_default.shader"` |
| `multiline` | bool | Allow the text to wrap onto several lines. | `multiline = yes` |
| `oneditingfinished` | expression | Older name for the edit-finished callback. | `oneditingfinished = "[ArticleDraft.OnQuantityChanged]"` |
| `fontsize` | int | Font size in interface pixels. | `fontsize = 17` |

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `onreturnpressed` | expression | Called when Enter is pressed in an edit box. |
| `cursorcolor` | colour | Colour of the text cursor. |

## Notes

Use `multiline = yes` for a text area and `text_validator` to restrict what can be typed.

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
