# Flexbox

Apply the flexbox display property to an HTML element. Can be applied to any block-level element.

**Example:**

Instruct an HTML `div` element, starting at the small viewport, to act as a flexbox column with its children elements positioned left and centre:

```html
<div data-util="col:sm:lc"></div>
```

## Syntax Options

Apply any combination of the below to a block-level HTML element.

| Target                | Viewport          | Value                                  |
|-----------------------|-------------------|----------------------------------------|
| `col` flexbox column  | `sm` small        | `str` stretch children                 |
| `row` flexbox row     | `sm.` small only  | `btw` space between children           |
|                       | `md` medium       | `lt` position children left & top      |
|                       | `md.` medium only | `lc` position children left & centre   |
|                       | `lg` large        | `lb` position children left & bottom   |
|                       |                   | `ct` position children centre & top    |
|                       |                   | `cc` position children centre & centre |
|                       |                   | `cc` position children centre & bottom |
|                       |                   | `rt` position children right & top     |
|                       |                   | `rc` position children right & centre  |
|                       |                   | `rb` position children right & bottom  |
