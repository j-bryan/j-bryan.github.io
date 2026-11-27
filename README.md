# Jacob Bryan’s portfolio

A static site built with HTML and CSS. Open `index.html` in a browser or serve the folder locally with `python3 -m http.server 8000`.

## Updating the site

Update Publications, Software, or About in `index.html`. The layout lives in `styles.css`. Future demos can live in standalone folders such as `demos/storage-dispatch/`, with each demo loading its own scripts and styles.

The campus animation uses SVG overlays in `index.html` and CSS keyframes in `styles.css`. The overlay coordinates match the 1200 × 800 artwork in `energy-campus-base.webp`, where the original blades have been removed. Visitors who prefer reduced motion see the original `energy-campus.webp`.

## GitHub Pages

Use the `j-bryan/j-bryan.github.io` repository to publish at `https://j-bryan.github.io/`. Push the site files to `main`, then select **Settings → Pages → Deploy from a branch → main → / (root)**. GitHub Pages will publish subsequent pushes to that branch. The `.nojekyll` file lets Pages serve the files directly.
