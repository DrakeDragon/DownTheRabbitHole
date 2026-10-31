# Down the Rabbit Hole

## A fairy-tale gravity-flip runner with roguelite progression

Fall into a world where fairy tales share the same impossible rabbit hole. Flip gravity to run along the floor or ceiling, slip past flying clocks and enchanted hazards, collect shinies, and choose curios that change your next attempt. Every run builds toward new heroes, companions, upgrades, cosmetics, and more of the story.

**Adventure Edition — GitHub Pages release package**

This is a complete, self-contained playable browser build. The game, styles, story, synthesized audio, and embedded sprite artwork are inside `index.html`. No installation, account, backend, API key, package manager, or build command is required to play or host it.

> Upload the EXTRACTED files in this ZIP to your repository. Keep `index.html` at the root of the branch/folder used by GitHub Pages. Uploading the ZIP alone does not publish the game.

## Contents

- [Story and tone](#story-and-tone)
- [How the game plays](#how-the-game-plays)
- [Controls](#controls)
- [Heroes and companions](#heroes-and-companions)
- [Worlds and bosses](#worlds-and-bosses)
- [Adventure expansion](#adventure-expansion)
- [Progression and replay](#progression-and-replay)
- [Modes and recurring activities](#modes-and-recurring-activities)
- [Artwork and animation](#artwork-and-animation)
- [Menus and accessibility](#menus-and-accessibility)
- [Play locally](#play-locally)
- [Publish on GitHub Pages](#publish-on-github-pages)
- [Saves and privacy](#saves-and-privacy)
- [Troubleshooting](#troubleshooting)
- [Release contents and development](#release-contents-and-development)
- [Validation and current limits](#validation-and-current-limits)

## Story and tone

Your chosen hero falls into a rabbit hole lined with books whose pages have gone blank. A grinning Cat appears, offering commentary that is rarely helpful and usually accurate. The fall becomes a journey through Wonderland, neighboring fairy tales, strange castles, and stories that seem aware someone is reading them.

The embedded narrative, **The Book of Falling**, unfolds through chapters and repeated runs. Its first volume follows the mysteries of the missing words, the Author, and the story itself. Later material turns toward an unwanted sequel and a shared universe pushed by marketing and publishing. Expect self-aware fairy-tale humor, sarcastic companions, familiar literary characters in new situations, and jokes about heroes who would very much prefer a quieter afternoon.

Story fragments also belong to individual realms. Revisit places to reveal more of their entries, browse unlocked writing in the Book menu, and build a record of the creatures and curios you encounter. The central narrative advances through play; it is not a branching dialogue adventure or an open-world platformer.

## How the game plays

1. Select an unlocked hero and, if available, a companion.
2. Choose your Curiouser difficulty and start a run with **Fall In**.
3. Your hero moves forward automatically. Tap to reverse gravity between the floor and ceiling.
4. Avoid solid hazards, flying enemies, and beams while collecting shinies.
5. Use limited airborne flips and any abilities supplied by your hero, companion, or current curios.
6. Complete a stage and stop on its completion page. Read its story and summary, then choose a curio. Defensive items, projectiles, magnets, score bonuses, and special effects can change your approach.
7. Your selection is applied once and highlighted. The game stays stopped until you press **Start Next Stage**; selecting an upgrade alone never resumes the run.
8. Face boss-themed obstacle patterns, build close-call combos, and push farther into the tale.
9. After a run, spend earned shards, improve your roster, claim available rewards, and try another combination.

Timing, positioning, and gravity are the core of the game. Attacks such as card volleys are triggered by abilities and flips rather than a separate manual combat button. Boss encounters are runner challenges with boss-specific hazard patterns, rather than conventional arena fights with a dedicated melee combat system.

## Controls

| Action | Touch / mouse | Keyboard |
| --- | --- | --- |
| Flip gravity during a run | Tap / click the playfield | Space, Up Arrow, or W |
| Pause or resume | Pause button | P or Escape during play/pause |
| Start from the title screen | Fall In | Enter |
| Retry after a run | Fall Again | Focus and activate Fall Again, or Enter with the page focused |
| Start the next stage | Select an upgrade, then Start Next Stage | Focus and activate the start button |
| Choose a curio, hero, or menu item | Tap / click the button | Tab to focus, then activate |
| Close a dialog | Return / close button | Escape |
| Inspect an animation | Open the animated collection; choose a movement | Use focused preview controls |

The game supports limited midair flips; available charges depend on the build. Tapping does not grant unlimited airborne direction changes. Buttons and menus handle their own input so selecting them does not also trigger a playfield flip.

## Heroes and companions

### 36 playable heroes

Heroes have different starting passives. Unlock them with in-game progression, gain hero experience, and explore combinations with companions and curios. The following descriptions are taken from the build's hero data.

| Hero | Passive |
| --- | --- |
| Alice | Curiouser: 1 free reroll of Curio choices each run. |
| Red Riding Hood | Basket of Goodies: shinies are worth +30%. |
| Gretel | Oven Trick: survive the first hit each run and burn everything nearby. |
| Puss in Boots | Seven-League Boots: +1 mid-air flip and snappier flips. |
| Jack | Beanstalk Dash: every 7th flip launches a smashing dash. |
| Thumbelina | Teeny Tiny: your hitbox is 30% smaller. |
| Pinocchio | Wooden Darts: start with Card Volley. Every 25 shinies, +1 card (max 4). |
| Little Mermaid | Sea Legs: lighter gravity, shinies drift to you, +10% shinies. |
| Snow White | Forest Friends: a free Tea Cozy each chapter and birds that gather shinies. |
| Cinderella | Midnight Chime: every 12th flip makes you a ghost for 1.2s. |
| Aladdin | Three Wishes: Curio choices show 4 options, plus 1 extra reroll. |
| Dorothy | Ruby Slippers: cheat death once per run. |
| Peter Pan | Never Grow Up: +1 mid-air flip and 8% lighter gravity. Hates adulthood and taxes. |
| Robin Hood | Merry Aim: start with 2 Card Volley. Steals from the rich spikes, gives to the poor you. |
| Mowgli | Bare Necessities: shinies drift to you, +15% shinies, hitbox 10% smaller. |
| Rapunzel | Long Hair, Do Care: every 9th flip is a dash. Whips hazards with her braid. |
| Sleeping Beauty | Beauty Sleep: +1 Tea Cozy each chapter and the world runs 5% slower. |
| Goldilocks | Just Right: +25% score and +10% shinies. Not too hot, not too cold. |
| King Arthur | Sword in the Stone: free Oven Trick each run and +10% score. Round table optional. |
| Ichabod Crane | Spooked Sprint: every 5th flip you turn ghostly for 0.6s. Very jumpy. |
| The Scarecrow | If I Only Had A Brain: +2 Curio rerolls. Brains not included. |
| The Tin Man | Heart Of Tin: +2 Tea Cozies per chapter, but the world is 5% faster. Needs oil. |
| Cowardly Lion | Courage!: Close Calls count +1 extra. Screams a lot. Brave in spite of it. |
| The Frog Prince | Royal Luck: Curio rarity odds +30%. Please do not kiss him. |
| Sherlock Holmes | Elementary: combos last 2s longer and score +10%. Notices everything except the spikes. |
| Sinbad | Seven Voyages: shinies +20% and drift to you. Has been shipwrecked six times. Is thriving. |
| Ali Baba | Open Sesame: +1 Tea Cozy each chapter and shinies +10%. Forty thieves not included. |
| Belle | Beastly Friend: +1 Tea Cozy each chapter and spikes are 8% shorter. Reads a lot. |
| Peter Rabbit | Carrot Dash: every 6th flip is a dash. Has a strong opinion about lettuce. |
| Tom Sawyer | Fence Painter: +1 Curio reroll and +10% shards. Got everyone else to do the work. |
| Gulliver | Big Steps: score +15% and the world is 6% slower. Everything is tiny. Everything is fine. |
| Momotaro | Peach Power: starts with Card Volley, shinies +10%, hitbox 8% smaller. Born from a peach. Moves on. |
| Anansi | Trickster: every 6th flip you ghost through hazards for 0.8s and gain +1 reroll. |
| The Mad Hatter | Hat Trick: every 3rd flip drops a shiny. Hates punctuation. Loves tea. |
| The March Hare | March Madness: score +35% and shinies +20%, but the world is 10% faster. Mad as a... hare. |
| The Cheshire Cat | Grin & Bear It: every 7th flip you fade through everything for 1s, and your hitbox is 10% smaller. |

### Six companions

| Companion | Benefit |
| --- | --- |
| White Rabbit | Score bonus |
| Dormouse | Slows the world |
| Mock Turtle | Additional Tea Cozy protection |
| Bill the Lizard | An extra airborne flip |
| Caterpillar | Brief ghosting after a flip |
| Cheshire Kitten | Attracts shinies and improves their value |

Companions accompany the hero with animated artwork. The roster also includes unlockable costumes, trails, hats, and titles; availability depends on progression and rewards.

## Worlds and bosses

### 24 realm definitions

The game cycles through a broad collection of fairy-tale and literary settings. These definitions supply names, hazards, music associations, and story/codex entries. Each of these 24 realms now has its own painted backdrop, with atmospheric shading, subtle depth movement, particles, and foreground details. Background art sits behind the existing gameplay actors and hazards.

1. The Rabbit Hole
2. The Tea Party Table
3. The Card Garden
4. The Queen's Court
5. The Looking-Glass World
6. The Jabberwock's Cave
7. The Gingerbread Forest
8. Beanstalk Heights
9. The Enchanted Ocean
10. Baba Yaga's Swamp
11. The Emerald Road
12. The Cave of Wonders
13. Neverland Lagoon
14. Sherwood Forest
15. Hamelin Town
16. The Snow Queen's Palace
17. Sleepy Hollow
18. Camelot
19. Treasure Island
20. The Jungle Book
21. Briar Rose Castle
22. Carpathian Castle
23. Frankenstein's Laboratory
24. The Land of Nonsense

### 22 bosses

The Queen of Hearts, The Beanstalk Giant, The Sorcerer of the Cave, The Jabberwock, The Big Bad Wolf, Captain Hook, The Pied Piper, The Snow Queen, The Headless Horseman, Baba Yaga, Count Dracula, Frankenstein's Monster, The Red Queen, Rumpelstiltskin, The Wicked Witch, Professor Moriarty, Long John Silver, Bluebeard, Medusa, The Kraken, Grendel, The Unwriter.

In the normal run structure, boss encounters occur every fourth chapter. Their weighted obstacle patterns alter what the runner must survive. Boss Rush and the Gauntlet change the encounter sequence. Boss artwork includes preparation, casting/attack, and recovery poses.

## Longer stages and upgrade stops

Stages now cover **13,600 distance units**, four times the previous 3,400. At normal starting speed, the opening stage takes approximately **55–57 seconds** rather than about 14 seconds. Later stages are faster, and hero abilities, mutators, slowing effects, and dashes change actual duration. Longer stages also require longer survival before the next upgrade; this is a pacing change, not a fixed timer.

At completion, the game pauses on a dedicated page showing time, shinies earned, story, and upgrade choices. Upgrade descriptions show the effect at the next level rather than JavaScript function text. Select one card to apply it once, review your build, and press **Start Next Stage** when ready. Initial Head Start upgrades also wait for **Start First Stage** after the required picks. If no upgrades remain, the start button is available without a choice. Endless Descent now follows this explicit stop-and-start flow too. The final Gauntlet victory still ends its mode normally.

## Adventure expansion

The Adventure Hub connects the existing roster and twenty-four realms to new permanent goals and build choices. Open it from the title screen or the **Adventure** navigation button. Seasonal Events remain available through the title event banner and inside the hub.

- **Realm Atlas:** inspect painted realm previews and earn five mastery stamps in each of the twenty-four realms: one clear, sixty collected shinies across clears, one clean clear, three clears, and five clears. That is **120 stamps**, each claimable once for two wonder essence and twenty-five shards. A shield, emergency blast, or revival being spent counts as a hit, so a protected collision does not qualify as clean.
- **Forty permanent contracts:** eight goal families with five tiers each track runs, shinies, flips, cleared stages, bosses, hero ownership, close calls, and deepest stage. Existing lifetime totals count immediately; the new stage-clear total starts with this edition. Goals have no deadline and each tier has its own Claim button.
- **Relic Forge:** craft twelve relics, improve each through three ranks, and equip any two. Spend wonder essence and shards to improve pickup range, shiny rewards, score, reaction time, collision size, gravity, dashes, shields, rerolls, emergency blasts, combo duration, or run shards. Crafting never auto-equips a relic. Equipped ranks are captured when a run starts.
- **Four expeditions:** choose a three-, six-, twelve-, or twenty-four-stage journey with a proper victory screen. The Tea Trail ends after Stage 3, before the first boss. First clears give larger rewards; repeat clears remain worthwhile. Expeditions use the existing realm order, full stage lengths, and manual upgrade breaks.
- **Run Records:** retain the latest thirty completed runs, including hero, mode, actual score, reached and cleared stages, shinies, bosses, duration, and victory status.
- **Portable saves:** export a JSON backup, preview an import, and explicitly restore it. Backups include progression, collections, relics, mastery, contracts, and recent records. They do not include an active run or the optional public sharing URL override.

Wonder essence is earned from cleared stages (one normally, three for a boss stage), contract claims, mastery claims, and expedition victories. Relics apply in Story, Endless, and Expeditions. Daily Tale, Boss Rush, and Weekly Gauntlet retain their existing rules and do not apply relic bonuses. This edition adds goals and systems to the existing worlds; it does not add a new set of realm paintings or character atlases.

See [EXPANSION_GUIDE.md](EXPANSION_GUIDE.md) for costs, effects, exact expedition rewards, and save-transfer steps.

## Progression and replay

- **Shinies and shards:** collect shinies during runs and earn persistent rewards for upgrades and unlocks.
- **Curios:** choose temporary run upgrades with different rarities and stacking limits. Rerolls and hero passives affect choices.
- **Permanent upgrades:** improve shiny value, rerolls, starting protection, opening curios, gravity strength, experience, rewards, and chest chances.
- **Hero experience:** develop individual heroes and unlock their available costume progression.
- **Curiouser difficulty:** climb ten unlockable difficulty levels. Clear Chapter 10 at your highest unlocked level to advance the difficulty ladder.
- **Close-call combos:** risky near misses add score and interact with certain builds.
- **Chests:** earn rewards such as shards, experience, and collection unlocks.
- **Awards and titles:** pursue achievements and equip earned titles.
- **Codex and story:** discover hazards, curios, realms, bosses, and narrative entries.
- **Lifetime statistics:** track runs, best score, deepest chapter, flips, shinies, close calls, and more.

There are no real-money purchases or checkout flows in this build. All shop actions use in-game progression.

## Modes and recurring activities

| Activity | What it does | Availability / goal |
| --- | --- | --- |
| Standard run | Chapter progression with curio choices and recurring bosses | Available from the title |
| Daily Tale | A date-seeded challenge with mutators | Reach Chapter 3 for its daily prize |
| Endless Descent | Continuing speed progression, with manual upgrades and stage starts | Unlock by reaching Chapter 5 |
| Boss Rush | A boss challenge every chapter with increased rewards | Unlock after three boss victories |
| Weekly Gauntlet | A seeded five-boss sequence and mutator | Unlock after three boss victories; milestone rewards at three and five |
| Daily quests | Three rotating objectives and claimable rewards | Completing all three awards a Silver chest |
| Visit streak | A seven-day reward sequence | Claim available visit rewards |
| Wheel of Whimsy | A free daily reward spin | Once per local date |
| Seasonal event | Tokens, reward tiers, and a themed hat | A 52-event annual rotation |

Daily and weekly activities are calculated locally from date-based rules. Matching seeds are not an online competition service: this release has no server-enforced timing or shared leaderboard. Browser date settings and local progression affect these activities.

## Branded run cards and sharing

The ending screen now centers a **1080 × 1350 portrait run card** rather than a plain score display. The card includes the Down the Rabbit Hole wordmark, realm artwork, the selected hero, score, stage reached, gravity flips, shinies, bosses, applicable best-result badges, and a "How far can you fall?" invitation. "Stage reached" describes the stage visited, not a claim that the last stage was completed. Shard and XP rewards remain visible below the main result actions.

- **Share My Run:** shares the PNG and invitation through the browser's native share interface when file sharing is supported. Text sharing or copy-invite fallback is used where appropriate.
- **Save Image:** exports the prepared PNG for posting manually. Some mobile browsers open the image rather than immediately downloading it.
- **Copy Invite:** copies a branded challenge message and public play link. If clipboard access is unavailable, a selectable text dialog is provided.
- **Play Link:** uses the current public game URL automatically, or lets the player set a public address when playing a downloaded/local copy. Local development addresses are not included in invitations. URL query strings and fragments are omitted.
- **Fall Again:** explicitly starts another run. Tapping or scrolling the result panel no longer automatically restarts the game.

The package also includes `assets/social-preview.png`, a **1200 × 630** branded website preview, and social metadata in the HTML. Upload the assets folder with the release. For the most reliable link previews, replace the metadata's relative image addresses with the deployed absolute URL as explained in [SHARING_GUIDE.md](SHARING_GUIDE.md). Social platforms cache previews and do not all interpret metadata or native image captions identically.

PNG generation happens locally in the browser. The game does not upload the card to a server. A player chooses whether and where to share it using their own browser/device controls. Native sharing availability, target apps, and clipboard permissions depend on browser and device support; this release does not guarantee identical behavior on every phone.

## Artwork and animation

### Obstacles and foreground clarity

The existing obstacle silhouettes now use material and color treatments selected for each realm: wood grain, porcelain, paper, foliage, metal, ivory/stone, candy, coral, and ice. Directional highlights and dark separation edges help active obstacles read against the painted scenery. Beam emitters and warnings use coordinated colors with a bright active core. Flying enemies have a subtle separation shadow.

The hero receives a fine dark silhouette edge, a warm directional rim, and soft local background shading. The ceiling route now gets a stronger rim and additional local shading as the hero approaches it, with extra strength in the Tea Party realm. The underlying painted character frames and movement poses are retained. Brief post-hit blinking now fades to 72% opacity rather than 35%, helping the player keep track of the hero; intentional ghost/phase transparency remains. Boss artwork is retained.

This pass changes presentation, not obstacle sizes, collision rules, stage length, or the stopped upgrade/next-stage flow. Cached obstacle materials are bounded to 72 entries to limit memory growth.

### Falling title screen

Alice descends through a vertical rabbit-hole shaft on the title screen. Stonework, books, playing cards, pocket watches, dust, and light streaks move upward at different speeds. A fixed airborne pose with gentle continuous drift and rotation replaces rapid title pose cycling, reducing jitter. The scene respects reduced motion and uses existing embedded artwork. Hero selection and the playable run retain their existing behavior.


This edition uses embedded, AI-generated painted sprite artwork and a custom Canvas animation renderer. The interface uses midnight blue, antique gold, illustrated scenery, and readable panels.

- Six embedded environment atlases provide 24 different painted realm backdrops. The renderer retains at most two decoded world atlases and preloads the next realm at an upgrade stop.
- Artwork covers all 36 heroes, 22 bosses, 12 animated enemy types, and six companions. Arrows and solid environmental hazards retain code-rendered visuals.
- New hero movement artwork supplies takeoff, airborne, falling, landing, and recovery poses.
- Hero playback distinguishes idle, run, takeoff, airborne, landing, dash, and hit reaction states. Some states combine painted poses with procedural breathing, lean, or transitions.
- Existing Alice running, idle, and dash rows are retained alongside the new movement poses.
- Sprite measurements anchor bodies and feet rather than positioning only whole atlas cells.
- State transitions briefly blend poses, and cached frame isolation removes neighboring fragments from irregular movement sheets.
- Boss preparation/cast/recovery selection responds to nearby encounter hazards.
- Enemy and companion playback uses measured positioning with approach or hover timing.
- The animated collection lets you inspect every hero, boss, and animated enemy, choose a movement, and pause playback without spending shards or changing unlocks.

This is a developing illustrated game release. Bosses and enemies still use their existing short painted cycles; not every action has a separate long, hand-drawn animation. Some generated poses and their transitions may still need manual artistic cleanup.

## Menus and accessibility

**Home** starts runs and opens the animated collection. **Heroes** manages the playable roster. **Pals** manages companions. **Shop** contains permanent upgrades and difficulty information. **Quests** contains modes and recurring rewards. **Events** shows the current token activity. **Book** contains awards, the codex, titles, story fragments, and The Book of Falling. **More** contains audio, vibration, statistics, and reset controls.

The layout is portrait-oriented and constrained on wide screens. Navigation switches to two rows in narrow layouts. Dialogs have keyboard focus handling, labels, and Escape dismissal. The motion renderer responds to the operating system's reduced-motion preference; this reduces presentation animation but does not remove the moving hazards central to gameplay. Sound and music levels are adjustable. Haptics depend on browser/device support. Audio may require a user gesture before it starts.

## Play locally

Extract the ZIP and open `index.html` in a desktop browser. All required game assets are embedded, so there are no separate image paths to repair. Local-file storage behavior varies between browsers; playing from a stable hosted URL is preferable for reliable persistent saves.

For a local HTTP preview, if Python is installed, run the following from the extracted folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/`. This command is optional and is not needed for GitHub Pages hosting.

Once downloaded, the self-contained file can run without remote artwork or libraries. The hosted version has no service worker or installable-PWA/offline-cache guarantee.

## Publish on GitHub Pages

1. Extract this ZIP on your computer.
2. Create or open the repository you want to use.
3. Upload the extracted release files directly into the repository root and commit them. Verify the entry file is named exactly `index.html`.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Choose your publishing branch, commonly `main`, and **/(root)**. Save the configuration.
7. Wait for GitHub's Pages deployment to complete, then open the site URL shown in Pages settings.

Keep the included empty `.nojekyll` file in the publishing root. There is no npm install or build step for this package. If your repository already publishes from `/docs` or uses a custom Actions workflow, put the release in that configured source or update the deployment configuration consistently.

GitHub's official instructions: [Configure a Pages publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) and [Create a Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).

## Saves and privacy

Progress is stored in browser `localStorage`, using the game's existing `drh_save_v2` key. Existing progress is preserved on the same browser origin. This edition adds manual JSON save export/import through Adventure → Save & Backups or More → Save & Backups. It does not add cloud accounts, automatic synchronization, multiple save slots, or active-run resume.

- Keep the same browser profile and hosting origin when updating the game to retain access to existing progress.
- Local files, localhost, GitHub Pages, and a custom domain can have separate storage contexts.
- Sites on the same origin can share storage keys. Two copies of this game on the same GitHub Pages origin can therefore use the same save key, even at different repository paths.
- Private browsing, clearing site data, or resetting progress can remove saves.
- The reset control in More is intended to delete progression. Do not use it to refresh artwork.
- No game login or custom analytics service is configured in the self-contained build. Hosting-provider access logging is outside the game's own save system.

## Troubleshooting

| Problem | What to check |
| --- | --- |
| GitHub shows repository files instead of the game | Open the deployed Pages site URL, not the repository or raw-file preview. |
| Pages shows a README instead of the game | Confirm `index.html` is in the configured publishing root. |
| The site returns 404 | Check the Pages branch/folder, deployment result, and published URL. |
| Upload completed but the old game remains | Wait for deployment, refresh, and check that the correct repository and branch were updated. |
| Nothing plays after uploading a ZIP | Extract it first and upload its contents; a ZIP is not a web entry point. |
| The game opens but takes time to appear | This illustrated build embeds a substantial amount of artwork. Allow the first download and decode to finish. |
| Sound is silent | Tap the page, check More audio settings, the mute control, and device/browser volume. |
| Progress appears missing | Check the exact origin and browser profile. A different URL origin does not migrate a previous save. |
| Browser storage is unavailable | Allow site storage and avoid restrictive/private modes when you want persistence. |
| An animation looks clipped or rough | Record the hero/enemy, movement state, and device/browser; use the gallery to reproduce it. |

## Release contents and development

| File | Purpose |
| --- | --- |
| `index.html` | Full editable, self-contained game source and playable release |
| `.nojekyll` | Static Pages publishing marker |
| `README.md` | Game description, controls, features, hosting, and troubleshooting |
| `RELEASE_NOTES.md` | Scope and current limits of this release |
| `VALIDATION.md` | Packaging checks and prior implementation checks |
| `SHA256SUMS.txt` | Checksums for the packaged files |
| `EXPANSION_GUIDE.md` | Mastery, contracts, relics, expeditions, and backup instructions |
| `tests/verify-game.cjs` | Dependency-free Node checks for expansion rules and save validation |
| `SHARING_GUIDE.md` | Share controls, public play links, and social-preview setup |
| `assets/social-preview.png` | Branded website-link preview image, 1200 × 630 |

The HTML contains the game's data tables, gameplay engine, audio synthesis, rendering, menus, save logic, sprite manifests, and movement refinements. Embedded artwork uses data URLs. No separate source download or asset folder is required to run the game itself. The included assets folder supplies the website social-preview image and should be uploaded with the full release. The package does not include the earlier authoring scripts or raw full-resolution PNG masters.

No software license is selected by this package. Decide your repository's licensing and attribution terms before representing it as open source. The game uses original interpretations of familiar literary and fairy-tale figures; this README does not provide a jurisdiction-specific rights clearance.

## Validation and current limits

The release package is checked for ZIP integrity, a root-level entry point, matching game bytes, embedded local artwork, and JavaScript syntax. The movement implementation previously passed 1,764 pose-and-draw checks, with browser spot checks of gameplay and gallery states. These are not a complete campaign playthrough, a visual approval of every frame, or physical-device certification.

See [VALIDATION.md](VALIDATION.md) and [RELEASE_NOTES.md](RELEASE_NOTES.md) for the release's checks and remaining limits. The expansion also has fourteen automated checks and phone-width browser checks. Run `node tests/verify-game.cjs` from the extracted release folder to verify its core expansion rules. These tests use mocked browser APIs and do not certify physical-device sharing or a complete campaign playthrough.
