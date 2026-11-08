# neon drift

a synthwave runner built with raw webgl2 — no libraries, one html file.

**play:** https://hokwaichan.github.io/neon-drift/

## controls
- ← → or A / D to steer, drag on touch
- space / tap to start and retry
- dodge the blocks, grab the gold

## webgl2 bits
- instanced rendering (`drawArraysInstanced`) for every block, pillar, orb and particle
- vertex array objects
- glsl 300 es: full-screen-triangle sky via `gl_VertexID`, `fwidth` anti-aliased grid, shader-drawn neon edges, distance fog

## run locally
open `index.html` in a browser, or `npx serve .`
