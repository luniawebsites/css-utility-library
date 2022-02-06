# Text Formats

Apply a colour, format, decoration or shadow to text inside an HTML element. Can be applied to any element containing text.

**Example:**

Instruct an HTML `p` element, starting at the small viewport, to set its contained text to blue:

```html
<p data-util="txt:sm:blu"></p>
```

## Syntax Options

Apply any combination of the below to an inline or block-level HTML element.

| Target     | Viewport          | Value                  |
|------------|-------------------|------------------------|
| `txt` text | `sm` small        | `wht` white            |
|            | `sm.` small only  | `red-lgt` light red    |
|            | `md` medium       | `red` red              |
|            | `md.` medium only | `red-drk` dark red     |
|            | `lg` large        | `grn-lgt` light green  |
|            | `hv` hover        | `grn` green            |
|            |                   | `grn-drk` dark green   |
|            |                   | `blu-lgt` light blue   |
|            |                   | `blu` blue             |
|            |                   | `blu-drk` dark blue    |
|            |                   | `ylw-lgt` light yellow |
|            |                   | `ylw` yellow           |
|            |                   | `ylw-drk` dark yellow  |
|            |                   | `pur-lgt` light purple |
|            |                   | `pur` purple           |
|            |                   | `pur-drk` dark purple  |
|            |                   | `gry-lgt` light grey   |
|            |                   | `gry` grey             |
|            |                   | `gry-drk` dark grey    |
|            |                   | `bld` bold             |
|            |                   | `und` underline        |
|            |                   | `shd` shadow           |
