## Smoke tests

Prereqs: Node installed.

1) Install deps
```
npm ci
```

2) Start dev server
```
npm run dev
```

3) Verify UI
- Hero H1 reads: "Makeup & Hair Styling by Arshnoor Kaur"
- Subtitle under hero: "Delhi | NCR — Luxury Bridal & Event Makeup Specialist"
- Nav shows NOOR logo image.
- Services section renders 4 cards from `data/services.json` with titles and prices.
- Booking & Payment Policy section exists and expands on click.

4) Accessibility quick checks
- All images have `alt`.
- Only one H1 on the page (hero).

5) Basic interactions
- Services and Projects cards drag without errors.
- Menu opens/closes; scrolling works.

