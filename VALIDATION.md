# Validation — Branded Share Edition

## Performed in this update

- JavaScript syntax check passes for the packaged HTML.
- Automated share-flow checks cover public URL sanitization, branded caption content, native PNG payloads, native text fallback, clipboard fallback, cancellation without fallback side effects, image-ready guarding, duplicate-share guarding, and dialog close routing.
- Canvas export renders a 1080 × 1350 run-card layout and a 1200 × 630 website preview using the existing realm/hero assets. The layout test contains synthetic values and is not included in the release.
- Browser inspection covers the phone-width ending screen, live result-card artwork, safe results scrolling, keyboard play-link dialog access, dialog cancellation, and explicit replay.
- Browser inspection covers the additional Tea Party ceiling-route contrast.
- No page rendering errors were observed during those checks.
- The packaged HTML matches Share Edition source; the preview PNG is present; ZIP integrity and SHA-256 checks pass.
- QA controls, synthetic result data, and test-only pages are excluded.

## Limits

Native share destinations were mocked for automated tests; the agent did not publish a post or send a message. Real-device share sheets, receiving-app caption handling, and preview cache refresh require platform testing. Cloud-browser checks do not certify every iPhone/Android combination or a complete campaign playthrough.

## Prior validation

Earlier releases checked 864 obstacle-material cases, 36 curios / 79 level descriptions, stage-stop flow, 96 environment crop cases, and 1,764 movement pose/draw cases. These are historical results, not rerun claims for this update.
