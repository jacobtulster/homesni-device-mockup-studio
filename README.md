# HomesNI Device Mockup Studio

A browser tool for composing Apple-device mockups and exporting stills or showcase scroll animations.

**Use it live:** [jacobtulster.github.io/homesni-device-mockup-studio](https://jacobtulster.github.io/homesni-device-mockup-studio/)

## What’s included

| File | Purpose |
| --- | --- |
| `index.html` | The full studio app (open this) |
| `IMac_vector.svg` | iMac device art |
| `IPhone_17_Vector.svg` | iPhone device art |
| `gif.js` / `gif.worker.js` | Local GIF encoder |

MacBook Pro and iPad use built-in SVG art inside `index.html`.

## How to use

1. Open the live site above, **or** open `index.html` locally (keep every file in this folder together).
2. Click a device in the sidebar to place it.
3. Drop a screenshot onto a device screen.
4. Use **Export** for PNG, JPEG, SVG, GIF, or video.

## Features

- iMac, MacBook Pro, iPad, and iPhone mockups
- Drag, resize, rotate, and layer controls
- Vertical screenshot pan with top snap
- Showcase scroll preview + GIF / video export at 60fps
- High-res SVG / PNG export sized from your source screenshot
