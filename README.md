# Omega Slash site — drop-in files

Copy all files in this folder into the root of your GitHub Pages repo,
overwriting the old `index.html` (and adding the new files). No build
step, no dependencies — just static HTML/CSS.

- `index.html` — homepage
- `styles.css` — shared styles for every page
- `privacy-luna.html` — Luna privacy policy
- `privacy-bhakti-deepam.html` — Bhakti Deepam privacy policy

## Before you push

1. **Play Store links** — each app card in `index.html` has a commented-out
   "Get it on Play" button. Once an app is live, uncomment it and fill in
   the real Play Store URL.
2. **New apps** — duplicate one of the `privacy-*.html` files, swap the
   app name/description, and add a matching card in the `.apps-grid`
   section of `index.html`.
3. **App icons** — each app currently uses a plain letter/glyph as a
   placeholder icon. Swap in a real icon image if you have one (replace
   the `.app-icon` div with an `<img>`).
4. Both privacy policies state "no data collected" — only keep that
   wording if it stays true. If a future version of an app adds
   analytics, ads, or a cloud feature, that policy needs updating before
   the update ships (Play Store checks this).
