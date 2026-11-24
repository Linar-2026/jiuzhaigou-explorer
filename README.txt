JIUZHAIGOU XR — TESTABLE PROTOTYPE

Upload these 4 files to the ROOT of the NEW GitHub repository:
index.html
ar.html
jiuzhaigou-miniature.glb
README.txt

Do not upload the ZIP itself. The 3D pages need internet access to load Three.js and model-viewer from CDNs.
Enable Settings > Pages > Deploy from a branch > main > /(root).
Open https://linar-2026.github.io/jiuzhaigou-explorer/

TEST 1: On desktop Chrome, 3D landscape appears. Drag to orbit, scroll to zoom, click gold markers, click Lake/Waterfall, try Guided Tour, click Chinese. Walk mode: click and use WASD; Esc exits pointer lock.
TEST 2: On iPhone Safari, open /ar.html and rotate 3D miniature. Tap Place landscape in AR. Quick Look depends on model-viewer generating a USDZ on device and has NOT been verified on an iPhone. If the AR button does not open AR, do not present it as working.
TEST 3: On WebXR VR headset with browser support, open index.html over HTTPS and use Enter VR button. Desktop Chrome without headset will report VR unsupported. VR has NOT been verified on hardware.

LIMITATIONS: The model is an original stylized low-poly concept, not photorealistic. Five Flower Lake and Nuorilang Waterfall are NOT geographically adjacent; they are deliberately placed together in this conceptual diorama. Water animation is an overlay; forest geometry is simplified. AR and VR require device testing.

TECH: Three.js 0.164.1 via jsDelivr, model-viewer 4.0.0 via Google CDN, procedural GLB. No paid assets. No external image licenses required.
