# Copilot Instructions for html5up-landed

## Project Overview
This is a static HTML5/CSS/Sass landing page template called "Landed" by HTML5 UP. It is designed to be modern, responsive, and multipurpose, featuring multiple pages and pre-styled elements. The project is primarily for personal or commercial use under the CCA 3.0 license.

## Architecture & Structure
- **Pages:** Main entry points are `index.html`, `elements.html`, `left-sidebar.html`, `right-sidebar.html`, and `no-sidebar.html`.
- **Assets:**
  - CSS: Located in `assets/css/`, with main styles in `main.css` and `noscript.css`. Font Awesome is used for icons.
  - JS: Located in `assets/js/`, includes jQuery, Scrollex, Dropotron, and custom scripts in `main.js` and `util.js`.
  - Images: All images are in `assets/images/` and `images/`.
  - Sass: Source files in `assets/sass/`, organized with partials in `libs/`.

## Developer Workflows
- **No build system is present by default.**
  - To update CSS, edit Sass files in `assets/sass/` and compile manually to `assets/css/main.css`.
  - Use any standard Sass compiler (e.g., `sass assets/sass/main.scss assets/css/main.css`).
- **No automated tests or CI/CD scripts are included.**
- **Debugging:**
  - Use browser dev tools for inspecting HTML/CSS/JS.
  - JS errors are typically handled in the browser console.

## Project-Specific Conventions
- **Class and ID naming:** Follows BEM-like and semantic patterns for clarity and maintainability.
- **JS Plugins:**
  - jQuery is the base for all JS plugins.
  - Scrollex and Dropotron are used for scrolling effects and dropdowns.
- **Responsive Design:**
  - Uses custom breakpoints defined in Sass (`_breakpoints.scss`) and JS (`breakpoints.min.js`).
- **Noscript Support:**
  - `noscript.css` provides fallback styles for users with JS disabled.

## Integration Points & External Dependencies
- **Font Awesome:** For icons, loaded via CSS.
- **jQuery:** Required for all interactive JS features.
- **Scrollex, Dropotron:** For scroll and dropdown effects.
- **Responsive Tools:** Used for adaptive layouts.

## Key Files & Directories
- `index.html`, `elements.html`, etc.: Main pages.
- `assets/css/main.css`: Main stylesheet (compiled from Sass).
- `assets/sass/main.scss`: Main Sass entry point.
- `assets/js/main.js`: Custom JS logic.
- `assets/js/jquery.*.js`: jQuery plugins.
- `assets/sass/libs/`: Sass partials for variables, mixins, breakpoints, etc.

## Example Workflow
1. Edit HTML in any main page file.
2. Edit styles in `assets/sass/main.scss` or partials, then compile Sass to CSS.
3. Edit JS in `assets/js/main.js` for custom logic.
4. Open `index.html` in a browser to view changes.

## License
- Free for personal and commercial use under CCA 3.0. See `LICENSE.txt` for details.

---
**If you need to automate Sass compilation or add build/test workflows, document those steps here.**
