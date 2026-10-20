# Whistler

A single-page visual history of James McNeill Whistler: his life as nine short moods, eighteen works with credits, and a timeline.

Plain static files with no build step. Open `index.html` in a browser, or serve the folder from GitHub Pages.

- `index.html` is the page. All text and credits are embedded in it.
- `images/` holds the artwork as 1200px WebP files. Each image is credited under its work, with a link to its source page.

The page, data and image script are generated from a private project, artist-histories, which holds `artist.json` and the image-search script. Edit the page's text there and rebuild, rather than editing `index.html` by hand.

The dedication line at the top hides itself after its end date, which is set in `artist.json`.
