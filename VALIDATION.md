# Validation — Adventure Edition

## Current release checks

- JavaScript syntax checked from the final embedded game script.
- Fourteen dependency-free Node checks against the actual release code cover additive save migration, content counts, contract eligibility and duplicate claims, crafting costs and rank caps, equipped-slot limits, effect snapshots and mode exclusions, all twelve relic effects and glass restrictions, once-per-stage rewards and clean stamps, duplicate mastery claims, expedition finish lines and first/repeat payouts, boss counting at victory, finish idempotence, thirty-record retention, save round-trip, and malformed backup rejection.
- Browser inspection at 320- and 430-pixel portrait app widths: Adventure screens, crafting and equipping, actual realm artwork, mastery progress, a three-stage expedition finish using test-only stage-completion controls, paused upgrade selection, explicit next-stage start, and save dialog close/focus behavior.
- The 320- and 430-pixel content width checks found no horizontal overflow. The final phone navigation uses a four-column, two-row grid.
- No game-page errors were observed in the inspected cloud-browser flows.
- Packaged entry point matches Adventure Edition source. ZIP CRC and SHA-256 checks verify package integrity.
- Test-only pages, synthetic starting funds, and QA completion buttons are excluded from the release.

Run `node tests/verify-game.cjs` from the release folder to repeat the fourteen automated checks. They use mocked DOM, canvas, audio, storage, and timing APIs; they are logic checks rather than a browser or device emulator.

## Prior checks retained as history

The previous release checked branded PNG sharing payloads, text and clipboard fallbacks, cancellation, URL validation, dialog close routing, result-screen scrolling, and Tea Party ceiling contrast. Earlier releases checked obstacle materials, curio descriptions, environment crops, and registered movement poses. Those historical suites were not all rerun for this expansion.

## Limits

Browser checks use a cloud Chromium environment and app-width fixtures, not physical iPhone/Android devices. The expedition completion scenario advances stages with test-only controls, so it does not establish difficulty balance or certify a full campaign playthrough. Save-file content validation and round-trip logic are automated; real-device download, import pickers, and native sharing still require phone testing. No post or message was sent during validation.
