# Implementation Rules — For Later Coding

No coding starts until user approves planning direction.

## Technical setup — confirmed

Current workspace:

- Framework: **Astro** (scaffolded, files recoverable from git).
- `sample.png` — style reference.
- `.vscode/` — editor config.
- `.astro/` — generated types.
- Original `src/`, `public/`, `package.json`, `astro.config.mjs`, `tsconfig.json` deleted from working tree but available in git history.

Before coding, restore and confirm:

- Restore deleted Astro project files from git.
- Run `npm install`.
- Verify `astro dev` runs.
- Package manager: npm.
- Deployment target: user to confirm (default Vercel).
- Asset source: user to confirm (real photos required).


## Quality requirements

Accessibility:

- Keyboard navigable.
- Visible focus states.
- Reduced motion support.
- Proper alt text for meaningful images.
- Decorative 3D hidden from screen readers.

Performance:

- Mobile-first fallback.
- Lazy-load heavy visuals.
- Avoid large unoptimized images.
- Keep font payload under 200KB.
- Keep animations GPU-friendly.

Design:

- One signature visual system.
- Consistent glass treatment.
- Strong type hierarchy.
- No generic service cards.
- No fake booking flow.
- Mixed real photos + 3D glass/depth UI.
- Mountains-first hero.
- Elegant editorial typography.
- CTA text: `Discover Nepal`.
- Real images only.

Strict content ban:

- No hotels.
- No transport.
- No flights.
- No tour packages.
- No prices.
- No booking flow.
- No service CTAs.
- No `Book` button copied from sample.

SEO/content:

- Real text content in HTML.
- WebGL/canvas must not be only source of important content.
- Metadata/copy needs approval.

## Build path after approval

1. Confirm open questions.
2. Lock content and section order.
3. Choose visual direction.
4. Choose motion/3D approach.
5. Build static structure.
6. Add visual system.
7. Add motion.
8. Test responsive and reduced motion.
9. Review with screenshots.
10. Iterate from user feedback.

After every change:

- Run subagent review against `review-process.md`.
- Fix issues or ask user directly if direction is unclear.
