# Skills Plan — Visit Nepal Website

Purpose: define which design and build skills must guide this project before any coding starts.

## Active skills to use

### 1. Senior graphic design direction

Use for:

- Visual identity.
- Composition.
- Color discipline.
- Image treatment.
- Layout hierarchy.
- Non-generic tourism mood.

Rules:

- Treat visually inspected `sample.png` as style reference, not content reference.
- Keep Nepal as the subject.
- Avoid generic travel-template look.
- Ask user before inventing brand claims, factual copy, itinerary, pricing, or service details.

### 2. Premium frontend design

Use for:

- Cinematic hero.
- 3D/depth feeling.
- Glass surfaces.
- Smooth premium transitions.
- Signature memorable visual.

Rules:

- One main “wow” system only.
- Keep supporting sections clean.
- Use dark cinematic base with controlled warm cultural accents.
- Respect mobile performance.
- Include reduced-motion fallback.

### 3. Frontend design

Use for:

- Distinct art direction.
- Page structure.
- Copy tone.
- Layout critique before build.

Rules:

- Hero must state page thesis.
- Typography must carry identity.
- Structural labels must mean something.
- Motion must support the journey, not decorate randomly.

### 4. GSAP / Framer scroll animation

Use for:

- Scroll-triggered reveals.
- Parallax landscape depth.
- Pinned story sections.
- Smooth transitions between places.
- Motion tied to user scroll.
- Integrating selected animated components from Componentry, React Bits, and OriginKit only after license/source review.

Preferred approach:

- GSAP ScrollTrigger for pinned cinematic sections and complex scroll choreography.
- CSS transitions for simple hover/focus states.
- Do not animate layout-heavy properties like width/height.

### 5. Web typography

Use for:

- Font pairing.
- Responsive type scale.
- Readability.
- Body line length.
- Font loading plan.

Rules:

- Maximum 2 primary type families.
- Body text must stay readable.
- Font payload target under 200KB.
- Use real Nepal tourism copy only after user approves content direction.

### 6. Caveman token optimizer

Use for:

- Concise assistant updates.
- Compact final summaries.

Rules:

- Keep technical meaning exact.
- Code and filenames remain normal.
- Planning documents stay professional and readable.

## Not used now

### Image generation

Not used because user chose real images only.

Rule:

- Do not generate AI landmark/place images for the final website unless user reverses this decision.

## Review subagent process

Use a reviewer subagent after each planning/code change in this session.

Reviewer checks:

- Premium refined visual direction.
- Clean non-generic design.
- Mixed real photos + 3D glass/depth UI.
- Mountains-first hero.
- Elegant editorial typography.
- Smooth animation plan.
- No hotel/transport/service content.
- No invented place facts.
- Real image requirement preserved.
