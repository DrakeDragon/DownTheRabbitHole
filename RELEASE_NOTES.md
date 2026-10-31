# Foreground Clarity Edition — release notes

## Obstacle materials

- Added 24 realm palettes for the existing solid-obstacle shapes.
- Added clipped material treatments for wood, porcelain, paper, plants, coral, candy, metal, ice, and stone/ivory.
- Added directional highlights and dark separation from scenery.
- Retained existing obstacle widths, heights, world positions, and collision checks.
- Gear presentation rotates smoothly using its cached material.
- Restyled beam emitters, warning dashes, and active beams without changing their activation or damage rules.
- Added a separation shadow to painted flying enemies.

## Hero visibility

- Retained painted hero frames and animation states.
- Added a fine dark silhouette edge and a soft warm directional rim during gameplay.
- Added soft local shading behind the hero rather than dimming the full environment.
- Reduced post-hit fading from 35% to 72% opacity; intentional ghost/phase transparency remains.
- Retained boss artwork.

## Retained

- 13,600-unit stages and existing pace.
- Stopped completion pages, upgrade choices, and explicit Start Next Stage button.
- 24 painted environments and falling title scene.
- Existing progression, story, modes, rewards, and save key.

## Performance and limits

Material images are cached with a 72-entry limit; the hero contrast layer uses reusable canvases. This is a procedural material and readability pass over existing obstacle shapes, not a replacement set of painted obstacle sprites. Physical-device performance and full-campaign balance still require playtesting.
