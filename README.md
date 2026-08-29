# polar.css

A tiny classless CSS theme inspired by [MVP.css](https://andybrewer.github.io/mvp/) and [Water.css](https://watercss.kognise.dev/), with light and dark palettes based on the Nord color family.

## What it is

- Classless styling for semantic HTML
- Nord-inspired light and dark themes
- Automatic dark mode with `prefers-color-scheme`
- Optional manual override with `data-theme="light"` or `data-theme="dark"`
- Styled typography, navigation, cards, forms, tables, code blocks, and details

## Usage

```html
<link rel="stylesheet" href="polar.css" />
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

## Design goals

- Feel polished on unclassed HTML
- Stay minimal and readable
- Use a softer Nord palette instead of harsh pure black and white
- Work well for landing pages, docs, small apps, and prototypes
