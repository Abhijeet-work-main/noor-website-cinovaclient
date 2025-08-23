## Manual actions required

1) Confirm the logo file exists at `/Assets/noor-logo.png`. If the actual path differs, update `branding.config.json.logoPath` and the references in `index.html` head and nav.
2) Local testing: fetching `data/services.json` requires serving over HTTP. There is no root `package.json`. Use any static server (e.g. VS Code Live Server) to open `index.html`, or add a minimal dev script if desired.

