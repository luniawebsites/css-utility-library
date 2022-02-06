# Heights

Set the height of an HTML element. Can be applied to any block-level element.

**Example:**

Instruct an HTML `div` element, starting at the small viewport, to use the full available height of its parent element:

```html
<div data-util="hgt:sm:max"></div>
```

## Syntax Options

Apply any combination of the below to a block-level HTML element.

| Target       | Viewport          | Value                |
|--------------|-------------------|----------------------|
| `hgt` height | `sm` small        | `scn` screen height  |
|              | `sm.` small only  | `max` maximum        |
|              | `md` medium       | `min` fit to content |
|              | `md.` medium only |                      |
|              | `lg` large        |                      |
