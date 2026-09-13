# Bustamante Palacio Website

- Read the [README](README.md) for setup, layout, and conventions.
- Discover skills under [`.agents/skills/`](.agents/skills/) and read the matching `SKILL.md` when the task fits. Do not load unused skills.

## Engineering Principles

- **KISS — Keep It Simple:** choose the simplest solution that meets the requirements.
- **LEAN:** minimize waste—code, dependencies, steps, and work that add no value.
- **YAGNI — You Aren’t Gonna Need It:** don’t implement features or abstractions until they’re actually needed.
- **DRY — Don’t Repeat Yourself:** keep a single source of truth; link instead of copying.

## Project Constraints

- Static site: `index.html` plus `assets/`. No build step, no bundler, no vendored CDN code.
- Keep design tokens (colors, fonts) in `assets/css/style.css`; Bootstrap and fonts stay on CDN.
- Preserve semantic HTML5, ARIA labels, heading hierarchy, and `prefers-reduced-motion` support.
- GitHub Pages deploys from `main` root; keep `.nojekyll`.

## Verification

- Open `index.html` in a browser; no build or test command applies.
