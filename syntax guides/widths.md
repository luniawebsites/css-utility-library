# Widths

Set the width of an HTML element. Can be applied to any block-level element.

**Example:**

Instruct an HTML `div` element, starting at the small viewport, to use 50% of the available width of its parent element:

```html
<div data-util="wid:sm:50"></div>
```

## Syntax Options

Apply any combination of the below to a block-level HTML element.

| Target       | Viewport          | Value                |
|--------------|-------------------|----------------------|
| `wid` width  | `sm` small        | `10` 10%             |
|              | `sm.` small only  | `20` 20%             |
|              | `md` medium       | `30` 30%             |
|              | `md.` medium only | `40` 40%             |
|              | `lg` large        | `50` 50%             |
|              |                   | `60` 60%             |
|              |                   | `70` 70%             |
|              |                   | `80` 80%             |
|              |                   | `90` 90%             |
|              |                   | `max` maximum        |
|              |                   | `min` fit to content |
