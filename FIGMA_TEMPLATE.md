# Viso Design System - Figma Template Guide

This guide provides specifications for recreating the Viso Design System in Figma.

## Color Palette

### Primary Backgrounds
| Name | Hex | Usage |
|------|-----|-------|
| bg-primary | #0d1117 | Page background, deepest layer |
| bg-secondary | #161b22 | Card backgrounds, surfaces |
| bg-tertiary | #21262d | Elevated elements, hover states |

### Accent Colors
| Name | Hex | Usage |
|------|-----|-------|
| accent | #3ddc84 | Primary accent, buttons, links |
| accent-dim | #2ea043 | Hover/active states |
| accent-glow | rgba(61, 220, 132, 0.4) | Glow effects, shadows |

### Semantic Colors
| Name | Hex | Usage |
|------|-----|-------|
| gold | #ffd700 | Success states, premium |
| red | #f85149 | Errors, destructive actions |
| orange | #ff9800 | Warnings, offline indicators |

### Text Colors
| Name | Hex | Usage |
|------|-----|-------|
| text-primary | #f0f6fc | Headings, primary text |
| text-secondary | #8b949e | Body text, descriptions |
| text-muted | #6e7681 | Disabled states, placeholders |

### Glassmorphism Colors
| Name | Value | Usage |
|------|-------|-------|
| glass-bg | rgba(13, 17, 23, 0.75) | Glass surface background |
| glass-border | rgba(48, 54, 61, 0.6) | Glass borders |

## Typography

### Font Family
- **Primary**: Inter (or system sans-serif)
- **Monospace**: JetBrains Mono (or system monospace)

### Type Scale

| Style | Size | Weight | Line Height | Letter Spacing | Usage |
|-------|------|--------|-------------|----------------|-------|
| H1 | 48px | 700 | 1.1 | -0.02em | Page titles |
| H2 | 36px | 700 | 1.2 | -0.01em | Section headers |
| H3 | 28px | 600 | 1.3 | 0 | Subsection headers |
| H4 | 22px | 600 | 1.4 | 0 | Card titles |
| H5 | 18px | 600 | 1.4 | 0 | Small headers |
| H6 | 14px | 600 | 1.4 | 0.05em | Labels, uppercase |
| Body Large | 18px | 400 | 1.6 | 0 | Lead paragraphs |
| Body | 16px | 400 | 1.6 | 0 | Standard text |
| Body Small | 14px | 400 | 1.5 | 0 | Secondary text |
| Caption | 12px | 500 | 1.4 | 0.05em | Tags, metadata |

## Spacing Scale

| Token | Value | Usage |
|-------|-------|-------|
| space-0 | 0px | None |
| space-1 | 4px | Tight gaps |
| space-2 | 8px | Small gaps |
| space-3 | 12px | Medium gaps |
| space-4 | 16px | Standard gaps |
| space-5 | 24px | Large gaps |
| space-6 | 32px | Section spacing |
| space-8 | 48px | Major sections |
| space-10 | 64px | Page sections |

## Border Radius

| Token | Value | Usage |
|-------|-------|-------|
| radius-sm | 4px | Small elements |
| radius-md | 8px | Inputs, buttons |
| radius-lg | 12px | Cards |
| radius-xl | 16px | Large cards |
| radius-full | 9999px | Pills, badges |

## Shadows & Effects

### Glassmorphism Effect
- Background: rgba(13, 17, 23, 0.75)
- Background Blur: 12px
- Border: 1px solid rgba(48, 54, 61, 0.6)
- Border Radius: 12px

### Glow Effect
- Box Shadow: 0 0 20px rgba(61, 220, 132, 0.4)
- Use with accent color elements

### Elevation Shadows
| Level | Shadow |
|-------|--------|
| sm | 0 1px 2px rgba(0, 0, 0, 0.3) |
| md | 0 4px 6px rgba(0, 0, 0, 0.4) |
| lg | 0 10px 15px rgba(0, 0, 0, 0.5) |

## Components

### Buttons

#### Default Button
- Height: 40px
- Padding: 0 16px
- Background: #21262d
- Border: 1px solid #30363d
- Border Radius: 8px
- Text: #f0f6fc, 14px, weight 500
- Hover: border-color #3ddc84

#### Primary Button
- Height: 40px
- Padding: 0 16px
- Background: #3ddc84
- Border: none
- Border Radius: 8px
- Text: #0d1117, 14px, weight 600
- Hover: background #2ea043

#### Ghost Button
- Height: 40px
- Padding: 0 16px
- Background: transparent
- Border: 1px solid rgba(48, 54, 61, 0.6)
- Border Radius: 8px
- Text: #f0f6fc, 14px, weight 500
- Hover: background rgba(61, 220, 132, 0.1)

#### Gold Button
- Height: 40px
- Padding: 0 16px
- Background: rgba(255, 215, 0, 0.15)
- Border: 1px solid rgba(255, 215, 0, 0.5)
- Border Radius: 8px
- Text: #ffd700, 14px, weight 600
- Hover: background rgba(255, 215, 0, 0.25)

### Inputs

#### Text Input
- Height: 40px
- Padding: 0 12px
- Background: #0d1117
- Border: 1px solid #21262d
- Border Radius: 8px
- Text: #f0f6fc, 16px
- Placeholder: #6e7681
- Focus: border-color #3ddc84

#### Text Area
- Min Height: 100px
- Padding: 12px
- Background: #0d1117
- Border: 1px solid #21262d
- Border Radius: 8px
- Text: #f0f6fc, 16px

### Cards

#### Standard Card
- Background: #161b22
- Border: 1px solid rgba(48, 54, 61, 0.6)
- Border Radius: 12px
- Padding: 24px

#### Glass Card
- Background: rgba(13, 17, 23, 0.75)
- Background Blur: 12px
- Border: 1px solid rgba(48, 54, 61, 0.6)
- Border Radius: 12px
- Padding: 24px

#### Gold Card
- Background: rgba(22, 27, 34, 0.9)
- Border: 1px solid rgba(255, 215, 0, 0.3)
- Border Radius: 12px
- Padding: 24px
- Optional: Left border 3px solid #ffd700

### Badges

#### Default Badge
- Padding: 4px 12px
- Background: rgba(110, 118, 129, 0.4)
- Border Radius: 9999px
- Text: #f0f6fc, 12px, weight 500

#### Accent Badge
- Padding: 4px 12px
- Background: rgba(61, 220, 132, 0.2)
- Border Radius: 9999px
- Text: #3ddc84, 12px, weight 500

#### Gold Badge
- Padding: 4px 12px
- Background: rgba(255, 215, 0, 0.2)
- Border Radius: 9999px
- Text: #ffd700, 12px, weight 500

## Layout Grid

### Container
- Max Width: 1200px
- Padding: 16px (mobile) / 24px (tablet) / 48px (desktop)

### Grid System
- Columns: 12
- Gutter: 24px
- Margin: 16px (mobile) / 24px (tablet) / 48px (desktop)

## Figma Setup Checklist

- [ ] Create Color Styles for all palette colors
- [ ] Create Text Styles for all typography variants
- [ ] Create Effect Styles for shadows and glows
- [ ] Create Grid Styles for layout
- [ ] Build Button component variants (Default, Primary, Ghost, Gold)
- [ ] Build Input component variants (Text, Text Area)
- [ ] Build Card component variants (Standard, Glass, Gold)
- [ ] Build Badge component variants (Default, Accent, Gold)
- [ ] Create spacing tokens as variables
- [ ] Create border radius tokens as variables
- [ ] Build sample page layouts

---

**AI Disclaimer**: This Figma template guide was created with the assistance of AI tools. Measurements and specifications should be verified against the actual CSS implementation.
