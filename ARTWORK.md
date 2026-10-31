# Encore menu artwork

Generated with the built-in image-generation tool. No CLI/API fallback was used. The generated atlas was inspected, split into four scene tiles, and encoded as WebP for the game. The game's live text, logo typography, controls, characters, boss movement, attack cues, and share-card statistics are rendered by code rather than baked into these menu paintings.

## Included assets

- assets/menu-atlas.webp — complete 2 × 2 source atlas, 1536 × 1024.
- assets/menu-rabbit-hole.webp — title background, 768 × 512.
- assets/menu-guild.webp — Adventure overview and contract artwork, 768 × 512.
- assets/menu-forge.webp — relic workshop artwork, 768 × 512.
- assets/menu-expedition.webp — expedition and travel artwork, 768 × 512.

The four tiles are also embedded inside index.html. The existing assets/social-preview.png remains the website-link preview. The existing boss atlases are preserved and use the improved code animation renderer.

## Generation prompt

Use case: stylized-concept. Asset type: production background atlas for the existing fairy-tale game Down the Rabbit Hole. Create one beautifully painted high-detail 2x2 environment atlas, four equally sized panels edge to edge, each panel a separate wide landscape composition with its own complete scene, no gutters. Overall landscape canvas approx 1536x1024. Upper left: dramatic vertical rabbit-hole well seen looking downward, spiral shelves of books, floating teacups, playing cards and pocket watches circling a distant cyan light; midnight teal shadows, amber lamps, luminous depth, centered spiral opening, no people. Upper right: enchanting Wonderland adventurers' guild hall inside a vast ancient tree, arched windows, gold illuminated maps, quest scrolls and travel trunks, welcoming teal and amber light, rich material detail. Lower left: magical relic workshop, aged brass clockwork, glowing lantern, ornate crown, silver quill and compass on an emerald workbench, delicately glowing runes, cinematic warm amber light. Lower right: breathtaking enchanted expedition landscape, winding luminous trail between giant mushrooms, tiny castle and forest, floating islands and open storybook map in foreground, moonlit turquoise and gold. Cohesive premium hand-painted fantasy game key art, elaborate painterly textures, cinematic lighting, excellent composition. Clear depth and readable large forms. Keep the lower third of each panel relatively dark and simple to accommodate live interface text. No typography, lettering, UI frames, logos, watermarks, characters or people.
