# Jiuzhaigou Little Worlds — V5

## What changed
- iPhone AR now loads four explicit USDZ files rather than relying on browser GLB-to-USDZ conversion. Each USDZ includes UsdPreviewSurface materials. This is a best-effort technical fix, **not yet verified on a physical iPhone**.
- Browser explorer includes falling winter snow, summer sunshine, spring blossoms, autumn leaves, and extra moving waterfall droplets.
- Apple Quick Look AR displays static models. The HTML weather/waterfall animation does **not** animate inside AR.

## Upload to GitHub Pages
Unzip this folder. Upload all 10 project files (index.html, ar.html, 4 GLB and 4 USDZ) to the **root** of Linar-2026/jiuzhaigou-explorer. Replace the old files with the same names. Keep filenames exactly. Commit changes and wait for the green GitHub Pages deployment check.

Open https://linar-2026.github.io/jiuzhaigou-explorer/ on desktop and Safari on iPhone. Choose a season in the 3D explorer; for AR, tap AR test, choose season again, then Place in AR. Test Object view colors and AR placement.

## Limitations
The browser scene and AR assets are separate artistic interpretations. Browser weather and water effects are not baked into the GLB/USDZ models. These models are not photogrammetry or surveyed Jiuzhaigou geography. No headset VR is included.

If AR remains white, capture the Object view screenshot and the iOS version. USDZ compatibility must be checked on device; material binding is not a guarantee.
