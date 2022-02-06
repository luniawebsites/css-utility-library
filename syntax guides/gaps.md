# Gaps

Used in combination with `col` and `row` utilities to set the spacing between the element's children. Can be applied to any block-level element.

**Example:**

Instruct an HTML `div` element, starting at the small viewport, to add 1em (16px) space between all its child elements:

```html
<div data-util="gap:sm:1,0"></div>
```

## Syntax Options

Apply any combination of the below to a block-level HTML element.

| Target    | Viewport          | Value              |
|-----------|-------------------|--------------------|
| `gap` gap | `sm` small        | `0,5` 1/2em (8px)  |
|           | `sm.` small only  | `1,0` 1em (16px)   |
|           | `md` medium       | `1,5` 1.5em (24px) |
|           | `md.` medium only | `2,0` 2em (32px)   |
|           | `lg` large        | `3,0` 3em (48px)   |
