
# 3D Website

A 3D, scroll-driven website

## Concept
One cloud of about 10,000 particles is the only 3D object on the page. As you scroll, it morphs between shapes that match each section:

| Section | Shape |
|---|---|
| Intro | Sphere |
| Workshops | DNA-style helix |
| Competitions | Torus knot |
| Exhibitions | Gridded cube |
| Lectures | Spiral galaxy |
| Join | The letters "TF" |

## Interactions
- **Scroll**: drives the morph, camera placement, colors and a 3D tilt on the text blocks
- **Cursor**: particles push away from the pointer and the whole object tilts toward it
- **Click or tap**: sends a shockwave through the particles
- **Side dots**: jump to any section (keyboard accessible)

## Tech
- Three.js r128 (loaded from cdnjs), a custom GLSL vertex and fragment shader, plain HTML, CSS and JavaScript
- Single file, no build step
- Responsive layout, respects `prefers-reduced-motion`, falls back to plain text if WebGL is unavailable

## Run it
Open `3d.html` in a browser (internet needed for the Three.js CDN and Google Fonts).
