# Component Sources Plan

Purpose: define how external animated component sources may be used later.

No code installation yet.

## Approved source categories

User mentioned:

- Componentry — `https://componentry.dev/`
- React Bits — `https://reactbits.dev/`
- OriginKit — `https://www.originkit.dev/`

## Current source notes

### Componentry

Candidate patterns to verify before use:

- Scroll Choreography.
- Scroll Tilted Grid.
- Sticky Scroll Cards.
- Layered Stack.
- Animated Gradient.
- WebGL Liquid.
- Silk Aurora.
- Image Ripple Effect.

Likely use:

- Scroll Choreography for place transitions.
- Layered Stack for glass/depth cards.
- Animated Gradient only as subtle overlay if real photo needs atmosphere.

### React Bits

Candidate patterns to verify before use:

- Aurora / Soft Aurora backgrounds.
- Magic Rings.
- Scroll Stack.
- Scroll Reveal.
- Split Text.
- Tilted Card.
- Glass Surface.
- Spotlight Card.
- Grain.

Likely use:

- Split Text or Scroll Reveal for section titles.
- Tilted Card or Glass Surface for place cards.
- Soft Aurora only as low-opacity atmosphere, not main image replacement.

### OriginKit

Observed source status:

- Public page describes Originkit as a free animated component library for modern websites.
- It is marked beta.
- Detailed component list was not available from the inspected public crawl.

Likely use:

- Inspect directly before choosing specific components.
- Use only if components are source-visible, license-clear, and visually cleaner than building custom.
- Candidate use areas: nav, CTA button, contact form polish, simple animated sections.

Do not assume:

- Do not assume OriginKit is the same as Origin UI.
- Do not assume shadcn compatibility until verified.

## Rules before using any component

- Verify license.
- Inspect source before importing.
- Verify exact component availability from the source site/repo at implementation time.
- Adapt style to Nepal visual system.
- Remove generic demo content.
- Keep animations smooth and purposeful.
- Do not add components that imply services: booking, pricing, hotels, flights, transport.
- Keep bundle/performance cost controlled.
