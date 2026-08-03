# 3D + Asset Plan

## Goal

Create a clean 3D creative feel using real Nepal imagery plus glass/depth UI.

User-selected direction:

- Mixed: real photos + 3D glass/depth UI.
- Mountains first.
- Real images only.

## Possible visual assets

Hero layers:

- Real mountain photograph.
- Mist/cloud layer.
- Optional temple/stupa foreground only if approved and visually accurate.
- Soft golden light.
- Large translucent `NEPAL` text.
- Glass place cards with perspective depth.

Place card images:

- Pashupatinath.
- Swayambhu.
- Lumbini.
- Everest / Khumbu region candidate.
- Annapurna / Machapuchare view candidate.
- Pokhara / Phewa Lake candidate.
- Bhaktapur Durbar Square candidate.
- Chitwan candidate.

Texture overlays:

- Subtle grain.
- Mist gradients.
- Glass blur.

## 3D approaches

### Default path — CSS/GSAP/Framer 3D depth illusion

Pros:

- Faster.
- Safer on mobile.
- Easier to build.
- Lower dependency cost.

Use:

- Layered images.
- Perspective transforms.
- Scroll parallax.
- Masked reveals.
- Glassmorphic cards.
- Depth shadows.

### Optional path — WebGL / Three.js hero atmosphere

Pros:

- Stronger premium “alive” feel.
- Better depth and interaction.

Costs:

- More implementation time.
- More performance risk.
- Needs mobile fallback.
- Needs careful accessibility handling.

Current rule:

- Use CSS/GSAP/Framer depth first because it preserves real-photo authenticity and performs better.
- Add WebGL/Three.js only after direct user approval.
- If added, WebGL is subtle atmosphere only, not fake landscape.

## Asset integrity rules

- Do not use unlicensed landmark photos.
- Do not generate fake religious/cultural imagery unless user explicitly approves.
- Do not represent sacred places inaccurately.
- No AI-generated final place imagery under current direction.
- Real images must be verified before use.

## Required from user

- Do you have real Nepal images?
- If not, should I source real licensed images later?
- Any place that must not be shown?
