
![enter image description here](https://github.com/SuperYosh23/VisoDesign/blob/main/LogoFullWhiteTip.png?raw=true)

An open-source dark theme design language featuring glassmorphism effects and vibrant green accents. Viso provides a complete set of CSS variables, components, and utilities for building modern, visually striking web interfaces.

## Features

- **Dark Theme**: Deep space-inspired color palette with high contrast text
- **Glassmorphism**: Frosted glass effects with backdrop blur and translucent surfaces
- **Vibrant Accents**: Green accent colors with glow effects
- **Semantic Colors**: Built-in success, error, and warning states
- **Typography Scale**: Consistent heading and body text hierarchies
- **Component Library**: Pre-styled buttons, inputs, cards, and more
- **Utility Classes**: Flexbox, grid, spacing, and layout utilities
- **Responsive Ready**: Mobile-first design patterns

## Quick Start

Include the CSS file in your HTML:

```html
<link rel="stylesheet" href="viso.css">
```

Add the theme attribute to your HTML tag:

```html
<html data-theme="viso">
```

Or to the body:

```html
<body data-theme="viso">
```

## Design Tokens

Viso is built on CSS custom properties that can be customized:

### Colors

| Token | Value | Usage |
|-------|-------|-------|
| `--viso-bg-primary` | `#0d1117` | Page background |
| `--viso-bg-secondary` | `#161b22` | Card/surface backgrounds |
| `--viso-bg-tertiary` | `#21262d` | Elevated elements |
| `--viso-accent` | `#3ddc84` | Primary accent color |
| `--viso-accent-dim` | `#2ea043` | Hover/active states |
| `--viso-gold` | `#ffd700` | Success states |
| `--viso-red` | `#f85149` | Error states |
| `--viso-orange` | `#ff9800` | Warning states |

### Typography

| Token | Value | Usage |
|-------|-------|-------|
| `--viso-text-primary` | `#f0f6fc` | Headings, primary text |
| `--viso-text-secondary` | `#8b949e` | Body text |
| `--viso-text-muted` | `#6e7681` | Disabled, placeholders |

### Effects

| Token | Value | Usage |
|-------|-------|-------|
| `--glass-bg` | `rgba(13, 17, 23, 0.75)` | Glassmorphism background |
| `--glass-border` | `rgba(48, 54, 61, 0.6)` | Glass borders |
| `--viso-accent-glow` | `rgba(61, 220, 132, 0.4)` | Accent glow effects |

## Components

### Buttons

```html
<button class="viso-button">Default Button</button>
<button class="viso-button viso-button-primary">Primary Button</button>
<button class="viso-button viso-button-ghost">Ghost Button</button>
<button class="viso-button viso-button-gold">Gold Button</button>
```

### Inputs

```html
<input type="text" class="viso-input" placeholder="Enter text...">
<textarea class="viso-input" rows="4" placeholder="Enter message..."></textarea>
```

### Cards

```html
<div class="viso-card">Card content</div>
<div class="viso-card-glass">Glass card content</div>
<div class="viso-card-gold">Gold accent card</div>
```

### Layout

```html
<!-- Container -->
<div class="viso-container">Centered content</div>

<!-- Flex utilities -->
<div class="viso-flex viso-items-center viso-gap-4">
  <span>Item 1</span>
  <span>Item 2</span>
</div>

<!-- Grid utilities -->
<div class="viso-grid viso-grid-cols-3">
  <div>Column 1</div>
  <div>Column 2</div>
  <div>Column 3</div>
</div>
```

## Typography Classes

- `viso-h1` through `viso-h6` - Heading styles
- `viso-text-sm`, `viso-text-base`, `viso-text-lg` - Text sizes
- `viso-text-secondary`, `viso-text-muted` - Text color variants
- `viso-font-mono` - Monospace text

## Spacing Utilities

Spacing classes follow the pattern `viso-{property}-{size}`:

- **Property**: `p` (padding), `m` (margin), `gap`
- **Size**: `0`, `1` (4px), `2` (8px), `3` (12px), `4` (16px), `5` (24px), `6` (32px)

Examples:

```html
<div class="viso-p-4">16px padding</div>
<div class="viso-m-2">8px margin</div>
<div class="viso-gap-3">12px gap</div>
```

## Example

Open `example-viso.html` in your browser to see a complete demonstration of all components and styles.

## Browser Support

Viso uses modern CSS features including:
- CSS Custom Properties (variables)
- Backdrop filter (glassmorphism)
- Grid and Flexbox layouts

Compatible with all modern browsers (Chrome, Firefox, Safari, Edge).

## Contributing

Contributions are welcome. Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

**AI Disclaimer**: This project and its documentation were created with the assistance of AI tools. While every effort has been made to ensure accuracy and quality, users are encouraged to review and test thoroughly before production use.
