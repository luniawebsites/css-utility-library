# Padding

Set the padding (inside margins) of an HTML element. Can be applied to any inline or block-level element.

**Example:**

Instruct an HTML `div` element, starting at the small viewport, to add 1em (16px) padding to all sides:

```html
<div data-util="pad:sm:1,0"></div>
```

## Syntax Options

Apply any combination of the below to an inline or block-level HTML element.

| Target                       | Viewport          | Value              |
|------------------------------|-------------------|--------------------|
| `pad` padding                | `sm` small        | `0,25` 1/4em (4px) |
| `pad-x` padding left & right | `sm.` small only  | `0,5` 1/2em (8px)  |
| `pad-y` padding top & bottom | `md` medium       | `1,0` 1em (16px)   |
| `pad-t` padding top          | `md.` medium only | `1,5` 1.5em (24px) |
| `pad-r` padding right        | `lg` large        | `2,0` 2em (32px)   |
| `pad-b` padding bottom       |                   | `3,0` 3em (48px)   |
| `pad-l` padding left         |                   |                    |
