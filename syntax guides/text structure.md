# Text Structure

Apply a font, size, alignment or structure to text inside an HTML element. Can be applied to any element containing text.

**Example:**

Instruct an HTML `p` element, starting at the small viewport, to set its contained text to 18px:

```html
<p data-util="txt:sm:2"></p>
```

## Syntax Options

Apply any combination of the below to an inline or block-level HTML element.

| Target     | Viewport          | Value                   |
|------------|-------------------|-------------------------|
| `txt` text | `sm` small        | `std` standard font     |
|            | `sm.` small only  | `fix` fixed width font  |
|            | `md` medium       | `0` 14px                |
|            | `md.` medium only | `1` 16px                |
|            | `lg` large        | `2` 18px                |
|            |                   | `3` 22px                |
|            |                   | `4` 28px                |
|            |                   | `5` 36px                |
|            |                   | `6` 46px                |
|            |                   | `7` 58px                |
|            |                   | `8` 72px                |
|            |                   | `l` left align          |
|            |                   | `c` centre align        |
|            |                   | `r` right align         |
|            |                   | `j` justify             |
|            |                   | `jc` justify centre     |
|            |                   | `nbr` prevent wrapping  |
|            |                   | `trn` truncate overflow |
