## feat(brand): apply NOOR branding & client content (hero, services, booking-policy, styles)

Edited:
- `style.css`: Injected brand CSS variables from `branding.config.json`, mapped accents, added hero subtitle styles, set hero bold color to brand accent, minor logo image style.
- `index.html`: Updated title/meta (description, og:image, favicon), loading logo text, nav logo to image with alt, hero H1 and subtitle, cleared services container, added Booking & Payment Policy section scaffold.
- `script.js`: Added `renderServicesFromData()` to load `data/services.json` and render cards before initializing drag controller; kept existing animations and behavior intact.
- `branding.config.json`: Verified logoPath; no schema changes.

Added:
- `data/services.json`: Services data for Party, Special Occasion, Engagement, Bridal with prices and descriptions.

Notes:
- Fonts loaded via Google Fonts per branding config: Playfair Display and Inter.
- Kept Cinova visual style and animations; added prefers-reduced-motion support already present.

