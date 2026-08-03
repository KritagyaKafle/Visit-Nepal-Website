# Motion + Interaction Plan

## Motion principle

Motion should feel like moving through mist, altitude, and layered landscape.

Use fewer, better animations.

## Hero motion

Planned behavior:

- Slow parallax between background image layers.
- Large `NEPAL` word subtly shifts or fades on scroll.
- Place cards lift slightly on hover.
- CTA has soft glow/frost transition.
- 3D glass/depth overlays create premium spatial feel while real mountain photo stays dominant.

No aggressive bounce.
No random spinning elements.

## Scroll choreography

Recommended:

- GSAP ScrollTrigger for pinned visual journey.
- Scrubbed parallax for mountains/cloud/mist layers.
- Staggered reveal for place cards.
- Smooth opacity/transform section transitions.
- Use selected component patterns from Componentry, React Bits, and OriginKit only where they improve smoothness and refinement.

Rules:

- Scrub animations use linear ease.
- Entrance animations use soft ease.
- Animate only `transform` and `opacity` where possible.
- Add `prefers-reduced-motion` fallback.

## 3D/depth interaction

Approved direction:

- Mixed real photos + 3D glass/depth UI.

Implementation preference:

- Default to CSS/GSAP/Framer 3D depth illusion first.
- Use WebGL/Three.js only after direct user approval.
- If WebGL is approved later, it must stay subtle and must not overpower real mountain photography.
- Mobile fallback must be static/low-motion.

## Micro-interactions

Use:

- Glass card hover lift.
- Nav active underline/fill.
- CTA pressed state.
- Smooth image reveal masks.
- Subtle cursor-follow glow only if performance allows.

Avoid:

- Heavy cursor effects on mobile.
- Excessive hover-only interactions.
- Infinite animation in every section.

## Reduced motion

If user device requests reduced motion:

- Disable parallax.
- Disable scrub animations.
- Keep simple fades or instant state changes.
- Keep content fully accessible.
