# Avatar Studio

Open **https://buicongnguyen.github.io/avatar-studio-play/**. Current updates are on the root page; `/test/` preserves the older snapshot.

This repository contains the built website. Source development is on `main` in the private avatar-studio repository. Release identity is in [release.json](release.json).

Start with updated Nabi, Nabi original, or Haru. Access code `buicongnguyen` unlocks all ten cards, available wardrobe choices, PC HD tiers and GLB import. `nabi` selects updated Nabi with default clothes. These are demo switches, not security: browser assets remain publicly downloadable.

## Try this update

- **Play → Two-person practice → Practice partner:** your current character faces Haru Light. Low or High kick reacts only on contact; Haru recoils into sitting. Stand up recovers, Reset restarts. Partner distance tests hits and misses. Phones enter a full-stage view with Controls/Practice view and End practice buttons.
- **Move → Dance → Load more dances:** captured Salsa, K-pop Magnetic and Roly Poly, YMCA-style gestures, Robot dance, and original Trump-style/Musk-style inspired loops. The three captured phrases play once and retain their travel. No music is included; inspired loops are not actual public-figure captures.
- **Move → Social → Load social motions:** Hug, Self-hug, and lowering onto hands and knees to look forward, then standing. These are solo gestures without a simulated partner.
- **Settings → Face:** Cheek fullness, Lip lick and Blow air on the eleven anatomical rigs. The new shape persists while expressions play; short face actions return to your chosen expression.
- **Settings → Body → Bust & chest:** Bust firm and Bust shape reach +150% of their authored morph displacement. Existing saved values retain their previous effect. This does not mean body dimensions grow by150%.
- Combat kicks have corrected knee/ankle orientation. Several older raised-foot motions and the backflip landing use precomputed repairs; intentional high-flight/inverted pointing is preserved.
- Anatomical mouths use a darker cavity and reduced reflections on tongue/teeth.

Existing content remains: 15 combat actions including left/right slaps, two flips, gym/everyday actions, Normal walk/run, playlists, scrub, 23 expression presets on full face rigs, silent video, touch pad and Grab & move controls. Original Nabi/Haru expose only the controls their rigs support.

The Korean gymnast has Light (39,496 triangles,7.03MB) and PC HD (142,728 triangles,23.75MB) tiers. Optional motion packs download for the selected avatar; they add animation tracks, not new character geometry. Phone performance depends on the device and selected tier.

## Known limits

Two-person practice is a coordinated animation prototype with swept foot collision checks, not a ragdoll or a complete combat game. Haru is the only NPC in this version. Its additional reaction pack is about 81 KB; Haru loads separately (3.41 MB). NPCs and paired-session state are excluded from primary-avatar GLB/preset export. Editing the body/outfit or choosing a different action ends practice.

This is a test version, not a full body/cloth collision simulator. Large body changes can expose garment intersections. The old Salsa (`Dance sway · legacy`) right arm and the self-hug now use checked paths around the torso; this is a targeted correction, not general collision physics. Nabi's skirt may intersect the legs during wide steps; her crop-jacket has a small existing seam fold at extreme firmness. The Asian man's mouth has a small lower-lip gap while open. Lip lick and Blow air are stylized approximations, not a speech or tongue-collision system. Some floor poses leave a small knee gap.

New cheek/tongue morphs and ordinary materials export in GLB. Timed face actions are studio logic and are not automatically baked into animation clips. Export includes body motions loaded in the session. Shy cheek tint and touch deformation are runtime effects.

Model, motion and dependency credits: [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).
