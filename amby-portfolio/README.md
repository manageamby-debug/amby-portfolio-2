# Amby – Portfolio

Open `index.html` in any browser (works offline except Google Fonts, which fall back to system fonts).

## Edit
- **Contact links:** search `index.html` for `mailto:`, `github.com/` and `wa.me/` and add your details
  (e.g. `mailto:you@email.com`, `https://github.com/yourname`, `https://wa.me/255XXXXXXXXX`).
- **Projects:** edit the `PR=[...]` array in `index.html`. For each project set `live` (website URL, shows a "Live preview" button), `repo` (GitHub link) and `shot` (screenshot as a data-URI, optional).
- **Photo on the card:** replace the embedded image (`IMG.src=...`) with your own base64 JPEG,
  or keep `assets/photo.jpg` as the master copy.
- **Skills / typing text:** edit the `.chips` spans and the `W=[...]` array.

## Folder
- `index.html` – the whole site
- `vendor/three.min.js` – Three.js r128 (local copy)
- `assets/photo.jpg` – the card photo
