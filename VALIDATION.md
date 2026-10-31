# Validation — Foreground Clarity Edition

## Checks performed for this update

- JavaScript syntax check passes for the packaged HTML.
- Automated render checks cover 864 combinations: 24 realm palettes, 18 obstacle kinds, and both floor/ceiling surfaces.
- Render coordinates are finite, original obstacle properties are not mutated, the drawing context is restored, and the material cache stays bounded.
- Beam rendering is exercised across 24 palettes.
- Source comparisons confirm existing collision, stage-play, and completion-flow functions are retained; stage distance remains 13,600 units.
- Browser inspections cover the ocean/coral and Tea Party/porcelain scenes, hero silhouette treatment, and flying-enemy contrast. No page rendering errors were observed in those checks.
- ZIP integrity, packaged-source byte equality, and file checksums pass.
- Local QA pages and test-only controls are excluded from the ZIP.

## Prior checks retained as historical results

The previous release checked 36 curios / 79 level descriptions, manual stage continuation and duplicate-action guards, 96 environment cases across 24 realms, and phone-width completion layout. The earlier movement implementation reported 1,764 pose-and-draw cases. These are historical checks, not rerun claims for this presentation-only pass.

## Remaining validation

These checks are not a complete campaign playthrough or physical iPhone/Android certification. Long-duration mobile performance and artistic review of all generated frames remain playtesting work.
