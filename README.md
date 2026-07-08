# HomesNI Device Mockup Studio

A local browser tool for composing Apple-device mockups and exporting stills or showcase scroll animations.

## What’s included

| File | Purpose |
| --- | --- |
| `index.html` | The full studio app (open this) |
| `IMac_vector.svg` | iMac device art |
| `IPhone_17_Vector.svg` | iPhone device art |
| `gif.js` / `gif.worker.js` | Local GIF encoder (works under `file://`) |

MacBook Pro and iPad use built-in SVG art inside `index.html`.

## How to use

1. Keep every file in this folder together.
2. Open `index.html` in Chrome / Edge (double-click is fine).
3. Click a device in the sidebar to place it.
4. Drop a screenshot onto a device screen.
5. Use **Export** for PNG, JPEG, SVG, GIF, or video.

> Tip: GIF export needs `gif.js` and `gif.worker.js` next to `index.html`.

## Features

- iMac, MacBook Pro, iPad, and iPhone mockups
- Drag, resize, rotate, and layer controls
- Vertical screenshot pan with top snap
- Showcase scroll preview + GIF / video export at 60fps
- High-res SVG / PNG export sized from your source screenshot
