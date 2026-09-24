# AGENTS.md

Guidance for coding agents working in this repository. See [docs/PRD.md](docs/PRD.md) and [docs/PROPOSAL.md](docs/PROPOSAL.md) for full details.

## Project

Alice Zhu's personal website — a single-page site meant to introduce her as a person (background, interests, photos), not a resume or portfolio. Audience: friends, classmates, professors, future acquaintances.

## Tech Stack

- Plain HTML, CSS, and vanilla JavaScript only. No frameworks, build tools, or package managers.
- Single page: [index.html](index.html). Images live in [assets/](assets/).

## Page Structure (in order)

1. Header/nav (not fixed on scroll) — links: About Me, My Story, What I Love, Gallery
2. Hero — large personal photo, name "Alice Zhu", tagline "Business Student & Student-Athlete"
3. About Me — name, hometown (Beijing), major (Business), student-athlete identity, short casual intro + tag chips (`Business Student`, `Student-Athlete`, `Beijing`)
4. My Story — narrative order: early background → moving to the US → current college/student-athlete life, with a casual photo alongside
5. What I Love — three interests: Golf, Business, Baking; visual-first, minimal text; use real photos for Golf/Baking, a fitting stock-style image for Business
6. Gallery — carousel/slideshow with left/right controls (not a grid)
7. Footer — simple only, e.g. `© 2026 Alice Zhu`; no CTA or contact section

## Design Guidelines

- Palette: light blue (main accent), cream/beige, white. Soft, warm, airy — not corporate.
- Typography: elegant display font for headings, simple readable font for body/nav.
- Generous white space; short paragraphs; photos carry more weight than text.
- Animations should be subtle only: fade-ins on scroll, small hover effects, smooth scroll, simple carousel transitions. Never flashy or distracting.

## Content Tone

Casual and friendly, like a personal introduction — not a professional bio. Keep text short; let photos do the storytelling.

## Avoid

- Long blocks of text or resume-style sections
- Corporate/overly professional visual design
- Bright/aggressive colors or crowded layouts
- Excessive or complex animations

## Accessibility & Responsiveness

- Alt text on all meaningful images.
- Sufficient text/background contrast.
- Nav and carousel controls must be easy to click/tap and understand.
- Layout must adapt cleanly to mobile while keeping the same soft visual style.
