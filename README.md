# VISSIØN RESERVE

Static landing page built from the supplied VISSIØN Reserve HTML mockup and prepared for Vercel. The background is served locally from `assets/bg.jpg`.

## Deploy on Vercel

1. In Vercel, import this GitHub repository.
2. Framework Preset: **Other** (or leave auto-detected).
3. Build Command: leave empty.
4. Output Directory: leave empty / root.
5. Deploy.

No build step is required: this is a static site.

## Location link

The supplied HTML did not contain an actual location URL, so none was invented.

When the real map link is available, replace `href="#location"` on the `SCAN / CLICK HERE` link in `index.html` with the map URL, for example `https://maps.google.com/?q=YOUR_LOCATION`.

## Included effects

- Background from `assets/bg.jpg`
- RGB ghost channels and scanlines
- Subtle image movement with `prefers-reduced-motion` support
- Mobile full-screen presentation
- Desktop framed presentation
