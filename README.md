# Lean Her Way

Landing page for Lean Her Way, supporting women-led businesses with tailored growth capital and financial solutions.

## Structure

`index.html` contains the full page (HTML, CSS and JavaScript in one file). Images and logos are in the `assets` folder.

## Publishing on GitHub Pages

In the repository, open Settings, then Pages. Under "Build and deployment", choose "Deploy from a branch", select `main` and the `/ (root)` folder, and save. The site will be live at https://mahrukhraza05.github.io/leanherway/ within a few minutes.

## Before launch

1. Replace `assets/hero-temp.jpg` with the full hero photo exported from Figma, saved as `assets/hero.jpg`, then update the image path in `index.html` and remove the `is-temp` class.
2. Add the LinkedIn, Instagram and Facebook links (search for `TODO` in `index.html`).
3. Add a form service endpoint to `FORM_ENDPOINT` in `index.html` so contact form messages arrive in your inbox. Until then, the form opens the visitor's email app.
