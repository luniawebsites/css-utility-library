# CSS Utility Library

A set of CSS utilities with a simple syntax for fast website design.

HTML attributes (instead of classes) are used to style elements. This is done so that separate, custom styles can be created as classes and kept separate from utilities. This also allows custom styles to take priority over utilities because classes have a higher specificity than attributes.

Syntax examples:

```html
<p data-util="txt:sm:blu">Hello!</p>
```

```html
<span data-util="bgd:md.:blu"></span>
```

```html
<div data-util="row:sm:cc"></div>
```

## Media Queries

The library is based on a mobile-first responsive and adaptive design strategy. All styles are grouped into media queries and divided into separate stylesheets. This lets you adopt a CSS loading strategy in your HTML page that reduces page loading time based on the user's viewport.

Five media queries are used for responsive and adaptive design:

- `sm` small
- `sm.` small only
- `md` medium
- `md.` medium only
- `lg` large

One media query is used for pseudo-classes:

- `hv` (hover)

## Syntax

All utility names are composed of three syntax shorthand groups separated by colons.

> `target : viewport/state : value`

**Target** is the name of the category you are styling, which can be anything from the text inside an element to the element's display type or padding. **Viewport/State** selects a media query. **Value** applies the style option.

> `txt:sm:blu`

This is a cascading utility used for a responsive design strategy. The viewport/state ends in `sm`, so the style will take effect in the small viewport and cascade upwards to bigger viewports (until the utility is overridden by a utility in one of these bigger viewports).

> `txt:sm.:blu`

This is a non-cascading utility used for an adaptive design strategy. This is the same as above, except that the viewport/state ends in a full stop which means it is confined to its own viewport. This is useful when you need to apply a style to a specific viewport only, without affecting any others.

> `txt:hv:red` instructs an HTML element to colour its contained text red when the element is hovered over.
>
> `grd:md.:300` instructs an HTML element to apply a grid layout with 300px wide columns at the medium viewport only.
>
> `pad:sm:0,25` instructs an HTML element to apply 1/4 em padding starting at the small viewport.


## Syntax Guides

Each target (category) has a reference guide in the **syntax guides** folder.

- Background colours
- Border colours
- Border radii
- Buttons
- Display
- Flexbox
- Gaps
- Grid
- Gutters
- Heights
- Margins
- Outlines
- Padding
- Shadows
- Text formats
- Text structure
- Widths

## Author

Contact me with any issues or questions at info@lunia.co.za.
