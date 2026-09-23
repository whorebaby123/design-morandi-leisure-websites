# Practical Morandi design tokens

Treat these as starting values, not immutable reproductions of the approved pages. Adapt to content and check actual contrast after changes.

## Color roles and area

- Use roughly 60–70% atmospheric base or pale surface, 20–30% supporting surfaces, and 5–10% accents as a starting visual balance.
- Assign dark structural ink to readable text, borders, active marks, and hard shadows.
- Keep one accent dominant for the primary action; reserve the other for selection or contextual distinction.
- Mix cool and warm pigments deliberately. Do not distribute all accent colors equally or wash the whole interface into undifferentiated grey.
- Use the mode-specific palettes in the two composition references. For a neutral alternative to rose or lavender, try muted clay `#B58B73`, sage `#A3ADA0`, or sand `#C9B995`; recheck text contrast.
- Target 4.5:1 contrast for ordinary text and 3:1 for large text and meaningful controls. Use ink-colored labels on pale pigments; do not assume white works on muted accents.

## Geometry and spacing

- Begin with a 4/8/12/16/24/32/48/64 px spacing scale, and break it only for clear compositional reasons.
- Use square or 2–8 px corner radii for windows and panels; reserve circles for meaningful dials or graphic motifs.
- Give structural panels 1–2 px borders and primary controls 2–3 px borders.
- Use 4–8 px hard offset shadows on primary controls; keep secondary controls quieter.
- Make touch targets at least 44 × 44 px. A pressed control travels into its shadow instead of merely changing opacity.

## Type and responsive behavior

- Choose modern sans-serif typography with reliable Chinese fallback: system-ui, PingFang SC, Microsoft YaHei, sans-serif.
- Start body text at 14–16 px, functional labels at 12–14 px, and display text around clamp(2.5rem, 6vw, 6rem). Adapt to available width and language.
- Apply tight display tracking only to short Latin headings. Keep Chinese text comfortable and avoid forced all-caps styling throughout the interface.
- Define reflow by content fit: collapse desktop overlaps and poster/console columns into a deliberate reading order before text or controls collide.
- Preserve clear keyboard focus, actual button semantics, and reduced-motion behavior. Do not require hovering to reveal essential actions.

## Two-version acceptance

Compare both pages with colors mentally removed. They must differ in silhouette and hierarchy, not just hue. A cold floating-window desktop and a warm poster-plus-console should remain easy to identify in grayscale.

Use task-relevant buttons and navigation. Where there is no audio content, replace transport controls with meaningful primary actions rather than adding a fake radio player.
