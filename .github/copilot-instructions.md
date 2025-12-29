# Copilot Instructions for CursorHaloOS

This document provides instructions for GitHub Copilot when working on this repository.

## Project Overview

CursorHaloOS is a landing page for "Cursor Halo" - a context-aware AI assistant for macOS that appears as a floating widget next to the user's mouse cursor.

## Repository Structure

- `index.html` - The main landing page (static HTML with embedded CSS)

## Technology Stack

- **HTML5** with semantic markup
- **CSS3** with modern features:
  - CSS Custom Properties (variables)
  - CSS Grid and Flexbox
  - CSS Animations and Keyframes
  - Glassmorphism effects (backdrop-filter, blur)
  - Responsive design

## Code Style Guidelines

### HTML
- Use semantic HTML5 elements
- Include appropriate accessibility attributes
- Use meaningful class names following a BEM-like convention
- Keep the structure clean and well-indented

### CSS
- Use CSS custom properties defined in `:root` for colors and common values
- Follow the existing naming conventions (e.g., `--bg-dark`, `--accent-cyan`)
- Use relative units (rem, em, %) for responsive design
- Group related styles together with section comments
- Maintain existing animation naming patterns (e.g., `cursorMove`, `haloAppear`)

### Responsive Design
- Mobile-first approach is preferred
- Use media queries for responsive breakpoints as defined in the CSS
- Ensure all interactive elements are touch-friendly

## Design System

### Color Palette
- Background: `#050507` (dark)
- Accent Cyan: `#00f2ea`
- Accent Purple: `#ff00ff`
- Text Main: `#ffffff`
- Text Muted: `rgba(255, 255, 255, 0.6)`

### Typography
- Primary Font: Inter (Google Fonts)
- Monospace Font: JetBrains Mono (for code elements)

## Best Practices

1. **Performance**: Minimize DOM operations and prefer CSS animations over JavaScript
2. **Accessibility**: Ensure proper color contrast and keyboard navigation
3. **Maintainability**: Keep the single-file structure clean with well-organized sections
4. **Browser Support**: Target modern browsers that support CSS Grid, Flexbox, and backdrop-filter

## Testing

Since this is a static HTML page, testing should include:
- Visual verification in multiple browsers
- Responsive design testing at various viewport sizes
- Animation performance testing

## Making Changes

When modifying this repository:
1. Preserve the existing visual design language
2. Maintain consistency with the glassmorphism aesthetic
3. Test all animations to ensure smooth 60fps performance
4. Verify responsive behavior across device sizes
