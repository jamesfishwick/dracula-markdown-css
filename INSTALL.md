# Dracula for Markdown CSS

## Install

### Option 1: Download

1. Download [`dracula-markdown.css`](./dracula-markdown.css)
2. Include it in your HTML:

```html
<link rel="stylesheet" href="dracula-markdown.css">
```

### Option 2: CDN (after official release)

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/dracula/markdown-css/dracula-markdown.css">
```

### Option 3: npm (after official release)

```bash
npm install dracula-markdown-css
```

```javascript
import 'dracula-markdown-css/dracula-markdown.css';
```

## Usage

### Basic Usage

The stylesheet applies directly to standard HTML elements. Just wrap your markdown-rendered content and include the CSS:

```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="dracula-markdown.css">
</head>
<body>
    <h1>My Markdown Content</h1>
    <p>This will be styled with Dracula colors.</p>
</body>
</html>
```

### With a Container Class

If you only want Dracula styling on specific content, use the `.dracula-markdown` wrapper class:

```html
<link rel="stylesheet" href="dracula-markdown-scoped.css">

<div class="dracula-markdown">
    <!-- Your markdown content here -->
</div>
```

## Included Files

| File | Description |
|------|-------------|
| `dracula-markdown.css` | Styles applied directly to HTML elements (body, h1, p, etc.) |
| `dracula-markdown-scoped.css` | Styles scoped to `.dracula-markdown` container class |

## Color Palette

This theme uses the official [Dracula color palette](https://spec.draculatheme.com/):

| Element | Color | Hex |
|---------|-------|-----|
| Background | Background | `#282A36` |
| Text | Foreground | `#F8F8F2` |
| Headings | Purple | `#BD93F9` |
| Links | Cyan | `#8BE9FD` |
| Code | Green | `#50FA7B` |
| Bold | Orange | `#FFB86C` |
| Italic | Yellow | `#F1FA8C` |
| Blockquotes | Comment | `#6272A4` |
| List markers | Pink | `#FF79C6` |
