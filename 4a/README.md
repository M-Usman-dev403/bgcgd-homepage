# BGCGD Homepage

Static homepage — open `index.html` in a browser, or push this folder to GitHub and enable Pages (Settings → Pages → deploy from branch, root).

## Files

- `index.html` — the whole page (markup + styles + scripts inline)
- `support.js` — rendering runtime, must sit next to `index.html`
- `image-slot.js` — image placeholder component
- `assets/logo-light.png` — logo with the wordmark recolored white for dark backgrounds
- `uploads/` — photos, the hero video, press logos, and the map pin icon

## Replacing images

Every photo is an `<image-slot>` with a `src`. Drop a new file into `uploads/` and change that `src`
(hero video: the `<video src="uploads/sizzle.mp4">` near the top of the page).

## Club locations (placeholder data)

Map pins and location cards come from the `CLUBS` array in `index.html` (search for `const CLUBS`).
Names, neighborhoods, ZIPs and coordinates are samples — replace them with the real list.
Pin graphic: `uploads/location_53876-25530.avif`.

## Colors

Navy `#061426`, blue `#1f7ae0` / `#3d9bff`, orange `#f08a2c`, page ground `#f2f4f7`.

## External resources (need internet)

Google Fonts (Archivo), Leaflet 1.9.4 + OpenStreetMap tiles for the Club map.
