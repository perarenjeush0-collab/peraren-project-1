# Jeush Daniel Peraren Portfolio — Implementation Plan

## Scope

Build a responsive personal portfolio website for Jeush Daniel Peraren, a second-year college student at Kabankalan Catholic College (KCC). The site introduces his coding, programming, and layouting interests; shares his hobbies—basketball, movies, and motor rides; and provides a GitHub Pages-ready static source structure.

## Project structure

- `index.html` — semantic single-page portfolio markup, navigation, sections, and accessible labels.
- `styles/main.css` — all visual styling, responsive layout rules, states, and motion preferences.
- `assets/avatar-mark.svg` — lightweight profile mark used in the hero and footer.
- `manus-routes.json` — route manifest for the home page.
- `README.md` — setup, customization, GitHub Pages, and commit-history notes.

## Design direction

Three possible directions were considered:

1. **Campus Blueprint** — structured academic portfolio with blue accents and diagram-like labels. Probability: 0.07.
2. **Courtside Code** — energetic basketball-poster developer identity with bold contrast. Probability: 0.04.
3. **Night Ride Journal** — cinematic portfolio inspired by movies and evening rides. Probability: 0.03.

### Selected: Campus Blueprint, adapted to blue and white

- **Design movement:** editorial student notebook meets technical blueprint.
- **Core principles:** clear hierarchy, confident spacing, useful labels, and a calm academic tone.
- **Color philosophy:** deep blue establishes trust and focus; lighter blue fields create depth; white space keeps the student story readable and approachable.
- **Layout paradigm:** an offset editorial composition with a fixed-feeling rail, numbered sections, and asymmetric cards rather than a generic centered grid.
- **Signature elements:** blueprint corner marks, section index labels, and thin ruled lines.
- **Interaction philosophy:** links and cards respond with small, precise shifts that feel like navigating a well-organized notebook.
- **Animation:** restrained rise-and-fade on load, underline and border transitions on interaction, and reduced motion for accessibility.
- **Typography system:** Space Grotesk for display and UI text, IBM Plex Mono for labels and metadata, with system fallbacks for reliable GitHub Pages rendering.
- **Brand essence:** a focused student portfolio that turns curiosity in code and design into visible progress. Personality: curious, disciplined, active.
- **Brand voice:** direct, optimistic, and personal. Example lines: “Learning by building, one layout at a time.” and “Here’s what I’m exploring next.”
- **Wordmark and logo:** a compact `JDP` monogram inside a blueprint-style rounded square.
- **Signature brand color:** `#1257A6`, a strong academic blue used for primary actions and key highlights.

## Implementation notes

Use only static HTML and CSS so the project can be opened locally and deployed directly with GitHub Pages. Keep all paths relative, include alt text and visible focus styles, and make the navigation usable on narrow screens without JavaScript.
