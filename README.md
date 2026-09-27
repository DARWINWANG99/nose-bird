# Teresa Nose Bird

A browser game controlled by nose movement through the front camera.

## Play

Recommended device: iPad in landscape mode.

After GitHub Pages is enabled for this repository, open:

https://darwinwang99.github.io/nose-bird/

Then:

1. Allow camera access.
2. Hold still for about 2 seconds while the game calibrates.
3. Move your nose/head slightly up and down to guide the bird.
4. Fly through gaps and collect stars.
5. If the bird hits a wall or the screen edge, the game ends.

## Current MVP

- Front-camera input
- MediaPipe Face Landmarker
- Nose-tip tracking
- Calibration and smoothing
- Mobile/iPad landscape layout
- Obstacles and collision detection
- Stars and score
- Local best score
- Camera preview with nose marker
- No backend required

The game is intentionally kept as a single `index.html` so it can be tested quickly before adding more features.

## GitHub Pages

In this repository, open:

**Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**

Then use the play URL above.
