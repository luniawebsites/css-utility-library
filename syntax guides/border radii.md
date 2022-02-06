# Border Radii

Add a radius to any or all corners of an HTML element. Content overflow is hidden.  Can be applied to any inline or block-level element.

**Example:**

Instruct the HTML `div` element, starting at the small viewport, to apply a radius to all corners:

```html
<div data-util="bor:sm:rad"></div>
```

## Syntax Options

Apply any combination of the below to an inline or block-level HTML element.

| Target                           | Viewport/State    | Value        |
|----------------------------------|-------------------|--------------|
| `bor` all borders                | `sm` small        | `rad` radius |
| `bor-tr` top right of element    | `sm.` small only  |              |
| `bor-br` bottom right of element | `md` medium       |              |
| `bor-bl` bottom left of element  | `md.` medium only |              |
| `bor-tl` top left of element     | `lg` large        |              |
|                                  | `hv` hover        |              |
