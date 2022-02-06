# Gutters

Apply a left and right margin to an HTML element. Can be applied to any inline or block-level element.

**Example:**

Instruct an HTML `div` element, starting at the small viewport, to apply a 1em (16px) margin to both its left and right side:

```html
<div data-util="gut:sm:1,0"></div>
```

## Syntax Options

Apply any combination of the below to an inline or block-level HTML element.

| Target       | Viewport          | Value              |
|--------------|-------------------|--------------------|
| `gut` gutter | `sm` small        | `1,0` 1em (16px)   |
|              | `sm.` small only  | `1,5` 1.5em (24px) |
|              | `md` medium       | `2,0` 2em (32px)   |
|              | `md.` medium only | `3,0` 3em (48px)   |
|              | `lg` large        |                    |
