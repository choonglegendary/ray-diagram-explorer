# Ray Diagram Explorer

A dependency-free interactive prototype for curved mirrors and thin lenses.

The interface uses the Legendary Six burgundy-and-gold identity and includes a reusable branded header for future simulations.
It is mobile-first: large touch controls, wrapped choices with no horizontal page sections, and a proportionally scaled full diagram for small screens.

Open `index.html` directly in a browser, or serve this folder locally:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Included

- Separate Mirror & Lens and Spherical Refraction simulation pages

- Convex and concave thin lenses
- Concave and convex curved mirrors
- Three principal-ray rules, with dashed virtual extensions
- Ray 1: parallel to the principal axis, then through/apparently from F
- Ray 2: through/toward F, then parallel to the principal axis
- Ray 3: through the optical centre for a lens, or reflected at the pole for a mirror
- Mirror Rule 4: through/toward 2F (C), then reflected back along the same path
- Presets for u = infinity, u > 2F, u = 2F, F < u < 2F, u = F, and u < F
- Slanted parallel rays and an image arrow for an off-axis object at infinity
- At u = infinity: F-ray plus centre ray for lenses; F-ray plus 2F(C)-ray for mirrors
- F and 2F position labels (with 2F = C for mirrors)
- Image hidden until at least two valid rays are selected
- Eye indicator on the viewing side whenever backward ray tracing forms a virtual image
- Local PNG, JPG, WebP and animated-GIF objects, transformed into the calculated image
- Uploaded GIF loop metadata is normalised to continuous playback without changing the original file
- Eight on-demand built-in GIF scenes selectable through compact numbered buttons
- Draggable object and image positions
- Adjustable object distance and focal length
- Live image distance, magnification, orientation, size and real/virtual classification

The optical element is intentionally drawn as a single vertical line so students focus on ray behaviour.

The spherical-refraction page covers convex and concave interfaces, adjustable refractive indices, radius of curvature, draggable object/image points, real or virtual axial point images, and optional uploaded or built-in animated stickers.
