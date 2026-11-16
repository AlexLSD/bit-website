# ביט · ינשוף הלמידה

The landing page and privacy policy of **Bit**, a Hebrew learning app with an owl buddy.

- `index.html`: the animated landing page. Bit hatches, greets visitors by the time of day, and talks when tapped.
- `privacy.html`: the app's privacy policy (link to it from Google Play Console).
- `favicon.svg`: Bit's icon.

Static files only, no build step. Works on GitHub Pages: Settings → Pages → Deploy from branch `main`, folder `/ (root)`.

When the app is live on Google Play, set `const RELEASED = true;` in `index.html` so the download buttons link to the store.

Created by [AlexLSD](https://www.linkedin.com/in/syusimov) · [Buy Bit a coffee](https://buymeacoffee.com/alexlsd)
