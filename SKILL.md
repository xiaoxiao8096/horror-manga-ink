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
| [Environment-first ink v5](references/environment-first-ink-v5.md) | Before every prompt | Apply ordinary environment priority, material-specific marks, unglamorous portrait handling, and anti-action-manga constraints |
| [Prompt templates v5](templates/prompt-templates.md) | Writing the image-editing instruction | Select the shared preservation block, environment-first base prompt, intensity, and scene modifier |

## Required Workflow

1. **Inspect the ordinary scene.** Identify subject type, source ratio, facial/identity anchors, pose, camera perspective, normal objects, scene structure, and readable text.
2. **Identify the material hierarchy.** Treat the person as part of the ordinary location. List environment anchors and source-supported material transitions—wall/shutter, road, vehicle, tree, lamp, cable, doorway, recess, reflection—before selecting one existing detail to observe too closely. Do not invent an event.
3. **Lock the source.** Preserve ratio, composition, identity, face shape, expression, hair, clothing, body/hand count, pose, lens perspective, major objects, and background architecture. Preserve every person and relationship in a group.
4. **Allocate ink by environment first.** Keep broad paper-white fields and make the ordinary place carry meaningful visual weight. Use black only for source-supported recesses, clothing interiors, uneven hair clumps, and genuine shadows. Create gray with small irregular material-following line clusters; do not use full-image screentone, dot overlays, gray wash, universal scratch texture, or polished long contour hatching.
5. **Build one prompt.** Read the v5 environment-first reference and templates. Use the generic base, relevant scene modifier, material anchors, and shared preservation block. Keep the source ratio unless a crop is explicitly requested.
6. **Transform once.** Use image editing with the supplied photo as reference. Request one original monochrome still; do not create dialogue, captions, a panel border, or extra narrative content.
7. **Run the lightweight check.** Confirm factual scene clarity, recognizable identity, preserved composition, broad white space, structural black, localized detail, and no unwanted new content.
8. **Deliver one image.** State the intensity, the tension cue, and preserved anchors. Do not make extra variants unless asked.

## Intensity Contract

| Level | Visual result | Must not change |
|---|---|---|
| Subtle | Mostly ordinary source scene, broad white breathing room, only a few local pen details | Source identity, composition, and scene facts |
| Medium (default) | Ordinary place and source materials share visual weight with the person; irregular local detail and sparse hatching make normal surfaces quietly uncomfortable | Source identity, pose, objects, perspective, materials, and scene facts |
| Intense | Stronger black/white imbalance and tighter detail around the same tension cue; ordinary setting remains legible | Identity, anatomy, object shapes, composition, and story facts; no gore or new event |

## Preservation Prompt Block

Always include this instruction in the image-editing prompt:

```text
Preserve the source photo's recognizable subject identity, facial structure, expression, pose, clothing silhouette, camera angle, lens perspective, composition, major object placement, background architecture, and all spatial relationships. Keep the ordinary real-world setting factual and readable. Do not add people, dialogue, readable text, injuries, gore, body distortion, new narrative events, copyrighted characters, or symbols.
```

For portraits, preserve natural eye scale, eye spacing, gaze, mouth, glasses, hair, and close-camera perspective. For groups, preserve every person and their spacing. For landscapes, preserve weather, horizon, buildings, and perspective. For objects, preserve silhouette, label, material, and placement.

## Hard Exclusions

Never create direct imitation of a named living creator, an existing comic, a specific panel, or a copyrighted character. Never add gore, injury, extra anatomy, deformation, a new character, speech bubbles, captions, logos, or invented readable text.

Do not change the photo's crop, aspect ratio, framing, perspective, pose, identity, object arrangement, materials, or scene structure unless the user explicitly asks. Do not produce color. Do not create cute/anime, glossy, pastel, beauty-illustration, painterly, neon, generic filter, heroic action-portrait, polished-anatomy, dramatic-action-shadow, or poster-like drift.

## Quality Gate

| Check | Pass condition |
|---|---|
| Normal reality | The original setting remains ordinary, factual, and readable |
| Ink structure | Ordinary environment materials carry meaningful visual weight through source-supported black, quiet white space, and irregular local marks; gray wash, dot blankets, polished long hatching, and global texture are absent |
| Portrait treatment | The person remains factual and unglamorous: natural eye scale, source asymmetry, real hair clumps/flyaways, and no heroic lighting or beauty smoothing |
| Tension | Normal materials and one existing detail carry the unease; no new horror event is added |
| Fidelity | The primary subject and all protected anchors remain recognizable and composition-consistent |
| Safety | No direct creator imitation, copyrighted characters, text, gore, or body distortion appears |
| Scope | Exactly one requested transformation is delivered |

If a critical check fails, correct only that failure with one focused regeneration. Otherwise stop.

## Feedback

Interpret feedback as environment-versus-person control: more/less environment detail, more/less face emphasis, dirtier/cleaner material observation, rougher/smoother wall or pavement marks, more/less visual weight for the lamp/recess/vehicle/tree, more/less white space, or less action-manga polish. Apply it to the current image only unless the user explicitly names a batch or lasting preference.
