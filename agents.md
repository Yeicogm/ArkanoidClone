# AGENTS.md

Simple HTML game project (Arkanoid clone). Single-file: `arkanoid.html`

## Project

- **Type**: Browser game (HTML/CSS/JS canvas)
- **Run**: Open `arkanoid.html` in any browser
- **Test**: Manual playtesting

## Key Commands

- No build system required
- No tests (manual verification only)

## Important Context

- Uses Web Audio API — sounds initialize on first user interaction (button click)
- Keyboard controls: Arrow keys (move), Space (launch ball)
- Previously improved with accessibility (skip link, aria-live, focus-visible, reduced-motion) and SEO (meta description)

## Skills Available

`.agents/skills/` contains installed skills from `autoskills`:
- `accessibility/` — WCAG guidelines
- `seo/` — search optimization
- `frontend-design/` — UI aesthetics

## Development Notes

- Font (Orbitron) loaded from Google Fonts — includes `preconnect` hints
- Game state updates use `aria-live` for screen reader feedback
- `prefers-reduced-motion` media query respected in CSS