# Jiuzhaigou Little Worlds — Version 9

## What's new
- **Start Adventure**: visible game entry and step-by-step instructions.
- Six interactive missions, advanced by actual visitor actions: rotate the scene, discover the forest, create a lake ripple, discover the waterfall, explore all four seasons, and tap a butterfly.
- Progress tracking and a completion screen; replay and optional bonus Nature Quiz.
- **AR Explorer Challenge** on the `ar.html` webpage: four seasonal questions and earned badges, with instructions. The questions are played on the webpage, not inside Apple Quick Look.
- Retains V8's ambient sound, Nature Quest, butterfly discovery, waterfall animation, Explore Land controls, four seasonal GLB and USDZ assets.

## Important iPhone AR limitation
Apple Quick Look can display and place a USDZ miniature, but cannot run the website's custom JavaScript mini-games inside its camera view. The AR page therefore offers a **companion browser game** before/after opening Quick Look. Colors and placement of USDZ still need real-device testing; this version does not claim to have fixed a white-model issue.

## Upload to GitHub Pages
1. Extract the ZIP.
2. Visit https://github.com/Linar-2026/jiuzhaigou-explorer
3. Upload all 11 files from inside this folder to the repository **root**, replacing same-named files; do not upload the ZIP itself.
4. Commit changes, wait for Pages deployment, then visit https://linar-2026.github.io/jiuzhaigou-explorer/
5. On iPhone Safari, open the AR page and test the seasonal models in Quick Look.

**Quick update:** If all four GLB and four USDZ models already exist in the repository, replacing `index.html` and `ar.html` is enough for the new gameplay.

## Verification
HTML and JavaScript syntax can be checked locally; interactive gameplay and AR device compatibility require testing on your computer and iPhone. Browser resources load from external CDNs.
