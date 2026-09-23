---
name: design-morandi-leisure-websites
description: "Design or restyle personal websites in a modern Morandi leisure-broadcast aesthetic: tactile controls, editorial typography, calm retro-computing atmosphere, and genuinely distinct cool-desktop or warm-console compositions. Use when the user references the approved Stillwater/Afterglow directions, Poolsuite-like leisure mood, Morandi radio interfaces, or asks to continue this specific visual language; do not use for generic Morandi color requests with no leisure, broadcast, or desktop-system intent."
---

# Design Morandi Leisure Websites

Create a personal web space that feels like a private leisure operating system or a beautifully art-directed radio console. Keep the emotional mechanism—escape, broadcasting, tactile controls, suspended time—without copying another product's logo, illustrations, wording, assets, or exact layout.

## Content boundaries

- Start from the current website brief. Do not import account personas, names, lyrics, catchphrases, or narrative lore from unrelated projects unless explicitly requested.
- Use concise factual labels and useful content. Do not invent motivational slogans, self-help copy, simulated social proof, or fake playback capabilities.
- Treat palette and decoration as separate decisions. Low saturation need not mean feminine, cute, pale pink, or delicate. When neutral styling is requested, use mineral blue, sage, sand, ochre, charcoal, and muted clay; omit hearts, bows, flowers, and similar motifs.
- Prefer warm mixed accents when the current brief leaves temperature open, while preserving a clearly cool option when two directions are requested. Do not turn every surface the same beige.
- Keep this skill focused on the approved Morandi leisure language. Do not merge later pixel-desktop, watercolor, or other art directions into it without an explicit request.

## Reference-to-design workflow

1. Read the current brief and identify the page purpose, chosen reference, visual priorities, exclusions, and requested number of versions.
2. If no direction is selected and exploration is requested, find visibly different real website references and give three per style. Clearly distinguish found references from authored work. Once a reference is selected, proceed without restarting broad research.
3. Extract transferable mechanisms: composition, color roles, typography, surface treatment, control hierarchy, and atmosphere. Keep visual similarity intentional without copying identity or assets.
4. Choose a composition, assign color roles, and define the primary action before implementation. Read [Design tokens](references/design-tokens.md) for a practical starting system.
5. Build the requested number of actual reviewable pages. For two versions, use both composition references and change at least four visual dimensions. Prioritize the still frame; add only useful interactions.
6. Apply concrete user feedback to the current deliverable. Preserve confirmed preferences and keep project-specific exclusions scoped appropriately.
7. Only create or revise a reusable skill when requested. Distill the approved result rather than presenting unreviewed experiments as established preferences.

## Choose the composition before implementation

Select the mode from the user's request, existing site, and desired mood:

- **Cool Coast Desktop:** quiet, airy, layered operating-system windows over an abstract coastal field. Read [Cool Coast Desktop](references/cool-coast-desktop.md).
- **Warm Afterglow Console:** bold editorial poster paired with a dense physical broadcast console. Read [Warm Afterglow Console](references/warm-afterglow-console.md).
- When the user requests alternatives or comparison, read both references and make the results differ in composition, density, typography, control geometry, and spatial rhythm—not merely palette.

If the preferred mode is unclear, infer it when the surrounding context is sufficient. Ask only when choosing the wrong mode would materially change the deliverable.

## Shared visual DNA

### Emotional target

The page should feel calm but not delicate, nostalgic but not vintage cosplay, and playful without becoming childish. Favor “private broadcast from a better afternoon” over productivity, luxury, or social-media aesthetics.

### Morandi color system

Use low-saturation, slightly gray pigments. Build each page from:

- one atmospheric base;
- one pale surface;
- one dark structural ink;
- two muted accent pigments;
- optionally one light cream for highlights.

Do not spread accents evenly. Give one accent a clear role such as playback, live state, or selected mode. Maintain readable contrast for text and controls; Morandi does not mean low-contrast UI.

### Typography

Use contemporary grotesk or humanist sans-serif families with strong weight range. Prefer modern system stacks or locally available fonts over fragile external dependencies.

- Display text: tight tracking, confident scale, compact line height, limited to one or two dramatic blocks.
- Interface labels: 12–14 px for functional text; use uppercase and generous tracking only for short Latin labels. Reserve 10–11 px for nonessential decorative metadata; never make tiny text the only action label.
- Supporting copy: generally 14–16 px with 1.5–1.7 line height and plain language. Use a Chinese-capable sans-serif fallback; do not apply tight Latin display tracking to long Chinese text.
- Allow an outlined or italic display phrase only as a singular editorial accent.

Avoid generic retro pixel fonts, faux terminal monospace everywhere, decorative scripts, and indiscriminate all-caps body copy.

### Tactile controls

Primary actions must be visually obvious before hover:

- 2–3 px dark border;
- opaque Morandi accent fill;
- hard offset shadow of 4–8 px using the structural ink;
- strong verb label or unmistakable play symbol;
- minimum touch target of 44 px.

Hover may lift the button 1–2 px and increase its shadow. Pressed state should move into the shadow and collapse it. Use this treatment for primary playback, next/skip, version switching, and one important state action—not every container.

### Surfaces and materials

Use mostly opaque, pigment-like surfaces. Add depth through borders, overlaps, hard shadows, paper grain, subtle translucent status strips, and controlled geometric fields. Thin chrome and tiny labels can suggest software; coarse shadows and physical switches can suggest hardware.

Do not default to blurred glass cards, blue-purple gradients, generic rounded-card grids, or uniformly floating capsules. Rounded corners should be rare and purposeful; circles belong to records, suns, dials, or status indicators.

### Motion and interaction

Interaction may remain light. Prioritize a complete still frame, then add small evidence of life:

- play/pause state;
- track title change;
- record rotation or restrained waveform;
- window focus pulse;
- slow ticker or status clock;
- pressed-button travel.

Keep motion slow enough to preserve leisure. Respect `prefers-reduced-motion`. Never let animation compensate for weak composition.

## Originality and variation rules

- Borrow the design mechanism, not protected identity. Replace names, copy, station numbers, iconography, and scene construction with original decisions.
- Treat each proposed version as a separate art direction. Change at least four of: global composition, density, typography behavior, image/field treatment, component silhouette, border system, shadow language, navigation placement, and motion motif.
- Do not interpret “personal website” as a photo portfolio unless the content requires it. The style works for private dashboards, reading rooms, music pages, travel logs, archives, start pages, and quiet utilities.
- Do not force radio controls into content that has no audio metaphor. Preserve the broader leisure-system language through navigation, status, tactile actions, and art-directed layout.
- Avoid tracing Poolsuite screenshots or recreating its marks. The result should be recognizably adjacent in mood and unmistakably original in execution.

## Implementation checks

Before handoff, verify:

- the primary action is the strongest interactive element;
- muted colors still meet practical contrast needs;
- the page is composed rather than filled with generic cards;
- copy contains no unrelated persona, invented claims, or motivational filler;
- any playback, saving, or live-state claim matches a real implemented behavior;
- mobile reflow preserves hierarchy and does not rely on absolute positioning;
- every visible control has a working state or clear destination;
- all external assets and fonts have reliable fallbacks;
- two requested versions remain distinguishable in grayscale and silhouette, not only in color.
