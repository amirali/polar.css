# polar.css

A tiny classless CSS theme inspired by [MVP.css](https://andybrewer.github.io/mvp/) and [Water.css](https://watercss.kognise.dev/), with light and dark palettes based on the Nord color family.

## What it is

- Classless styling for semantic HTML
- Nord-inspired light and dark themes
- Automatic dark mode with `prefers-color-scheme`
- Optional manual override with `data-theme="light"` or `data-theme="dark"`
- Optional inline layouts with grid or flex helpers
- Styled typography, navigation, cards, forms, tables, code blocks, and details

## Usage

Local file:

```html
<link rel="stylesheet" href="polar.css" />
```

Remote (via GitHub raw):

```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/amirali/polar.css/main/polar.css" />
```

Follow system theme automatically:

```html
<html lang="en">
```

Force a theme manually:

```html
<html lang="en" data-theme="light"></html>
```

```html
<html lang="en" data-theme="dark"></html>
```

## Files

- `polar.css` — main stylesheet
- `index.html` — demo page

## Inline layouts

Use opt-in helpers when fields or components should sit on one line or wrap into columns.

```html
<div data-layout="grid">
  <div data-field>
    <label for="name">Name</label>
    <input id="name" type="text" />
  </div>

  <div data-field>
    <label for="email">Email</label>
    <input id="email" type="email" />
  </div>
</div>
```

```html
<div data-layout="flex">
  <div data-field>
    <label for="city">City</label>
    <input id="city" type="text" />
  </div>

  <div data-actions>
    <button type="submit">Save</button>
    <button type="reset">Reset</button>
  </div>
</div>
```

You can also use the equivalent helper classes:

- `.inline-grid`
- `.inline-flex`
- `.field`
- `.actions`

## Design goals

- Feel polished on unclassed HTML
- Stay minimal and readable
- Use a softer Nord palette instead of harsh pure black and white
- Work well for landing pages, docs, small apps, and prototypes
