---
name: horror-manga-ink
description: One-click original monochrome psychological-horror manga photo transformation. Use when a user provides an existing photo and wants an unsettling black-ink-on-white-paper treatment that preserves identity, pose, composition, perspective, and ordinary scene facts. Use localized precise pen detail, decisive source-supported black shapes, broad white space, and one existing visual tension cue; do not use to reproduce a named living artist, copyrighted character, existing comic, or specific panel.
---

# Monochrome Horror Manga Ink

Transform a supplied photo into an **original** monochrome psychological-horror manga still. The default is one medium-intensity result built from normal reality, black ink, white paper, precise local observation, and one already-present tension cue.

Do not name, imitate, or recreate a living artist's exact style, a copyrighted comic, character, or panel. Translate such requests into general traits: factual ordinary setting, decisive black ink, broad white space, variable pen line, detailed observation, restrained hatching, and quiet psychological unease.

## Resources

| Resource | Read when | Purpose |
|---|---|---|
| [Visual grammar and safety](references/visual-grammar-and-safety.md) | Before every conversion | Apply identity preservation and safety boundaries |
| [Ordinary world and single tension v3](references/ordinary-world-and-single-tension-v3.md) | Before every prompt | Apply normal reality, source-supported black, white space, detail allocation, portrait, and night-selfie rules |
| [Prompt templates v3](templates/prompt-templates.md) | Writing the image-editing instruction | Select the shared preservation block, v3 base prompt, intensity, and scene modifier |

## Required Workflow

1. **Inspect the ordinary scene.** Identify subject type, source ratio, facial/identity anchors, pose, camera perspective, normal objects, scene structure, and readable text.
2. **Select one existing tension cue.** Choose one source fact to observe too closely: a still gaze, glasses reflection, a narrow recess, one lamp, a hand, an empty corridor, a light edge, or another already-present detail. Do not invent an event.
3. **Lock the source.** Preserve ratio, composition, identity, face shape, expression, hair, clothing, body/hand count, pose, lens perspective, major objects, and background architecture. Preserve every person and relationship in a group.
4. **Allocate ink deliberately.** Keep broad paper-white fields. Use pure black only for source-supported structural shapes. Create gray only with sparse form-following hatching and small line clusters; do not use full-image screentone, dot overlays, gray wash, or universal scratch texture.
5. **Build one prompt.** Read the v3 reference and templates. Use the generic base, the relevant scene modifier, and the shared preservation block. Keep the source ratio unless a crop is explicitly requested.
6. **Transform once.** Use image editing with the supplied photo as reference. Request one original monochrome still; do not create dialogue, captions, a panel border, or extra narrative content.
7. **Run the lightweight check.** Confirm factual scene clarity, recognizable identity, preserved composition, broad white space, structural black, localized detail, and no unwanted new content.
8. **Deliver one image.** State the intensity, the tension cue, and preserved anchors. Do not make extra variants unless asked.

## Intensity Contract

| Level | Visual result | Must not change |
|---|---|---|
| Subtle | Mostly ordinary source scene, broad white breathing room, only a few local pen details | Source identity, composition, and scene facts |
| Medium (default) | Decisive source-supported black shapes, fine selected detail, sparse hatching-gray, one clear tension cue | Source identity, pose, objects, perspective, and scene facts |
| Intense | Stronger black/white imbalance and tighter detail around the same tension cue; ordinary setting remains legible | Identity, anatomy, object shapes, composition, and story facts; no gore or new event |

## Preservation Prompt Block

Always include this instruction in the image-editing prompt:

```text
Preserve the source photo's recognizable subject identity, facial structure, expression, pose, clothing silhouette, camera angle, lens perspective, composition, major object placement, background architecture, and all spatial relationships. Keep the ordinary real-world setting factual and readable. Do not add people, dialogue, readable text, injuries, gore, body distortion, new narrative events, copyrighted characters, or symbols.
```

For portraits, preserve natural eye scale, eye spacing, gaze, mouth, glasses, hair, and close-camera perspective. For groups, preserve every person and their spacing. For landscapes, preserve weather, horizon, buildings, and perspective. For objects, preserve silhouette, label, material, and placement.

## Hard Exclusions

Never create direct imitation of a named living creator, an existing comic, a specific panel, or a copyrighted character. Never add gore, injury, extra anatomy, deformation, a new character, speech bubbles, captions, logos, or invented readable text.

Do not change the photo's crop, aspect ratio, framing, perspective, pose, identity, object arrangement, or scene structure unless the user explicitly asks. Do not produce color. Do not create cute/anime, glossy, pastel, beauty-illustration, painterly, neon, or generic filter drift.

## Quality Gate

| Check | Pass condition |
|---|---|
| Normal reality | The original setting remains ordinary, factual, and readable |
| Ink structure | Broad paper-white space, source-supported black shapes, and sparse form-following hatching replace gray wash, dot blankets, and global texture |
| Tension | One existing source detail carries the unease; no new horror event is added |
| Fidelity | The primary subject and all protected anchors remain recognizable and composition-consistent |
| Safety | No direct creator imitation, copyrighted characters, text, gore, or body distortion appears |
| Scope | Exactly one requested transformation is delivered |

If a critical check fails, correct only that failure with one focused regeneration. Otherwise stop.

## Feedback

Interpret feedback as scene-structure control: more/less white paper, more/less structural black, more/less local pen detail, simplify a background, focus tension on a different existing cue, make the setting more ordinary, or make the single tension cue stronger. Apply it to the current image only unless the user explicitly names a batch or lasting preference.
