# Bustamante Palacio Website

Personal website of the Bustamante Palacio brothers with a distinctive dark theme aesthetic.

🌐 **Live Sites:**
- **Production:** [bustamantepalacio.info](https://www.bustamantepalacio.info)
- **GitHub Pages:** [luismiguelbp.github.io/bustamantepalacio](https://luismiguelbp.github.io/bustamantepalacio)

## Overview

- **Bootstrap 5.3.8**: Latest Bootstrap framework from CDN
- **Bootstrap Icons**: Modern icon library
- **Custom Dark Theme**: Deep ocean gradient with warm orange accents
- **Distinctive Typography**: Playfair Display (headings) + DM Sans (body) + JetBrains Mono (code)
- **Smooth Animations**: CSS-only animations with `prefers-reduced-motion` support
- **Fully Responsive**: Mobile-first design with fluid typography
- **Accessibility First**: ARIA labels, semantic HTML, keyboard navigation support

## Design System

### Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Primary | `#0f172a` | Deep navy background |
| Secondary | `#1e3a5f` | Ocean blue gradients |
| Accent | `#f97316` | Warm orange highlights |
| Highlight | `#06b6d4` | Cyan accents |
| Text | `#e2e8f0` | Light gray text |

### Typography

- **Display**: Playfair Display (Google Fonts)
- **Body**: DM Sans (Google Fonts)
- **Monospace**: JetBrains Mono (Google Fonts)

## Features

- LinkedIn profile badges integration
- Contact information via email
- Social media links (Twitter/X, GitHub, LinkedIn, GitHub Pages)
- Animated hero section with gradient backgrounds
- Responsive footer with contact details

## File Structure

```
├── index.html          # Main homepage (semantic HTML5)
├── assets/
│   ├── css/style.css   # Custom styles with CSS variables
│   ├── fonts/          # Local fonts
│   ├── img/            # Images
│   └── js/             # Custom scripts
├── favicon.ico
├── AGENTS.md           # Agent instructions
├── .gitignore          # Git ignore rules
├── .cursorignore       # Cursor Agent exclusions
├── .nojekyll           # Disable Jekyll processing
└── README.md
```

## Dependencies (all from CDN)

- **Bootstrap 5.3.8**: CSS framework
- **Bootstrap Icons 1.11.3**: Icon library
- **Google Fonts**: Playfair Display, DM Sans, JetBrains Mono
- **LinkedIn Badges**: External script

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Accessibility Features

- Semantic HTML5 structure (`header`, `section`, `footer`, `nav`)
- ARIA labels for interactive elements
- Screen reader-only text (`.sr-only` class)
- `prefers-reduced-motion` media query support
- Focus indicators for keyboard navigation
- Proper heading hierarchy

## Requirements

- A modern browser (Chrome, Firefox, Safari, or Edge latest)
- No runtime, build tools, or package installation required

## Setup

1. Clone the repository.
2. No dependencies to install; third-party libraries load from CDN at runtime.

## Usage

Open `index.html` in a web browser. No build process required.

## Verification

- Manual: open `index.html` and check hero, links, responsive layout, and keyboard navigation.
- No test, lint, or build commands apply to this static site.

## Deployment

### GitHub Pages

This site is configured for GitHub Pages deployment:

1. Push to the `main` branch
2. Enable GitHub Pages in repository Settings → Pages
3. Select source: `main` branch, `/ (root)` folder

The `.nojekyll` file ensures faster deployment by skipping Jekyll processing.

## Documentation

- [Agent instructions](AGENTS.md)

## License

© Bustamante Palacio
