---
name: horror-manga-ink
description: One-click monochrome psychological-horror manga photo transformation. Use when a user provides an existing photo and wants an original Japanese black-and-white horror-manga atmosphere with bold ink, crosshatching, screentone, and unsettling mood while preserving identity, pose, composition, and scene facts. Use for portraits, groups, landscapes, interiors, streets, and objects; do not use to reproduce a named living artist, copyrighted character, existing comic, or specific panel.
---

# Monochrome Horror Manga Ink

Transform a supplied photo into an **original** black-and-white psychological-horror manga image. The default is a single medium-intensity result: stark ink contours, crosshatching, screentone, deep shadow masses, paper grain, and quiet unease.

Do not name, imitate, or recreate a living artist's exact style, a copyrighted comic, character, or panel. Translate any such request into general visual traits: black ink, high contrast, dense hatching, halftone texture, uncanny stillness, and psychological tension.

## Resources

| Resource | Read when | Purpose |
|---|---|---|
| [Visual grammar and safety](references/visual-grammar-and-safety.md) | Before every conversion | Apply generic ink vocabulary, identity preservation, and acceptance checks |
| [Value map and line grammar v2](references/value-map-and-line-grammar-v2.md) | Before writing the final prompt | Apply four-layer values, local directional hatching, negative space, anti-drift, and close-night-portrait rules |
| [Prompt templates](templates/prompt-templates.md) | Writing the image-editing instruction | Select the shared preservation block, v2 value-map prompt, intensity, and scene modifier |

## One-Click Workflow

1. **Inspect the source.** Identify subject type, source ratio, facial/identity anchors, pose, composition, lighting, major objects, scene structure, and any readable text.
2. **Lock the source.** Preserve ratio, subject identity, face shape, expression, hairstyle, clothing silhouette, body/hand count, pose, camera angle, perspective, major object placement, and background architecture. Preserve every person and their relationship in a group photo.
3. **Set intensity.** Use **Medium** by default. Use **Subtle** only if the user asks for a lighter ink conversion. Use **Intense** only if the user requests stronger psychological tension. Intensity controls only line density, black masses, screentone, and abstract ink texture.
4. **Build one prompt.** Read the v2 value-map reference and prompt templates. Use the four-layer value system, the generic medium base, the relevant scene modifier, and the shared preservation block. Keep the original aspect ratio unless the user explicitly requests a crop.
5. **Transform once.** Use image editing with the supplied photo as reference. Request an original monochrome ink result; do not generate dialogue, text, a panel border, or extra narrative content.
6. **Run the lightweight check.** Confirm that the result is monochrome, recognizable, ratio-consistent, and free from unwanted new people, objects, readable text, gore, body distortion, or source-composition drift.
7. **Deliver one image.** State the selected intensity and the preserved anchors. Do not make extra variants unless requested.

## Intensity Contract

| Level | Visual result | Must not change |
|---|---|---|
| Subtle | Fine contours, sparse screentone, moderate shadows, low hatching density | Source identity and composition |
| Medium (default) | Clear ink contours, dense hatching in shadows, visible halftone, strong black-white hierarchy | Source identity, pose, objects, perspective, and scene facts |
| Intense | Heavy black masses, elaborate hatching, layered screentone, pronounced abstract ink texture | Identity, anatomy, object shapes, and composition; no gore or new events |

## Preservation Prompt Block

Always include this instruction in the image-editing prompt:

```text
Preserve the source photo's recognizable subject identity, facial structure, expression, pose, clothing silhouette, camera angle, perspective, composition, major object placement, and background architecture. Keep all non-target objects and spatial relationships. Do not add people, dialogue, readable text, injuries, gore, body distortion, new narrative events, copyrighted characters, or symbols.
```

For portraits, protect face shape, eye spacing, expression, hair silhouette, clothing, and pose. For groups, protect every person and their spacing. For landscapes, protect weather, horizon, buildings, and perspective. For collectibles/products, protect silhouette, label, material, and placement.

## Hard Exclusions

Never create direct imitation of a named living creator, an existing comic, a specific panel, or a copyrighted character. Never add gore, injury, extra anatomy, deformity, a new character, speech bubbles, captions, logos, or invented readable text unless separately requested and permitted.

Do not change the photo's crop, aspect ratio, framing, perspective, pose, identity, object arrangement, or scene structure unless the user explicitly asks. Do not produce a color result.

## Quality Gate

| Check | Pass condition |
|---|---|
| Monochrome | The result uses black, white, and grayscale ink treatment only |
| Style | Four-layer values are visible: structural blacks, selective paper-white highlights, grouped halftone midtones, and local form-following hatching. The image avoids cute-anime, pastel, glossy, cel-shaded, painterly, and global-scratch-noise drift |
| Fidelity | The primary subject and all protected anchors remain recognizable and composition-consistent |
| Safety | No direct creator imitation, copyrighted characters, text, gore, or body distortion appears |
| Scope | Exactly one requested transformation is delivered |

If a critical check fails, correct only that failure with one focused regeneration. Otherwise stop.

## Feedback

Interpret feedback as **intensity**, **value map**, or **texture** control: more/less black mass, more/less paper-white breathing room, stronger/weaker hatching, denser/lighter screentone, cleaner/messier linework, stronger/weaker psychological tension, or more/less organic abstract texture. Apply it to the current image only unless the user explicitly names a batch or lasting preference.
