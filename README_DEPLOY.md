# Elementia v20.54 — GitHub Pages artwork migration

This package is a folder-based replacement for the v20.53 browser edition. All original card IDs, rules, saves, art, and screen layout remain as before.

## Upload instructions

1. Back up the working `index.html` on GitHub.
2. Extract this ZIP to a folder on your computer.
3. Copy **`index.html` and the entire `assets` folder** to the ROOT of the `Elementia` repository. Keep exact capitalization.
4. **Upload the four MP3 music files from this package to the repository root**, or keep the identical music files you already have there.
5. With GitHub Desktop, commit and push these files (recommended for hundreds of image files); do **not** upload the deployment ZIP itself as a single GitHub file.
6. Visit `https://reymasgamez.github.io/Elementia/index.html?v=2054` after GitHub Pages deployment. Look for `v20.54 · Asset Library`.

**Important:** Uploading only `index.html` will give missing card images because the HTML now references `assets/cards/...`. If using the GitHub web interface, upload images in element-sized batches into the correct folders. The full folder tree is required.

## Content notes

- This edition incorporates the 11 element packages currently available (including previously supplied Air) and externalizes existing Aether art.
- No new Aether source ZIP or Other ZIP was supplied in this batch. The 16 previously embedded Aether designs have been extracted to the asset library. Other artwork remains as it was.
- Full cards are stored as optimized `*_card.webp`, and frame-free board portraits as `*_portrait.webp`. These are derived from the user's supplied PNGs; original files are not modified.
- Newly supplied Earth, Fire, Light, Time, Water art is indexed for future game-rule updates. This does **not** make missing gameplay mechanics functional.
- Upgraded cards without a distinct artwork source still show their existing placeholders.
- Forest Spirit and Forest Spectre's Growth still cost 1 Water Quanta.

When replacing an image later, retain its filename, and update the `?v=2054` reference in `index.html` to a newer version if a browser keeps the old image cached.
