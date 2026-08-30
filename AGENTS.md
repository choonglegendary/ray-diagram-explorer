# Legendary Six Simulation Style

This project belongs to Legendary Six and is taught by Mr. Choong (016-484 0556). Follow these rules whenever adding or changing a simulation.

## Teaching approach

- Build the diagram students normally draw in STPM, then make it move. Familiar textbook construction comes before extra theory.
- Prioritise the picture and direct manipulation. Keep formulas and readouts secondary.
- Cover all physically distinct cases and make real/virtual behaviour obvious.
- Use the correct representation for the topic: axial point objects where magnification is not part of the ray construction; arrows or media where transverse size matters.
- Keep physics and sign conventions internally consistent. Verify limiting and virtual cases rather than improvising them for appearance.
- Use concise labels familiar to students: O, I, F, 2F, C, P, n₁, n₂, u, v and m.

## Visual and interaction style

- Design mobile-first. The complete diagram must scale to the phone width as one picture. Never require horizontal scrolling or left/right page sliding.
- Do not use background grids.
- Keep the Legendary Six burgundy, gold and cream branding, logo, Mr. Choong's name and phone number.
- Keep the header compact. Do not add generic labels such as “Interactive Physics”.
- Prefer compact controls, quick-case buttons and direct dragging. Put the main continuous control below the diagram when that makes phone use easier.
- Avoid long instructions, large explanatory paragraphs, unnecessary legends and repeated notes.
- Put direction arrows on physical rays. Use dashed grey extensions for virtual rays.
- Show an eye for virtual-image tracing, without an explanatory eye caption.
- Mark important positions on both sides where relevant. Draw normals clearly in a distinct green and connect spherical-surface normals to C.
- Keep diagrams uncluttered while preserving the construction students need to learn.

## Images, GIFs and shared UI

- Call the numbered built-in media options **Scenes** on every page.
- Support local PNG, JPG, WebP and GIF uploads where an object/image representation is useful.
- Normalise GIF loop metadata so animations continue indefinitely.
- Centre uploaded media on the calculated point when the construction uses points.
- Scale image media by the calculated magnification, including inversion; do not impose an artificial diagram-size cap.
- Let students drag O and I directly. Do not add a separate “move O / move I” toggle.
- Use 5 cm as the minimum adjustable object distance unless the physics requires another bound.

## Site integration

- New simulations must use the same navigation, responsive behaviour and branding as the existing pages.
- Reuse shared assets and controls instead of introducing inconsistent terms or colours.
- After implementation, check JavaScript syntax, representative physics cases, mobile layout assumptions, GitHub Pages deployment and live URLs.
