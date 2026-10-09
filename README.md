# WDD 331R Portfolio

**Student:** Ammon Johnson\
**Semester:** Fall Semester, 2026\
**Live Site:** [View Site](https://ammon-j.github.io/Portfolio-WDD331R/)

## About

This repository is my portfolio for WDD 331R: Advanced CSS.
Each week I add new pages and styles as I work through the course
assignments. The site deploys automatically to GitHub Pages on
every push to main.

## CSS Architecture

This project uses a layered CSS architecture. The source files are organized in the `css/` directory and imported into `main.css` using the `@layer` rule. 

* `tokens/`: Global design variables (colors, spacing, typography, etc.).
* `base/`: Resets and element-level base styles.
* `layout/`: Macro page structures and grids.
* `components/`: Modular, reusable UI chunks (e.g., site navigation, cards).
* `utilities/`: Single-purpose utility classes.

## Build Tool & Local Development

This project uses **Lightning CSS** to bundle and minify the CSS, paired with `live-server` for a seamless local development environment.

### How to run the project locally
1. Install the required dependencies: `npm install`
2. Run the development server and CSS watcher: `npm run dev`
   *(This starts a local server and automatically rebuilds the CSS and refreshes the browser whenever you save a file.)*
3. To manually build the production file without starting a server: `npm run build`

The bundled and minified CSS output is generated at `dist/styles.css`.

## Pages

- [Home](index.html)
- [Custom Properties and Nesting](unit-1/custom-properties/index.html)
- [Layered Components](unit-2/layered-components/index.html)