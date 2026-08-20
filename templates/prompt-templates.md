# Monochrome Horror Manga Prompt Templates v2

Use the source photo as the visual reference. Preserve its source ratio unless the user explicitly requests a crop. Build the image in this order: solid black masses → reserved paper-white highlights → grouped halftone midtones → localized directional hatching.

## Shared preservation block

```text
Preserve the source photo's recognizable subject identity, facial structure, expression, pose, clothing silhouette, camera angle, perspective, composition, major object placement, background architecture, and all spatial relationships. Preserve every person in a group. Do not add people, dialogue, readable text, injuries, gore, body distortion, new narrative events, copyrighted characters, or symbols.
```

## Default medium-intensity prompt

```text
Transform the provided photo into an original Japanese monochrome psychological-horror manga illustration. First organize the image as a strict four-layer black-and-white value map: controlled solid-black structural masses, a few deliberate paper-white focal highlights, grouped halftone midtone fields, and localized directional crosshatching that follows real form and light. Use imperfect variable-weight ink contours, etched interior lines, selective screentone, restrained paper grain, silent negative space, and quiet psychological pressure. Keep the source aspect ratio and all identity/composition anchors. The result must be an original black-ink horror-manga image, not a specific artist's work or an existing comic panel.

[Shared preservation block]

Avoid all color, pastel accents, glossy oversized eyes, blush, cute or chibi anime aesthetics, smooth cel shading, clean vector fills, painterly rendering, airbrushed gray fog, neon rim light, uniform scratch noise, speech bubbles, captions, title text, logos, gore, extra anatomy, facial drift, beauty retouching, warped perspective, or source-composition drift.
```

## Subtle prompt modifier

```text
Use a low hatching density, clear paper-white breathing room, moderate black masses, sparse grouped screentone, and fine interior contours. Keep the source highly readable; do not flatten it into a generic comic filter.
```

## Intense prompt modifier

```text
Use more decisive structural black masses, denser but still directional crosshatching, layered grouped screentone, and sharper value separation. Increase psychological pressure through negative space, light isolation, and shadow hierarchy only. Do not alter identity, anatomy, pose, object shapes, or the source composition; do not add gore or a new event.
```

## Scene modifiers

| Scene | Add this modifier |
|---|---|
| Portrait | `Keep eyes, face shape, eye spacing, hair silhouette, expression, clothing, and pose exactly recognizable. Use sparse cheek-plane and under-eye hatching, not beauty retouching. Preserve a few white highlights around eyes or glasses rather than giving glossy anime eyes.` |
| Close night portrait | `Preserve the source vertical ratio and close-camera perspective. Keep glasses as crisp geometric ink contours with selective paper-white reflections; make hair and street recession controlled black masses; translate the practical lamp into a compact paper-white glow with halftone falloff; preserve the real street depth and face shape.` |
| Group | `Preserve every person, their spacing, gestures, clothing, and relationship cues; do not merge, omit, add, or rearrange anyone.` |
| Landscape | `Preserve horizon, weather, cloud structure, buildings, and perspective. Translate light into black-mass, paper-white, halftone, and directional-hatching hierarchy; do not invent objects or dramatic events.` |
| Object / collectible | `Preserve silhouette, labels, material, colorway as black-white value structure, and placement; do not reshape, beautify, or add accessories.` |
| Interior / street | `Preserve perspective, architecture, furniture, signs, and non-target objects. Use quiet fields of shadow, selective highlights, and receding directional hatching to create tension without changing the place.` |
