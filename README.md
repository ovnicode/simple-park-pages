# simple-park-pages

Public static pages for Simple Park, served via GitHub Pages at
`https://simple-park.game.ovnicode.com`.

- `index.html` — home page presenting the game, with a link to the privacy policy.
- `privacy-policy.html` — the app's privacy policy (linked from Google Play Console).
- `assets/` — optimized WebP images (icon, feature graphic, screenshots) sourced from
  `store-assets/` in the main `simple-park` game repo.
- `src/input.css` / `css/styles.css` — Tailwind CSS source and compiled, minified output.
  Plain HTML/CSS, no JS framework or server-side build step — GitHub Pages serves the
  files as-is.

## Updating styles

```
npm install
npm run build   # compiles src/input.css -> css/styles.css
```

Commit the rebuilt `css/styles.css` along with any HTML changes.
