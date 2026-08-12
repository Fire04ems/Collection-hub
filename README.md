# Collection Hub v6 — Fixed Set Symbols

This fixes the prior update.

## What changed
- Set tiles now actually render an image.
- Matching Pokémon TCG sets use their individual set symbol.
- Any set without a match uses `pokemon-set-fallback.png`.
- Broken remote symbol images also fall back automatically.
- English and Japanese sets are split into separate tabs.
- Your Pokémon and coin data remain unchanged.

## Upload to GitHub
Replace/upload:
- index.html
- pokemon-data.json
- manifest.webmanifest
- sw.js
- icon.svg
- pokemon-set-fallback.png

Then commit, wait for GitHub Pages to deploy, and hard-refresh the site once in the browser.
