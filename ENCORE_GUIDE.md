# Encore Edition

## Boss encounters

Boss stages keep the game's one-tap gravity controls. Watch the next floor or ceiling threat and cross to the open route. Low obstacles now arrive on both surfaces, so remaining on the floor for a whole encounter no longer works. Wider gaps, small obstacle heights and chapter-boundary safety space keep the new rhythm readable.

Patterns have alternating landing threats, an occasional short same-side pair, safe-route treasure, and optional centre treasure. Boss speed is not globally increased. Phase labels divide the encounter into three presentation stages; later threats become only slightly taller. Curiouser settings and existing mode rules continue to apply.

The intent panel names the next route attack. Narrator bubbles stay out of the boss fight view so they do not cover these cues; unlocked story remains available through the existing story systems. Surface labels account for the Looking-Glass reflection.

## Counter stars

A counter star is a gold four-point star inside a rotating square, distinct from normal shinies. It appears in the open route between attacks. Collecting one uses the ordinary pickup system, returns a visible golden strike toward the boss, grants score, and makes the boss recoil as that strike arrives.

Each counter earns rounded score based on `35 × the current score multiplier`. It also grants 0.8% of one stage's distance as boss damage credit. Damage credit is limited to 8% of the stage, even if more stars are collected. The boss can finish a little sooner; the encounter never ends from one counter star. Surviving to the end still works, and stars require no additional attack button or hero unlock.

The boss progress bar includes counter damage. When a fight ends from that credit, the next stage starts at its normal boundary. Damage, counter count, projectiles and animation reactions reset for the next stage. A boss-clear page notes your counter count.

The changes apply to normal boss stages, Boss Rush and Weekly Gauntlet. Date-seeded modes remain deterministic for a matching seed, build and actions. Their exact obstacle layouts change from the previous edition, so scores should not be treated as cross-version leaderboard records.

## Animation and readability

The original boss artwork and four action poses remain the visual foundation. The renderer now crossfades registered poses, adds gentle torso and head motion, coordinates casting accents with attack release, and shows counter recoil after the returning strike. Each boss has a small cadence and colour variation. Poses are fitted within the game area, with breathing room around the hero.

This is animation and playback refinement, not a new set of long hand-drawn sprite sheets. Motion reduction keeps the essential attack poses and readable cues while reducing continuous movement. Enemy and hero artwork, Tea Party contrast, and the established movement systems are preserved.

## Ending screen and fast replay

The ending screen has a fixed bottom action bar with two large buttons:

- **Share My Run:** the prominent gold button; native PNG sharing when supported, with the existing fallbacks.
- **Fall Again:** an equally reachable green button that immediately starts the same type of run, including the chosen expedition.

Both remain visible while the poster, rewards and notes scroll. On very short phone screens the poster may scroll behind the bar, but the two actions remain available. Safe-area padding leaves room for the phone's home indicator. Sharing is optional and replay never depends on sharing.

An additional contract note shows a reward ready to claim or real progress toward a replay-related goal. All previous manual stage-start breaks remain intact: choosing a curio still does not resume play by itself.

## New artwork

The title uses a painted rabbit-hole well. Adventure headers and feature cards use an illustrated guild hall, magical relic workshop, and expedition landscape. These images share the existing midnight teal and antique gold palette. Image data is embedded in index.html, so the game still runs without external image requests. Editable WebP assets are included in assets/. The original generated atlas and prompt are documented in ARTWORK.md.

## Installation and saves

Extract the ZIP and upload the contents to your GitHub Pages root, keeping index.html at the root and including assets/ for the website link-preview image. No build or package manager is needed to play.

The existing save key is unchanged. Adventure progression, contracts, relics, records, and JSON backup/restore remain compatible. An active run is not saved across reloads. Export a backup through Save & Backups when moving between browsers or hosting origins.

## Suggested playtest

Try a boss encounter with your usual hero and difficulty. Check whether the floor/ceiling rhythm is readable and the counter stars feel rewarding. Test the results action bar on your phone, including after scrolling the rewards. The automated checks verify mechanics and layout rules, but real-phone playtesting is still the right way to tune the final difficulty and animation feel.
