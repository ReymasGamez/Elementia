ELEMENTIA: THE RETURN — v20.56 COMPLETE GITHUB DEPLOYMENT
============================================================

This is a COMPLETE deployment package, not a symbols-only patch.
It contains the v20.55 Light mechanics, the v20.54 card-art asset library,
all four existing music MP3 files, and all 12 official element symbols
as separate reusable files under assets/symbols/.

HOW TO DEPLOY ON WINDOWS
------------------------
1. Keep a backup of your current working Elementia repository.
2. Extract this ZIP to a temporary folder.
3. Open your local Elementia repository folder (GitHub Desktop: Repository -> Show in Explorer).
4. Copy the CONTENTS of the extracted deployment folder into your repository root.
   You should see index.html and assets/ directly in the repository root,
   not an additional Elementia_v20.56_GitHub_Deployment/ subfolder.
5. Choose to replace index.html and any matching files when asked.
6. Commit and push with GitHub Desktop.
7. Open https://reymasgamez.github.io/Elementia/index.html?v=2056

IMPORTANT
---------
The HTML intentionally relies on assets/cards/ and assets/symbols/.
Upload ALL extracted contents; uploading index.html alone would leave
card artwork and symbols missing. GitHub Desktop has no 100-file browser
upload cap. The four MP3s remain at the repository root as before.

NEW SHARED SYMBOL PATHS
-----------------------
assets/symbols/Air.webp
assets/symbols/Darkness.webp
assets/symbols/Fire.webp
assets/symbols/Water.webp
assets/symbols/Earth.webp
assets/symbols/Light.webp
assets/symbols/Life.webp
assets/symbols/Death.webp
assets/symbols/Time.webp
assets/symbols/Gravity.webp
assets/symbols/Entropy.webp
assets/symbols/Aether.png

The original symbol image bytes were extracted from the v20.55 HTML.
The v20.55 Light mechanics were preserved; no game-rule changes intended.
