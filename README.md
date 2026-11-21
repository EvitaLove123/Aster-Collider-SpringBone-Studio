# Aster Collider & Spring Bone Studio

Mobile-first, browser-based VRM physics workspace for Android and GitHub Pages.

## Current prototype
- Import VRM 0.x / VRM 1.0 and GLB for local preview using Three.js and three-vrm.
- Discover model bones.
- Create, select and delete collider groups.
- Add sphere collider records with bone attachment, XYZ offset and radius.
- Create spring-chain setting records with stiffness, drag, gravity, hit radius and collider-group assignment.
- Basic bone rotation preview and procedural motion timeline.
- Save workspace settings as JSON locally.

## Important limitations
This is an editor prototype, not yet a complete VRM physics authoring/exporter. Collider and spring settings currently remain in the workspace and are not serialized into the VRM `secondary` extension. The VRM export button is intentionally disabled to avoid producing invalid files. Procedural motion is a preview, not a baked animation clip. Full Spring Bone simulation, robust collider placement, advanced pose presets, and verified VRM 0.x / 1.0 export remain future work.

## Run
Open the GitHub Pages site in a modern mobile browser. Model files are processed locally in the browser and are not uploaded to a server.

## Deploy
Repository Settings → Pages → Deploy from a branch → `main` / `/(root)`.
