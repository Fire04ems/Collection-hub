# Collection Hub v3 — Pokémon Spreadsheet Import

This update keeps the Coin collection and imports the Pokémon workbook into the Hub.

Imported Pokémon data:
- 198 set sheets
- 21,143 card rows
- 4,507 owned variation entries
- 32,859 needed variation entries
- 13,714 variation entries marked unavailable (`-`)

## IMPORTANT: Upload all 5 app files

Replace/upload these files in the root of the existing GitHub repository:
- index.html
- pokemon-data.json  <-- NEW and required
- manifest.webmanifest
- sw.js
- icon.svg

You can also upload README.md, but it is not required for the app.

After committing, wait for GitHub Pages to deploy, then refresh the website. If the installed phone version stays old, open the GitHub Pages site in the browser first and refresh it.

## Pokémon tracking behavior
- X becomes Have, quantity 1.
- Numeric quantities are retained.
- Blank tracked variations are Need.
- `-` is shown as unavailable and is not counted as Need.
- The workbook odd placeholder value `4845` is treated as blank/Need because those sheets' own totals show it is not an owned-card marker.
- Edits made in the app are stored locally on that device.
- Where an English workbook set can be matched to the Pokémon TCG API, card images are loaded automatically.
