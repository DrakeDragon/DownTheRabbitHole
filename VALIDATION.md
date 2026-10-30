# Release validation

## Packaging checks performed for this ZIP

- Packaged `index.html` is byte-for-byte identical to the latest Movement Edition deliverable.
- Entry file is named `index.html` and resides at the archive root.
- README, release notes, validation notes, `.nojekyll`, and checksums are present.
- JavaScript is extracted from the packaged HTML and checked with `node --check`.
- Sprite data URLs are embedded in the HTML; no external script or stylesheet dependencies are required.
- ZIP CRC/integrity check passes; extracted file bytes match their SHA-256 entries.

## Prior implementation validation

The movement pass reported 1,764 pose-and-draw checks across 36 heroes and seven movement states, plus anchor validity and landing event checks. Browser checks covered title/gallery presentation and starting gameplay. Earlier checks included a narrow-layout preview. These are recorded as prior implementation checks, not rerun claims from packaging.

## Not yet certified

A complete campaign run, every generated frame's artistic quality, long-duration performance on low-memory devices, and physical iPhone/Android compatibility require further playtesting. Packaging checks confirm release structure and source consistency; they do not certify AAA visual quality or eliminate all gameplay issues.
