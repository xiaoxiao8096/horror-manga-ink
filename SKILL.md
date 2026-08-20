---
name: horror-manga-ink
description: Redraw a supplied photo as one original monochrome psychological-horror manga illustration. Use when a user wants their recognizable identity and ordinary setting retained but needs the photograph re-authored into a unified black-ink comic world—not a pencil sketch, photo trace, line filter, or photorealistic ink portrait. Do not use to reproduce a named living artist, copyrighted character, existing comic, or specific panel.
---

# Monochrome Horror Manga Ink

Turn one photo into one **original, unified black-and-white comic illustration**. Preserve who and where the source depicts, but redraw the photographic surface into coherent manga graphics. The default result must read as a drawn image at first glance, never as a photograph covered with pen effects.

Do not name, imitate, or recreate a living artist's exact style, a copyrighted comic, character, or panel. Translate such requests into general traits: deliberate black-white grouping, crisp contour, drawn character identity, designed environment, controlled texture, ordinary reality, and psychological unease.

## Resources

| Resource | Read when | Purpose |
|---|---|---|
| [Visual grammar and safety](references/visual-grammar-and-safety.md) | Before every conversion | Apply identity preservation and safety boundaries |
| [Identity-anchor redraw v6](references/identity-anchor-redraw-v6.md) | Before every prompt | Separate hard anchors from photo surfaces and apply the anti-sketch gate |
| [Prompt templates v6](templates/prompt-templates.md) | Writing the image-editing instruction | Select the anchor lock, redraw base, intensity, and scene modifier |

## Required Workflow

1. **Inspect the source.** Identify hard identity and scene anchors: face proportions, glasses/accessories, hair silhouette, expression, clothing, framing, lens viewpoint, primary objects, spatial direction, and main location.
2. **Separate anchors from surfaces.** Lock hard anchors. Mark all soft photo surfaces for redraw: pores, lens blur, digital noise, literal gradients, individual hair strands, tiny reflection fragments, incidental clutter, and minor edge detail.
3. **Plan the redraw.** Rebuild person and setting through the same graphic system. Simplify the face into clear planes; group hair into coherent shape clusters; select essential architecture, pavement, vehicle, tree, lamp, and recess shapes; omit incidental photographic clutter.
4. **Allocate graphic layers.** Use crisp black contours/fill shapes, selected controlled pen texture, and clean paper-white fields. Ensure every person and object uses compatible line weight, black-white grouping, and texture logic.
5. **Build one prompt.** Read the v6 redraw reference and templates. Use the generic redraw base, the relevant scene modifier, and the shared anchor lock. Keep the source ratio unless a crop is explicitly requested.
6. **Transform once.** Use image editing with the supplied photo as reference. Request one complete monochrome redraw; do not create panels, captions, dialogue, or extra narrative content unless explicitly requested.
7. **Run the anti-sketch gate.** Reject the result if it reads as pencil, charcoal, photo trace, photorealistic ink, a line filter, or a visible photograph beneath hatching. Regenerate once with the redraw constraint focused on that failure.
8. **Deliver one image.** State preserved anchors and the redraw choice. Do not make extra variants unless asked.

## Intensity Contract

| Level | Visual result | Must not change |
|---|---|---|
| Subtle | Clear graphic redraw with simplified planes, restrained texture, and quiet white space | Hard identity, framing, and scene anchors |
| Medium (default) | Fully unified drawn person and environment, deliberate black shapes, controlled texture, and ordinary unease | Hard identity, composition, perspective, and location anchors |
| Intense | Stronger graphic contrast and selective texture while remaining a coherent redraw, not a textured photo | Hard identity, anatomy, object placement, scene anchors, and no new event |

## Shared Anchor Lock

Always include this instruction in the image-editing prompt:

```text
Preserve only the source photo's hard anchors: recognizable facial proportions, glasses/accessories, hairstyle silhouette, expression, clothing silhouette, framing, lens viewpoint, primary object placement, spatial direction, and real-world setting. Redraw all photographic surfaces into one consistent black-ink comic world. Do not add people, readable text, injuries, gore, body distortion, new narrative events, copyrighted characters, or symbols.
```

For portraits, hard anchors include face proportions, glasses, hair silhouette, eye spacing, nose/mouth relationship, expression, and clothing. For groups, preserve each person's identity anchors and spacing. For environments, preserve location direction, architecture/landscape structures, practical lights, and primary object positions.

## Hard Exclusions

Never create direct imitation of a named living creator, existing comic, specific panel, or copyrighted character. Never add gore, injury, extra anatomy, deformation, a new character, speech bubbles, captions, logos, or invented readable text.

Do not output pencil sketch, charcoal sketch, photorealistic ink portrait, pen trace, line filter, every-pore detail, photo skin texture, lens artifacts, universal crosshatching, full-image screentone, dot overlay, gray wash, generic grain, color, cute anime drift, glossy/anime eyes, beauty-retouched face, polished action-hero anatomy, cinematic poster light, panel borders, or a photographic base visible beneath ink.

## Quality Gate

| Check | Pass condition |
|---|---|
| Redraw | The image reads as a unified original comic illustration at first glance; no photo-sketch or line-filter base remains visible |
| Identity | Face proportions, accessories, hair silhouette, expression, clothing, and source viewpoint remain recognizable |
| Scene | Major location, perspective, lights, primary objects, and spatial direction remain recognizable but are graphically re-authored |
| Unity | Person and environment share one contour, black-fill, texture, and white-space system |
| Scope | No panel layout, dialogue, text, gore, new character, new event, or copied creator/page/character appears unless separately requested and permitted |

If a critical check fails, correct only the single most important failure with one focused regeneration. Otherwise stop.

## Feedback

Interpret feedback as redraw control: make the result more/less graphic, simplify face planes, redraw the street more aggressively, preserve a specific identity anchor, reduce/remove photo texture, make black shapes more decisive, use fewer/more controlled texture fields, or make person and environment feel more stylistically unified. Apply feedback only to the current image unless the user explicitly names a batch or lasting preference.
