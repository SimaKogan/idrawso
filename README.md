# I draw so.

Single-page photo gallery on plain JavaScript (ES modules, no framework):
photos taken with a Samyang 500mm f/6.3 Mirror lens, grouped by place.

## Run

    npm start

Then open http://localhost:8000. Opening `index.html` directly does not work,
because browsers block ES modules and `fetch` on `file://`.

## Structure

- `index.html`, `styles/idrawso.css` — page and styles
- `src/main.js` — entry point
- `src/ui/` — menu, sections and image viewer
- `src/fotos.json` — sections and photo numbers

## Photos

Photos are expected in `500/` (full size) and `500s/` (thumbnails) and are
not stored in this repository.
