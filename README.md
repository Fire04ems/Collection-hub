# Collection Hub v5

Pokémon set-symbol fallback update.

## Behavior
- If a Pokémon set has a matching official set symbol from the card database, that individual set symbol is displayed.
- If no symbol match is found, the Pokémon symbol supplied for the project is displayed instead.
- English and Japanese set tabs remain separate.
- Pokémon collection data and the Coin collection are unchanged.

## GitHub update
Upload/replace these files in the root of the existing repository:

- index.html
- pokemon-data.json
- manifest.webmanifest
- sw.js
- icon.svg
- pokemon-set-fallback.png

If `set-symbol-fallback.png` from v4 is still in the repository, it can be deleted after the new file is uploaded.

After committing, wait for GitHub Pages to deploy and refresh the website in the browser before reopening the installed phone app.
