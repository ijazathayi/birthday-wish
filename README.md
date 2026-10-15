# Birthday Wish Site 🎂

A mobile-first birthday letter page. Pure HTML/CSS/JS — no build step, no dependencies.

## What's inside
- `index.html` — the whole site (letter types out on open → surprise button → finale)
- `vercel.json` — optional Vercel config (clean URLs)

## Deploy on Vercel (easiest way)

1. Go to https://vercel.com/new
2. Drag & drop this whole folder (or connect your GitHub repo if you've pushed it)
3. Vercel auto-detects it as a **static site** — leave all settings as default, press **Deploy**
4. You get a link like `https://your-site.vercel.app` — share that with her. Works every time she opens it, on phone or laptop.

### Or with the CLI
```bash
npm i -g vercel
vercel
```

## Changing the letter
Open `index.html`, find `var LETTER =` (about 60% down the file) and replace the text between the quotes.
Every `\n` in the text becomes a new line. Keep it simple — no code knowledge needed.

## Notes
- No microphone or headphones logic — it opens straight to the letter now.
- Animations pause automatically for users with reduced-motion enabled (battery saver / accessibility).
- Fonts load from Google Fonts; the site still works offline-ish if fonts fail (falls back to system fonts).
"# birthday-wish" 
