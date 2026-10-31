# Validation — Painted Realms & Longer Stages

## Checks performed in this update

- JavaScript syntax check on the packaged HTML passes.
- 36 curios / 79 upgrade-level descriptions produce nonempty readable text without function source.
- Automated flow tests cover stage selection remaining stopped, explicit continuation, duplicate selection and duplicate continuation guards, two initial Head Start picks, exhausted upgrade pools, and Endless stage stops.
- 96 environment drawing cases cover 24 realms at four distances; source crop rectangles remain valid and decoded world cache remains bounded to two atlases.
- Browser QA confirms readable upgrade cards, selection remaining on the completion page, and the next-stage button resuming play.
- Browser inspection includes a phone-width completion layout and painted Rabbit Hole/Ocean presentation, with no page rendering errors observed in those checks.
- Packaged index.html matches the new Realm Edition source byte-for-byte. ZIP integrity and SHA-256 file checks pass.
- The archive excludes local QA pages and test-only controls.

## Prior validation

The earlier movement pass reported 1,764 pose-and-draw checks across 36 heroes and seven states, plus anchor and landing checks. These are prior implementation results, not rerun claims from this update.

## Remaining testing

These checks do not constitute a complete campaign playthrough, a visual approval of every frame, or physical iPhone/Android certification. Longer-stage balance and performance across devices require further playtesting.
