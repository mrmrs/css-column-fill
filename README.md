# css-column-fill

Functional CSS for column-fill

## Filesize

| File | Size |
|------|------|
| `dist/column-fill.css` | 762 bytes |
| `dist/column-fill.min.css` | 586 bytes (152 Gzipped) |

## Install

```sh
npm install css-column-fill
```

## Usage

### Import

```css
@import "css-column-fill";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-column-fill/dist/column-fill.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-column-fill/dist/column-fill.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.column-fill-auto` | `column-fill: auto;` |
| `.column-fill-balance` | `column-fill: balance;` |
| `.column-fill-inherit` | `column-fill: inherit;` |
| `.column-fill-auto-s` | `column-fill: auto;` |
| `.column-fill-balance-s` | `column-fill: balance;` |
| `.column-fill-inherit-s` | `column-fill: inherit;` |
| `.column-fill-auto-m` | `column-fill: auto;` |
| `.column-fill-balance-m` | `column-fill: balance;` |
| `.column-fill-inherit-m` | `column-fill: inherit;` |
| `.column-fill-auto-l` | `column-fill: auto;` |
| `.column-fill-balance-l` | `column-fill: balance;` |
| `.column-fill-inhherit-l` | `column-fill: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.column-fill-auto-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/column-fill.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/column-fill.css` — formatted
- `dist/column-fill.min.css` — minified

## License

MIT
