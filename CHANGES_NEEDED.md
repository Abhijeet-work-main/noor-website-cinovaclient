## Manual actions required

1) Provide the exact Booking & Payment Policy text. Replace the placeholder inside the `<details>` block in `index.html` (section with id `policy`).
2) Confirm the logo file exists at `/Assets/noor-logo.png`. If the actual path differs, update `branding.config.json.logoPath` and the references in `index.html` head and nav.
3) About copy not provided. Share 2–3 sentence About text to place under an About/Intro block and to derive the first 140 chars for the meta description.
4) Local testing: fetching `data/services.json` requires serving over HTTP. There is no root `package.json`. Use any static server (e.g. VS Code Live Server) to open `index.html`, or add a minimal dev script if desired.

