# 3D Dungeon Labyrinth

A self-contained, browser-based first-person 3D dungeon maze built with **Three.js**, procedural HTML5 `<canvas>` textures, and synthesized Web Audio soundscapes. Start in pitch darkness, find the flashlight, navigate past cobwebs, crawling spiders, and framed wall artwork, and reach the bright sanctuary exit marked **OvertPsyops.AI** and **@TLTHE5TH**.

## Features
- **Pitch-Black Start & Working Flashlight:** Begins in darkness with a prompt to find the flashlight; press `F` to toggle your beam on or off once picked up.
- **Dungeon Atmosphere to Light Transition:** Deep corridors feature weathered stone, corner cobwebs, and animated 3D spiders with glowing red eyes, transitioning into bright light near the exit.
- **Framed Wall Artwork:** Displays uploaded artwork from `ART_FILES` (such as `art1.jpg`) on framed wall panels along the corridors, with an automatic procedural fallback.
- **Web Audio Soundscape:** Plays an eerie low dungeon drone while exploring and transitions to a bright victory chime when reaching the exit.
- **Live Minimap:** Top-right radar showing corridors, walls, the flashlight pickup, exit, and player position/facing angle.
- **Zero Build Step:** Runs directly in modern browsers from a single `index.html` file and hosts on GitHub Pages.

## Controls
- **Move:** `W` `A` `S` `D` or `Arrow Keys`
- **Look Around:** Move mouse (with pointer lock) or use `Q` / `E` to turn
- **Toggle Flashlight:** `F` (after picking up the flashlight)
- **Mute / Unmute Audio:** `M`
- **Pause / Resume:** Press `Esc` and click **Resume**

## Adding Artwork
1. Upload image files (for example, `art1.jpg`, `art2.jpg`) to the repository root next to `index.html`.
2. Add the exact filenames inside the single `ART_FILES` array in `index.html`.
3. Commit changes and wait for GitHub Pages to finish deploying.

## Hosting on GitHub Pages
1. Create a public repository on GitHub (for example, `3d-maze`).
2. Add `index.html` and `README.md` to the repository root.
3. Go to **Settings -> Pages**, set **Source** to **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. Open `https://tlthe5th.github.io/3d-maze/`.
