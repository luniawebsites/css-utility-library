# Grid

Apply a grid layout to an HTML element. Can be applied to any block-level element. The gaps between the columns and rows automatically increase at each viewport.

**Example:**

Instruct an HTML `div` element, starting at the small viewport, to apply a grid layout with 300px wide columns:

```html
<div data-util="grd:sm:300"></div>
```

## Syntax Options

Apply any combination of the below to a block-level HTML element.

| Target     | Viewport          | Value                    |
|------------|-------------------|--------------------------|
| `grd` grid | `sm` small        | `300` 300px wide columns |
|            | `sm.` small only  | `400` 400px wide columns |
|            | `md` medium       |                          |
|            | `md.` medium only |                          |
|            | `lg` large        |                          |
