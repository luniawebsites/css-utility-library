# Display

Set display options for an HTML element. Can be applied to any inline or block-level element.

**Example:**

Instruct an HTML `div` element, at the small viewport only, to hide:

```html
<div data-util="dis:sm.:hid"></div>
```

## Syntax Options

Apply any combination of the below to an inline or block-level HTML element.

| Target        | Viewport          | Value                   |
|---------------|-------------------|-------------------------|
| `dis` display | `sm` small        | `hid` hide              |
|               | `sm.` small only  | `hid-emp` hide if empty |
|               | `md` medium       |                         |
|               | `md.` medium only |                         |
|               | `lg` large        |                         |
