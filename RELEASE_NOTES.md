# Painted Realms & Longer Stages — release notes

## Upgrade display fix

Curio description functions are now evaluated at the appropriate upgrade level. Cards display readable effect text. The same function-to-text issue is also corrected in curio info dialogs. All 36 curios and their 79 available level descriptions were checked.

## Longer stages

Stage distance increased from 3,400 to 13,600 units. The first stage is roughly a minute at starting speed; later stages and modified runs vary. Enemy speed, character artwork, boss artwork, collision sizes, and hero abilities are retained.

## Explicit stage starts

Completing a stage opens a stopped completion page with summary, story, and upgrade cards. Choosing a card applies it once and highlights it. The player must press Start Next Stage to resume. Multiple Head Start picks stay on the preparation screen and end with Start First Stage. Exhausted upgrade pools still permit continuing. Endless now pauses for manual choices and stage starts; final Gauntlet victory still ends normally.

## Painted environments

24 different painted realm backdrops replace the shared scenery treatment. Added atmosphere, subtle depth movement, particles, foreground materials, and restrained action-area shading. Existing character and boss renderers remain in place. A bounded cache retains up to two decoded world atlases, with upcoming scenes preloaded during upgrade stops.

## Included from previous builds

The falling title, full hero roster, boss roster, companions, movement animation states, animated gallery, narrative, events, quests, rewards, and browser-local save key remain included.

## Current limits

- Longer runs change pacing and reward timing; broad balance and real-phone performance still need playtesting.
- Painted scenery is a backdrop, not new explorable geometry or collision platforms.
- Bosses/enemies retain their existing short painted animation cycles.
- Some generated sprite poses still warrant visual cleanup.
- No cloud save, online leaderboard, service worker, or installable offline/PWA guarantee.
