# Collection Hub v13 — Embedded Set Symbols

This version fixes the Poké Ball fallback problem by embedding the Pokémon set-symbol images directly into `pokemon-data.json`.

https://fire04ems.github.io/Collection-hub/

Embedded existing set symbols: 87

Explicit symbols added for:
- Mega Evolution
- Pitch Black (PBL)
- Chaos Rising
- Perfect Order (POR)

The app now uses symbol priority:
1. Embedded symbol data
2. Local symbol file
3. API symbol
4. Pokémon fallback

Because the primary symbol is embedded in `pokemon-data.json`, GitHub folder uploads and browser image caching can no longer make those set symbols disappear.

## GitHub update
Replace:
- index.html
- pokemon-data.json
- sw.js
- manifest.webmanifest
- icon.svg
- pokemon-set-fallback.png

The `english-symbols/` and `japanese-symbols/` folders can remain in the repository, but the app no longer depends on them for sets that have embedded symbols.

Cache version: v13.
