# Margins

Set the margins around an HTML element. Can be applied to any inline or block-level element.

**Example:**

Instruct an HTML `div` element, starting at the small viewport, to add a 1em (16px) margin to all sides:

```html
<div data-util="mar:sm:1,0"></div>
```

## Syntax Options

Apply any combination of the below to an inline or block-level HTML element.

| Target                      | Viewport          | Value              |
|-----------------------------|-------------------|--------------------|
| `mar` margin                | `sm` small        | `0,25` 1/4em (4px) |
| `mar-x` margin left & right | `sm.` small only  | `0,5` 1/2em (8px)  |
| `mar-y` margin top & bottom | `md` medium       | `1,0` 1em (16px)   |
| `mar-t` margin top          | `md.` medium only | `1,5` 1.5em (24px) |
| `mar-r` margin right        | `lg` large        | `2,0` 2em (32px)   |
| `mar-b` margin bottom       |                   | `3,0` 3em (48px)   |
| `mar-l` margin left         |                   |                    |
