# Ray Marching SDF Playground

Interactive WebGL 2 ray marching playground with 8 signed distance field scenes rendered entirely from math — no meshes, no textures, pure fragment shader computation.

## Scenes

- **Mandelbulb** — Animated fractal power geometry
- **Infinite Corridor** — Repeating architectural flythrough
- **Organic Blobs** — Smooth union metaballs
- **Crystal Lattice** — Infinite repetition with animated nodes
- **Twisted Torus** — Domain-warped torus with orbiting spheres
- **Menger Sponge** — Recursive boolean subtraction fractal
- **Alien Terrain** — FBM noise heightfield with floating orbs
- **Gyroid Surface** — Triply periodic minimal surface

## Features

- WebGL 2 fragment shader ray marcher
- Soft shadows with adjustable softness
- Ambient occlusion
- Glow/volumetric light accumulation
- FunForrest color palette (gold/orange/dark brown)
- Interactive orbit camera (drag to rotate, scroll to zoom)
- Touch/pinch support for mobile
- PNG screenshot export
- Keyboard shortcuts (1-8 scenes, H panel, P screenshot, Space pause)

## Tech

Single HTML file. WebGL 2 GLSL fragment shaders. No dependencies.

## Author

Ian Handy — [ianhandy.com](https://ianhandy.com)
