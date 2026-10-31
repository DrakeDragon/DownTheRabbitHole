# Validation — Encore Edition

## Automated checks

Run `node tests/verify-game.cjs` from the release folder. The test reads the actual embedded script from index.html and needs no npm dependencies.

All 21 checks passed:

1. Additive migration of earlier saves.
2. Adventure content counts.
3. Contract eligibility and duplicate-claim prevention.
4. Crafting costs, affordability and rank caps.
5. Two unique equipped slots and unequipping.
6. Captured relic ranks, repeated recalculation and challenge-mode exclusions.
7. All twelve relic effects and glass restrictions.
8. Once-per-stage essence and clean mastery tracking.
9. Duplicate mastery-claim prevention.
10. Expedition finish lines, first/repeat rewards and finish idempotence.
11. Boss counting at expedition victory.
12. Thirty-record history retention.
13. Save round-trip and migration.
14. Malformed and unsafe backup rejection.
15. Floor/ceiling boss threats, modest heights and geometric flip windows across all 22 bosses.
16. Idle-floor collision checks against all 22 bosses with the default unprotected hero.
17. Counter eligibility and the eight-percent damage cap.
18. Every boss's pose bounds and drawing with finite coordinates; four-pose cache exercised across 176 drawing samples.
19. Counter damage finishing a boss and resetting at the next stage.
20. Ordinary non-boss generation matching the prior implementation under the same seed.
21. Deterministic boss generation under the same seed.

These tests use mocked browser, canvas, storage, audio and timing APIs. They verify rules and drawing arguments, not photographic output or human difficulty balance.

## Browser checks

- New title artwork, removed collection entry, and prominent Fall In placement.
- New guild-hall Adventure artwork and legible overlay text.
- Branded results and persistent actions on a 320 × 568 app-width fixture.
- Both primary buttons have 64-pixel height and remain inside the fixture's visible bounds.
- Result content scrolled by 757 pixels while the replay button remained fixed.
- Fall Again starts play immediately and the results action bar disappears during play.
- Actual boss artwork inspected after correcting an uninitialized reaction timer; no game-page errors observed in that flow.
- Test fixtures use separate save keys. Synthetic scores, invulnerability and QA controls are excluded from the release.

## Packaging

The root index.html matches Encore Edition source, local artwork is embedded, the asset previews and documentation are included, ZIP CRC checks pass, and packaged files match SHA-256 sums.

## Limits and historical checks

Cloud Chromium app-width fixtures are not physical iPhone/Android certification. The current release does not claim a full campaign playthrough or prove final boss balance. Native sharing and file pickers still require device testing. The earlier sharing-payload and gallery suites are historical checks rather than current rerun claims. No post or message was sent during validation.
