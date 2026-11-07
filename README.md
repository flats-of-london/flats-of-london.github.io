# Fourth Floor Planner

A 3D model of a one-bedroom fourth-floor flat in London (53 m², ceiling 2.26 m), built from the agent's floor plan and viewing photos, with a furniture planner.

**Live site:** https://gaspardol.github.io/3d_chesterton_london/

- **3D / Plan** views, eye-level presets, cut-away walls and ceiling toggle
- **Walk** mode: first-person walk-through (WASD + mouse, or touch joystick) with a minimap
- Add, drag, rotate and resize furniture at typical UK sizes; items turn red when they hit a wall, fixture or other piece, and show gaps to the nearest wall in cm
- Several layouts, saved in your browser (`localStorage`)

Dimensions come from the floor plan (scale checked against the four room sizes); window heights, ceiling slopes and the stair layout are estimates. Measure on site before buying anything that has to fit tightly.

Files: `index.html` (three.js app, no build step), `flat_glb.txt` (the model, a base64-encoded GLB), `flat_meta.json` (walls/fixtures for collision checks, room labels).
