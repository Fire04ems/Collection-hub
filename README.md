# Collection Hub v8b — Embedded English + Japanese Symbols

This build fixes the English symbol regression.

It scans the Main Sheet for every embedded set-symbol image and pairs it with the set name in the adjacent cell.

Local symbols matched:
- English: 70
- Japanese: 21

Upload/replace:
- index.html
- pokemon-data.json
- manifest.webmanifest
- sw.js
- icon.svg
- pokemon-set-fallback.png
- entire `english-symbols` folder
- entire `japanese-symbols` folder

Matched symbols are local files, so they no longer disappear if the public Pokémon API fails.
Unmatched sets continue to use the Pokémon fallback symbol.
