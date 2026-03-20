# Repository Guidelines

## Project Scope
This repository is a personal one-page resume website for GitHub Pages. Keep it static and production-ready. Use only HTML, CSS, and a small amount of vanilla JavaScript. Do not add frameworks, package managers, build tools, preprocessors, or third-party UI libraries.

## Repository Structure
The site lives in the repository root:
- `index.html` - main page content
- `styles.css` - all styling and responsive rules
- `main.js` - minimal progressive enhancement only
- `README.md` - local preview and deployment notes

If assets are added later, place them under `assets/`. Keep the structure flat and obvious.

## Design and Content Direction
The design must remain minimal, clean, and professional, with an engineering-oriented tone suitable for German research and industry contexts. Prioritize readable typography, clear spacing, restrained color use, and straightforward hierarchy. Avoid flashy animations, decorative effects, and novelty interactions.

Content should present a profile centered on Mechatronics Engineering, applied machine learning, sensor data, industrial systems, and engineering analytics. Keep all claims factual and technically credible.

## Coding Rules
Use semantic HTML and simple, readable structure. Avoid unnecessary wrappers and abstractions. Keep CSS organized by page section and use reusable class names. JavaScript must enhance navigation or minor interactions only; core content must work without JavaScript.

Do not introduce external runtime dependencies. Prefer system fonts over remote font services. Keep the site fully compatible with GitHub Pages as plain static files.

## Accessibility and Responsiveness
Every change must preserve keyboard accessibility, visible focus states, sufficient contrast, sensible heading order, and mobile readability. Do not rely on hover-only behavior or JavaScript for essential navigation.

## Deployment Notes
The site should be deployable by pushing the root files to GitHub and enabling Pages from the default branch root. A `.nojekyll` file is not required unless underscore-prefixed paths are introduced later.

## Content Hygiene
Before publishing, replace all placeholders in `index.html`, especially name, email, profile links, employer wording, university wording, and project details. Do not deploy sample contact information.

## Commit Guidelines
Use concise Conventional Commit messages such as `feat: add publications section` or `fix: improve mobile navigation`. Keep commits focused and avoid mixing unrelated design, content, and structural changes.
