# Animated Banner Assets

This directory contains animated SVG banners for the GitHub profile README. These banners feature TV-style motion effects that display skills dynamically.

## Features

Each banner includes:
- **Animated gradient backgrounds** that cycle through colors continuously
- **Moving scan lines** creating a classic TV/CRT screen effect
- **Bouncing skill icons** with staggered animations
- **Pulsing text effects** for emphasis
- **Floating particles** for added visual interest
- **Dark/Light theme variants** that adapt to user preferences

## Banner Files

### Full Stack Developer Banner
- `fullstack-light.svg` - Light theme variant with purple gradient
- `fullstack-dark.svg` - Dark theme variant with blue gradient
- Showcases: React, Node.js, Python, Django, MongoDB

### Data Scientist Banner
- `datascience-light.svg` - Light theme variant with pink-orange gradient
- `datascience-dark.svg` - Dark theme variant with purple gradient
- Features: Animated bar chart, TensorFlow, Python, Jupyter

### Hire Me Banner
- `hireme-light.svg` - Light theme variant with green gradient
- `hireme-dark.svg` - Dark theme variant with teal gradient
- Displays: Contact information with pulsing effects

## Technical Details

All SVG files use:
- Native SVG animations (SMIL animations)
- No external dependencies
- Compatible with all modern browsers
- Automatically loop indefinitely
- Lightweight file size (~3-4KB each)

## Usage in README

The banners are displayed using the `<picture>` element for responsive theme switching:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="path/to/dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="path/to/light.svg">
  <img alt="Description" src="path/to/light.svg">
</picture>
```

This ensures users see the appropriate theme variant based on their system preferences.
