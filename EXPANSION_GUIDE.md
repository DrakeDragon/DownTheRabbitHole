# Adventure Edition — Player and Hosting Guide

## Start here

Open **Adventure Hub** on the title screen. If you already played earlier editions, open **Contracts** first: your old lifetime totals can satisfy goals immediately. Claim a completed tier, visit the Relic Forge, craft a relic, then press Equip. Each run can carry two relics. Try **Expeditions → The Tea Trail** for a complete three-stage adventure.

The main game's stage length, painted worlds, character animation, Tea Party contrast, upgrade selection, and explicit Start Next Stage flow are preserved.

## Wonder essence

| Source | Essence | Other rewards |
| --- | ---: | --- |
| Clear a normal stage | 1 | Normal run rewards |
| Clear a boss stage | 3 | Normal boss and run rewards |
| Claim a mastery stamp | 2 | 25 shards |
| Claim contract tiers 1–5 | 2 / 4 / 6 / 8 / 10 | 30 / 70 / 110 / 150 / 190 shards |
| Win an expedition | See below | See below |

A stage reward is granted once per completed stage. Mastery and essence are saved at stage completion. Ordinary run payouts still happen when that run ends. Quitting a run before its end does not create a Run Record or grant its unfinished run payout.

## The Realm Atlas

Each of the twenty-four realms has five stamps:

1. Clear the stage once.
2. Collect sixty shinies there across completed stages.
3. Clear without taking a hit.
4. Clear the stage three times.
5. Clear it five times.

A shield loss, emergency blast, or revival counts as taking a hit. Invulnerable contacts and hazards destroyed during a dash do not. Atlas totals begin with this edition because earlier saves did not record per-realm clears. All maps are visible as a travel guide; an unvisited label marks places you have not reached. Selecting a realm previews it; it does not teleport the player or bypass stages. Five stamps per realm means 120 one-time stamp rewards.

## Permanent contracts

| Family | Tier goals |
| --- | --- |
| Runs | 1, 5, 15, 40, 100 |
| Shinies | 50, 250, 1,000, 4,000, 15,000 |
| Gravity flips | 25, 100, 500, 2,000, 8,000 |
| Stage clears | 1, 5, 20, 60, 150 |
| Boss defeats | 1, 3, 10, 30, 100 |
| Heroes owned | 1, 3, 8, 18, 36 |
| Close calls | 5, 25, 100, 400, 1,500 |
| Deepest stage reached | 2, 4, 8, 16, 24 |

Claim each eligible tier individually. There is no expiry and no requirement to claim an earlier tier before a later one. Existing lifetime stats qualify immediately; stage clears use the new expansion total.

## Relic Forge

| Rank being crafted | Essence cost | Shard cost |
| --- | ---: | ---: |
| 1 | 3 | 60 |
| 2 | 8 | 180 |
| 3 | 16 | 400 |

Each relic costs the same to craft and improve. Equipping and unequipping cost nothing. Relic effects add to or multiply the existing build as described; they do not overwrite your curios or hero abilities. Changes apply on the next run. Maximum rank is three; there are twelve relics and two equipped slots.

| Relic | Bonus per rank |
| --- | --- |
| Wayfinder Compass | +12 pickup-range pixels |
| Bottomless Purse | +3% shiny rewards |
| Lost Crown | +3% score |
| Patient Pocket Watch | 1.5% slower travel |
| Silver Thimble | 2% smaller collision size |
| Skyward Boots | 2.5% stronger gravity for quicker surface crossings |
| Comet Brooch | +0.1 seconds to each dash |
| Guardian Lantern | +1 shield charge at the start of each stage |
| Second Draft Quill | +1 reroll per run |
| Ember Kettle | +1 emergency blast per run |
| Unbroken Ribbon | +0.3 seconds of combo duration |
| Treasury Key | +4% ordinary run shards |

Story, Endless, and Expeditions apply relics. Daily Tale, Boss Rush, and Weekly Gauntlet exclude them. Glass builds retain their shield and emergency-blast restrictions. A relic that affects a dash or combo is useful when the run's abilities supply that mechanic.

## Expeditions

| Expedition | Stages | First-clear reward | Repeat-clear reward |
| --- | ---: | --- | --- |
| The Tea Trail | 3 | 5 essence + 100 shards | 1 essence + 33 shards |
| Beyond the Crossroads | 6 | 12 essence + 240 shards | 4 essence + 80 shards |
| The Midnight Voyage | 12 | 25 essence + 500 shards | 8 essence + 166 shards |
| The Grand Descent | 24 | 55 essence + 1,000 shards | 18 essence + 333 shards |

Expeditions start at the beginning and follow the normal realm order. They use your selected hero, companion, Curiouser setting, equipped relics, and the standard seasonal modifier. The normal boss cadence is every fourth stage. Clear the final stage to receive a victory, ordinary run payout, and expedition reward. Fall Again repeats the selected expedition. First-clear bonuses are saved per expedition.

## Run Records

The latest thirty completed runs are stored locally and included in exports. Each record distinguishes stage reached from stages cleared. A failed attempt on Stage 3 generally has two cleared stages; a Tea Trail victory has three. Existing earlier attempts are not reconstructed.

## Move your save

1. On the old browser, choose Save & Backups, then Export Save File.
2. Keep the downloaded JSON file in Files or another location you control.
3. On the new browser, open the same game edition and Save & Backups.
4. Select Import a save file and choose the JSON.
5. Review the hero, runs, shards, deepest stage, and essence shown in the preview.
6. Press Restore Save only when this is the progress you want to keep.

Restore replaces the destination browser's game progress. Export that destination save first if it matters. Cancelling the preview leaves progress unchanged. Invalid or unsupported files show an error before replacement. An active run is not included. The sharing-link override is separate from game progression and is not imported. Browser download and file-picker behavior varies by phone.

Existing saves use the unchanged `drh_save_v2` key and gain the expansion fields without resetting heroes or currency. Keeping the same hosting origin preserves normal browser storage. Manual export/import is the way to transfer across origins or browsers; this is not cloud synchronization.

## Host and verify

Extract the release ZIP and upload its contents to your GitHub Pages root. Keep index.html, .nojekyll, and the assets folder together. No build process is required. Optional developer checks: install Node.js from its official distribution, then run `node tests/verify-game.cjs` in the release folder. No npm packages are required by the checks.

The existing SHARING_GUIDE.md explains native share controls and website-preview setup. Playtest on the phones and browsers you intend to support before treating this as a platform-certified release.
