# DOOM 3D Test Lab — Prototype 0.1

This is milestone 1: a dependency-free WebGL 1 test scene, intended to test browser graphics and camera controls before integrating Freedoom data.

## Run
- Open `index.html` in a modern browser with WebGL enabled.
- For GitHub Pages, upload `index.html` to a repository and enable Pages for the branch/root folder.
- Click inside the scene to capture the mouse. Press Escape to release it.

## Controls
- Mouse: look around (click viewport first)
- W/A/S/D: move
- Q/E: down/up
- Shift: move faster
- Buttons: wireframe, frustum culling, reset camera, render scale

## Current limitations
- The room, crates, pillars, and red figures are placeholder test geometry.
- This does not yet contain Freedoom's map, monsters, sounds, gameplay, or occlusion culling.
- The “frustum rejected” count measures object-level view-frustum rejection only; it is not hierarchical occlusion culling.
- The wireframe view is a diagnostic approximation.
- FPS/driver performance depends on browser and hardware.

## Next milestone
Load a freely licensed Freedoom WAD, inspect its map data and license files, and build a converter from map sectors/lines into 3D geometry. Keep original source assets and licenses in the repository as required by their terms.
