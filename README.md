# Fourth Floor Planner

A 3D model of a one-bedroom fourth-floor flat in London (53 m², ceiling 2.26 m), built from the listing's floor plan and viewing photos, with a furniture planner.

**Live site:** https://gaspardol.github.io/flats_of_london/

- **3D / Plan** views, eye-level presets, cut-away walls and ceiling toggle
- **Walk** mode: first-person walk-through (WASD + mouse, or touch joystick) with a minimap
- Add, drag, rotate and resize furniture: generic pieces at typical UK sizes plus ~85 popular IKEA items at their listed sizes (simplified shapes; not affiliated with IKEA); items turn red when they hit a wall, fixture or other piece, and show gaps to the nearest wall in cm; pieces taller than the 2.26 m ceiling or the sloped ceiling by the windows are flagged too
- Several layouts, saved in your browser (`localStorage`)

Dimensions come from the floor plan (scale checked against the four room sizes); window heights, ceiling slopes and the stair layout are estimates. Measure on site before buying anything that has to fit tightly.

Files: `index.html` (three.js app, no build step), `flat_glb.txt` (the model, a base64-encoded GLB), `flat_meta.json` (walls/fixtures for collision checks, room labels).
