# Magzhan Turganbay — Student Portfolio

An English-language personal portfolio with a creative layout, light and dark themes, and a little student humor.

**Website:** https://jubby786.github.io/magzhan-portfolio/

**Source:** https://github.com/Jubby786/magzhan-portfolio

## Run it locally

Download this repository and open `index.html` in a browser. No package installation or build step is needed.

You can also serve the folder locally if Python is installed:

```bash
python -m http.server 8000
```

Then open http://localhost:8000/.

## Publish and update with GitHub Pages

The publishing source is **main / (root)** in **Settings → Pages → Deploy from a branch**.

1. Edit `index.html` in the repository or on your computer.
2. Commit your changes to `main`.
3. Check the **Actions** tab for the Pages deployment result.
4. Open the website after the deployment succeeds. If you still see the previous version, refresh the page.

The `.nojekyll` file keeps this a plain static website.

## What is included

- Responsive layout and mobile navigation.
- Light/dark theme with local preference storage where supported.
- Scroll animations with reduced-motion support.
- Keyboard focus styles and Escape-to-close navigation.
- Readable content and navigation when JavaScript is unavailable.
- About, projects, developing skills, education, and verified GitHub links.

## Content

The V2I capstone is marked **In Progress**. Smart irrigation is identified as a literature review, and optical communication work as university labs. There are no invented awards, contact details, or proficiency scores.

## Customize

All content, CSS, and JavaScript are in `index.html`. Edit the `:root` variables for colors. Project descriptions are in `#projects`; GitHub links are in `#contact`.

Google Fonts are optional external requests; system fonts are used when they cannot load. There is no contact form, tracking script, API key, backend, or paid dependency.
