# Shadow

Apply a drop shadow effect to an HTML element. Can be applied to any inline or block-level element.

**Example:**

Instruct an HTML `div` element, starting at the small viewport, to apply a dark drop shadow:

```html
<div data-util="shd:sm:drk"></div>
```

## Syntax Options

Apply any combination of the below to an inline or block-level HTML element.

| Target       | Viewport/State    | Value        |
|--------------|-------------------|--------------|
| `shd` shadow | `sm` small        | `lgt` light  |
|              | `sm.` small only  | `drk` dark   |
|              | `md` medium       |              |
|              | `md.` medium only |
|              | `lg` large        |              |
|              | `hv` hover        |              |
