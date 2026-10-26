# button_group

Keeps a set of checkbuttons mutually exclusive.

## At a glance

- **Kind:** `button_group`
- **Category:** Interaction
- **Children:** none
- **Used in the shipped interface:** 21 times

## When to use it

Keeps several checkbuttons mutually exclusive.

## Also used on game types derived from this kind

These properties are not declared on the engine kind itself, but appear on game types that derive from it. They are listed here because looking them up usually starts from the kind.

| Property | Value type | Meaning |
|---|---|---|
| `checked` | bool | State of a checkbutton. |
| `text` | loc | Text to display: a localisation key, a literal string, or a data-binding expression returning either. Supports `#` formatting tags and `$` arguments. |
| `align` | flags | Horizontal and vertical alignment of the text inside its box. |
| `raw_text` | string | Text displayed without localisation lookup, usually to mix literals with data bindings. |

## Common properties

All widgets also accept the [common properties](../common-properties.md); they are not repeated here.
