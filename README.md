# 3D Walkthrough Maze

A self-contained, browser-based first-person 3D maze built with **Three.js** and procedural HTML5 `<canvas>` textures. Walk through the corridors, navigate using the top-right minimap, and reach the exit marked with **OvertPsyops.AI** and **@TLTHE5TH**.

## Features
- **First-Person 3D Walkthrough:** Smooth movement and wall-sliding collision detection in Three.js.
- **Live Minimap:** Real-time top-down view showing walls, corridors, the exit beacon, and player position/facing direction.
- **3D Exit Signpost:** Displays `OvertPsyops.AI` and `@TLTHE5TH` at the end of the maze alongside the glowing green exit beacon.
- **Zero Build Step:** Runs directly in modern browsers from a single `index.html` file and hosts cleanly on GitHub Pages.

## Controls
- **Move:** `W` `A` `S` `D` or `Arrow Keys`
- **Look Around:** Move mouse (with pointer lock) or use `Q` / `E` to turn
- **Pause / Resume:** Press `Esc` and click **Resume**

## Hosting on GitHub Pages
1. Create a public repository on GitHub (for example, `3d-maze`).
2. Add `index.html` and `README.md` to the repository root.
3. Go to **Settings → Pages**, set **Source** to **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. Open `https://<your-username>.github.io/3d-maze/`.
