# Jiuzhaigou Little Worlds — Version 7

## New interactions
- **Five clickable treasures:** blossom, butterfly, leaf, water jewel, golden star; counter and completion postcard.
- **Guided four-stop journey:** forest → lake → waterfall → panorama. Use **Next stop**.
- **Three discovery markers:** open bilingual information; lake/waterfall markers trigger a ripple.
- **Four seasons:** spring, summer, autumn, winter; animated seasonal weather and a short fade between scenes.
- **Water:** turn on **Tap water**, then tap the lake or waterfall pool to generate expanding ripples. Waterfall droplets already animate.
- **Nature sound:** user-activated synthesized water-like ambient sound; turn off using same button.
- **Explore land:** V6 keyboard walking (WASD) and mobile arrow controls preserved.
- **iPhone AR:** four GLB previews and four USDZ files; select season in `ar.html`, then open Apple Quick Look. The browser effects, collectibles, and walking controls are NOT available inside Apple's Quick Look. USDZ colors are not independently verified on a physical iPhone.

## Upload to GitHub Pages
1. Unzip this package on your computer.
2. In `https://github.com/Linar-2026/jiuzhaigou-explorer`, choose **Add file → Upload files**.
3. Drag the **11 extracted files**, not the ZIP or the parent folder, to the repository root. Confirm the names are exactly `index.html`, `ar.html`, four `jiuzhaigou-*.glb`, four `jiuzhaigou-*.usdz`, `README.md`.
4. Commit changes and wait for GitHub Pages deployment to finish.
5. Open `https://linar-2026.github.io/jiuzhaigou-explorer/` and hard refresh if needed.

### Limitations and tests
- Internet required for Three.js and model-viewer CDN imports.
- This is original **stylized educational art**, not a surveyed or photorealistic reconstruction of Jiuzhaigou.
- Test desktop 3D controls, iPhone Safari touch controls, and iPhone AR **separately**. A successful desktop 3D preview does not prove iPhone AR renders colors correctly.
- iPhone Safari does not provide general immersive WebXR VR; no VR headset experience is claimed.
- Seasonal fade is a short overlay transition, not full geometry morphing.
- Browser nature audio is synthesized, not a real field recording.


## Version 8 additions
- Opt-in procedural audio: wind, waterfall proximity and soft synthesized bird chirps (no third-party recordings). Audio requires a user tap, including on iPhone.
- Volume slider, on/off button; sound intensity changes as the walking camera approaches the waterfall.
- Three interactive stylized butterflies; tap to discover.
- Nature Quest 5 tasks: discover forest, lake, waterfall, all four seasons, and complete 3-question quiz with at least 2 correct.
- Existing 5 collectible gems, seasonal effects, guided tour, walking mode, AR GLB/USDZ assets are preserved.
- AR Quick Look does NOT run browser audio, butterflies or mini-games; AR remains a separate static seasonal model. USDZ color accuracy requires testing on iPhone.
- Sound is generated locally by Web Audio, so no external MP3 files or licenses are needed.
