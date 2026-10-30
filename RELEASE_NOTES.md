# Movement Edition — release notes

This package contains the latest completed movement build from this project. Packaging does not change gameplay, balance, saves, or artwork.

## Included

- Self-contained HTML source with embedded artwork and audio synthesis.
- 36 heroes, 22 boss definitions, 24 realm definitions, six companions, 12 painted animated enemy types, and code-rendered hazards/projectiles.
- Expanded hero takeoff, flight, landing, and recovery poses.
- Measured sprite anchors, transition blending, and cached frame isolation.
- Movement selection and pause controls in the animated collection.
- Phone-oriented menus, narrow-screen navigation, and dialog focus handling.
- Existing story, progression, rewards, events, modes, and device-local saves.

## Remaining limits

- Bosses and enemies retain short existing painted cycles; not every state has a new long animation.
- Some generated frames and costume consistency still warrant visual cleanup.
- Realm backgrounds share a common illustrated scenery treatment.
- Some hero states reuse poses with procedural motion.
- No cloud save, online leaderboard, service worker, or installed offline/PWA support.
- Full campaign completion and physical iPhone/Android certification have not been performed.
- The embedded artwork increases initial download and decode cost.

## Updating an existing repository

Replace its existing game entry point with this package's `index.html`, retaining the same hosting origin if you want the browser to keep using its existing save. Commit `.nojekyll` and the documentation alongside it. Follow the README for Pages configuration. No source rebuild is required.
