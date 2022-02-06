# Buttons

Style an HTML element to look like a primary or secondary button. Can be applied to any inline or block-level element.

**Example:**

Instruct an HTML `button` element, starting at the small viewport, to apply a primary button style at the full available width of its parent element:

```html
<button data-util="btn:sm:max"></button>
```

## Syntax Options

Apply any combination of the below to an inline or block-level HTML element.

| Target                     | Viewport          | Value                |
|----------------------------|-------------------|----------------------|
| `btn` primary button       | `sm` small        | `fix` fixed width    |
| `btn-sec` secondary button | `sm.` small only  | `max` maximum width  |
|                            | `md` medium       | `min` fit to content |
|                            | `md.` medium only |                      |
|                            | `lg` large        |                      |
