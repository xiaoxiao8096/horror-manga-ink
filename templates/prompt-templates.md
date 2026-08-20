# Identity-Anchor Manga Redraw Prompt Templates v6

Use the supplied photo only as a source of identity, composition, and scene anchors. Preserve its original aspect ratio and overall framing unless the user explicitly asks for a crop. Render one original monochrome psychological-horror manga illustration; do not emulate a named living artist, copyrighted character, published page, or specific comic.

## Shared Anchor Lock

```text
Preserve only the photo's hard anchors: recognizable facial proportions, glasses shape, hairstyle silhouette, neutral expression, clothing silhouette, source framing, close-camera lens viewpoint, street direction, building/vehicle/lamp placement, and overall real-world setting. Redraw all photographic surfaces into one consistent black-ink comic world. Do not add people, dialogue, readable text, injuries, gore, body distortion, new events, copyrighted characters, or symbols.
```

## Default Medium Redraw Prompt

```text
Redraw the provided photo as one original monochrome psychological-horror manga illustration, not as a sketch, trace, filter, or photorealistic ink portrait. Use the source only for hard identity and scene anchors. Rebuild the face, hair, glasses, shirt, road, vehicle, buildings, tree, lamp, pavement, and dark recesses into one coherent graphic system of crisp black contours, deliberate black fill shapes, selected controlled pen texture, and clean paper-white fields.

Keep the person recognizable through face proportions, glasses, hair silhouette, eye spacing, nose/mouth relationship, neutral expression, clothing, and close-camera viewpoint. Simplify facial skin into a few clear drawn planes; remove pores, lens blur, photo noise, tiny reflection fragments, and literal photographic gradient shading. Group hair into drawn black/gray shape clusters rather than preserving individual photographic strands. Redraw the environment as a designed ink setting: preserve only key architecture planes, pavement direction, vehicle silhouette, practical lamp, tree mass, shutter/doorway, and recesses. Remove incidental clutter and make person and environment use the same line weight, black-white grouping, and texture logic.

[Shared Anchor Lock]

Avoid pencil sketch, charcoal sketch, photorealistic ink, pen trace, every-pore detail, photographic skin texture, lens artifacts, crosshatching over every surface, full-image screentone, dot overlay, gray wash, generic grain, glossy/anime eyes, cute styling, polished action-hero anatomy, cinematic poster lighting, color, panel borders, frames, dialogue, captions, logos, gore, extra anatomy, altered identity anchors, or imitation of a specific artist, comic, character, or published page.
```

## Subtle Redraw Modifier

```text
Keep the illustration spare and graphic: fewer texture fields, simple facial planes, clear object silhouettes, quiet white space, and only selected pen texture. It must still look fully drawn, never like a filtered photo.
```

## Intense Redraw Modifier

```text
Increase ink-shape contrast and selected material texture, but retain graphic simplification. Make the ordinary scene more visually uncomfortable through deliberate redraw choices; do not reintroduce photographic detail, action-poster drama, or a new event.
```

## Scene Modifiers

| Scene | Add this modifier |
|---|---|
| Portrait | `Use face proportions, glasses, hair silhouette, eye spacing, and expression as hard identity anchors. Render the face as a simplified drawn character with a few strong planes and small line accents; do not trace skin pores, lens blur, or every facial shadow.` |
| Close night portrait | `Keep the vertical framing, close camera viewpoint, same glasses, hair, dark shirt, street direction, lamp placement, vehicle/buildings, and road depth. Redraw the street as coherent ink architecture with a few deliberate planes and silhouettes. Redraw the face and street with one unified graphic language; do not keep photographic night gradients or facial microtexture.` |
| Group | `Keep each person's identity anchors, clothing, spacing, and relation. Redraw all people and the environment in one consistent graphic system; do not preserve photo surfaces or merge identities.` |
| Landscape | `Keep horizon, weather, buildings, road, and perspective anchors. Redraw the location through designed black/white shapes and selected ink texture; do not trace every photographic branch, cloud, or surface.` |
| Object / collectible | `Keep silhouette, labels, material identity, and placement. Redraw the object as a coherent ink object using decisive shape groups; do not trace reflections, noise, or every surface imperfection.` |
| Interior / street | `Keep real architecture, furniture/vehicles, room or street direction, and main lights. Rebuild the scene using selected planes, silhouettes, and controlled ink texture; omit incidental photo clutter and avoid a simple line-filter result.` |
