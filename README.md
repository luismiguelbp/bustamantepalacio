# Bustamante Palacio Website

Personal website of the Bustamante Palacio brothers with a distinctive dark theme aesthetic.

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
- **Primary**: `#0f172a` (Deep navy)
- **Secondary**: `#1e3a5f` (Ocean blue)
- **Accent**: `#f97316` (Warm orange)
- **Highlight**: `#06b6d4` (Cyan)
- **Text**: `#e2e8f0` (Light gray)

### Typography
- **Display**: Playfair Display (Google Fonts)
- **Body**: DM Sans (Google Fonts)
- **Monospace**: JetBrains Mono (Google Fonts)

## Features

- LinkedIn profile badges integration
- Contact information via email
- Social media links (Twitter/X, GitHub, LinkedIn)
- Animated hero section with gradient backgrounds
- Responsive footer with contact details

## File Structure

```
bustamantepalacio/
├── index.html          # Main homepage (semantic HTML5)
├── assets/
│   └── css/
│       └── style.css   # Custom styles with CSS variables
├── favicon.ico
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

## Setup

Simply open `index.html` in a web browser. No build process required.
