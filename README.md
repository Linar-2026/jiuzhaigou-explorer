# Jiuzhaigou · Little Worlds (Version 4)

Cute, playful 3D interpretation inspired by user-provided references. This is **not** a geographically accurate model.

## GitHub Pages upload
Upload ALL files from this folder into the **root** of the GitHub repository (not inside another folder):
- `index.html`
- `ar.html`
- `jiuzhaigou-spring.glb`
- `jiuzhaigou-summer.glb`
- `jiuzhaigou-autumn.glb`
- `jiuzhaigou-winter.glb`

You do not need `make_models.py` on GitHub. If GitHub already has files with the same names, upload these files to replace them.

In Settings > Pages, select Deploy from branch > main > /(root). Wait for deployment, then visit `https://linar-2026.github.io/jiuzhaigou-explorer/`.

## Tested versus experimental
- `index.html`: Real interactive 3D created procedurally in JavaScript with Three.js. Season switching, orbit/pinch, viewpoints, bilingual notes, and mobile collapsible panel are implemented. **Requires internet** to load Three.js from jsDelivr CDN. Cannot be tested by simply opening an offline file without internet.
- `ar.html`: Four-season GLB previews and **experimental** iPhone Safari AR using model-viewer's automatic Quick Look conversion. No separately validated USDZ files are included. White materials may still occur in Quick Look. Do not claim AR is validated until checked on a physical iPhone.
- WebXR VR: not included. iPhone Safari does not provide general WebXR immersive VR support.

## Notes
The desktop/browser scene is richer than the four lightweight AR GLB assets. This version prioritizes a working and appealing browser explorer, rather than pretending that unverified AR works.
