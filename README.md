# Avatar Studio

Open **https://buicongnguyen.github.io/avatar-studio-play/**. Current updates are on the root page; `/test/` preserves the older snapshot.

This repository contains the built website. Source development is on `main` in the private avatar-studio repository. Release identity is in [release.json](release.json).

Start with updated Nabi, Nabi original, or Haru. Access code `buicongnguyen` unlocks all eleven cards, available wardrobe choices, PC HD tiers and GLB import. `nabi` selects updated Nabi with default clothes. These are demo switches, not security: browser assets remain publicly downloadable.

## Try this update

- **Play Single:** existing touch pad and Grab & move, Press/Pull strength and timed face reactions. Entering Single ends any active or loading partner session.
- **Play Multiple:** choose Combat or Life, then a partner. Combat supports low/high punch, low/high kick and left/right slap with contact-based regional reactions, fall to sitting and recovery. Life contains the existing paired hugs and kisses. Switching submodes cancels the other session; choosing the tab alone does not load a second avatar.
- **Move → Life:** the solo Life category now appears beside Dance and the category buttons wrap on small screens. Move Combat and Life provide shortcuts to Play Multiple.
- **Calibrated joint rules:** both actors evaluate eight knee, elbow, wrist and ankle joints against reviewed bind frames. A narrow, smoothly faded guard can repair a small reversed airborne right knee in five reviewed kick clips. Other measurements are diagnostic; this is not a whole-body collision or anatomical simulator. Existing valid shipped kicks remain unchanged. These checks add no geometry and run locally in the browser.
- **Play Multiple → Life:** choose an unlocked partner (including duplicates or PC HD), then Hug, Kiss or Hug-and-kiss, posture and standing arm arrangement. Floor poses keep fixed supporting arms. Side-lying requires original hair without glasses or a headband. Start fits the current pair; contact holds until Release. Pause, Reset and End control both actors. End restores your previous motion, camera and face preferences. An unsupported fit reports a reason. Phone controls keep the pair visible; screenshots include both.
- **Shots → Enter Picture mode:** hold the current frame or choose one of ten standing/seated poses. Pick a temporary expression, adjust the camera and Save picture. Return to motion restores the previous clip/time/play state and camera; body/outfit/makeup edits remain. Pose packs download on demand, and no saved face setting is overwritten.
- **Move → Life:** load solo kiss/hug invitations and floor rest motions. The connected floor rest sequence lies down, rests on the back and both sides, and stands up. Sleep closes supported eyelids; kiss gestures temporarily shape the lips. Your saved face settings return afterward. The body works on Original Nabi, whose face lacks these controls.
- **Move → Dance → Load dance styles:** belly, box step, ballet-influenced turn, upright breaking, clothed burlesque-inspired flourish, contemporary reach, solo tango and flamenco-inspired steps. **Combat → Load martial arts:** boxing, Taekwondo-style, Muay Thai-style, solo Judo entry and sword actions. **Hit reactions:** regional recoils and a supported backward sit/recovery chain. All are optional animation-only downloads.
- **Settings → Body:** independent Muscle fullness, Torso/Leg length, and a longer-legs/shorter-torso preset. **Outfit:** fitted tops and sport shorts, shirt length, opaque sport bra/optional support layer, padding, and sneakers/socks/barefoot on audited anatomical rigs. Default public wardrobe restrictions remain.
- **Play Single → Touch strength:** 1–10 gain, default4, with region caps. Strong touches carry nearby skin and clothing together. At higher settings the touch area expands after depth reaches its limit.
- **Settings → Face:** seven face-shape controls, cheek fullness up to 200%, persistent cheek/lip colors and iris color. Independent jaw width/roundness avoids forcing a pointed chin; eye-socket depth is a small signed adjustment. Glasses, headbands and original/short/bob hairstyles can be combined on the anatomical avatars. Original Nabi/Haru retain their supported controls. Built-in mouth lining is now matte dark pink.
- **Play Multiple → Combat → Start two-person Combat:** choose any unlocked Light partner, including the same character twice, or an explicit PC HD option. Low/High punch, Low/High kick and both slaps react only on contact. Choose regional Recoil or Fall to sitting; Stand up recovers and Reset restarts. Try 0.55–0.65 m for hands and 0.65–0.8 m for kicks; reach depends on the pair. Captions always work, with optional local browser voice off by default. Phones enter a full-stage view with Controls/Combat view and End combat buttons.
- **Move → Dance → Load more dances:** captured Salsa, K-pop Magnetic and Roly Poly, YMCA-style gestures, Robot dance, and original Trump-style/Musk-style inspired loops. The three captured phrases play once and retain their travel. No music is included; inspired loops are not actual public-figure captures.
- **Move → Life → Load social motions:** Hug, Self-hug, and lowering onto hands and knees to look forward, then standing. These are solo gestures without a simulated partner.
- **Settings → Face:** Cheek fullness, Lip lick and Blow air on the eleven anatomical rigs. The new shape persists while expressions play; short face actions return to your chosen expression.
- **Settings → Body → Bust & chest:** Bust firm and Bust shape reach +150% of their authored morph displacement. Existing saved values retain their previous effect. This does not mean body dimensions grow by150%.
- Combat kicks have corrected knee/ankle orientation. Several older raised-foot motions and the backflip landing use precomputed repairs; intentional high-flight/inverted pointing is preserved.
- Anatomical mouths use a matte dark-pink cavity and reduced reflections on tongue/teeth. A guarded Asian-male/lean cavity-floor correction removes the pink chin patch seen during kissing head tilts; extreme head-down plus maximum open jaw retains an older anatomy limitation.

Existing content remains: 15 combat actions including left/right slaps, two flips, gym/everyday actions, Normal walk/run, playlists, scrub, 23 expression presets on full face rigs, silent video, touch pad and Grab & move controls. Original Nabi/Haru expose only the controls their rigs support.

The Korean gymnast has Light (39,496 triangles,7.03MB) and PC HD (142,728 triangles,23.75MB) tiers. Optional motion packs download for the selected avatar; they add animation tracks, not new character geometry. Phone performance depends on the device and selected tier.

## Known limits

Joint guards are runtime preview behavior, excluded from ordinary GLB animation export. Unknown or changed skeletons receive no guessed corrections. Paired Life contacts remain audit-only. Phone testing uses browser emulation; physical-device performance remains unmeasured.

Paired Life offers nine action/posture combinations using bounded pair-specific fitting and authored motion, not nine captured clips or complete body/clothing physics. Seated and side-lying Kiss/Hug-and-kiss share a body pose. Initial fitting can take seconds to tens of seconds on Light and several minutes for some HD poses; it can be cancelled, and Replay reuses accepted fitting. Raised-arm floor poses can expose substantial skin-through-clothing at the shoulder/collar, especially on the male tee. Side-lying rejects alternate rigid hairstyles, glasses and headbands until their contact is supported; saved appearance is preserved. The player keeps current proportions; the independently loaded partner uses its default outfit/profile. Large edits can be unsupported. Saved face settings are preserved, and original Nabi only receives facial channels its rig supports. Pair clips and the NPC are preview state, excluded from normal primary-avatar GLB export. Phone validation uses browser emulation.

Picture poses are static default-shape fits with shared-finger and rigid-clothing limits. Photo expressions are preview overrides, not baked GLB facial clips. Imported GLBs without compatible Photo clips can still hold the current frame. Phone checks use emulation; real-device checks remain.

Life floor poses are fitted at default shapes/outfits. Small legacy hair/garment seam intersections remain (up to about5.6mm), and the largest hand residual is about1.2mm. Rest holds are static; rigid hair and skirts can clump or crease. Use the connected sequence for entry/exit.
New style routines are short authored/adapted previews; only the two identified new dance phrases are captured. Breaking is upright top-rock and tango/Judo are solo. Supported falls end sitting, not in a ragdoll. Shared finger joints limit fist detail; the legacy Nabi skirt stays elevated when seated and a sleeve can dip about4mm into the floor. Full-trajectory framing can make travelling routines small on phones.
Face customization exports ordinary morphs, textures and visible accessories. Animated eye-shape blink/gaze corrections need the documented studio runtime adapter in another engine. Only the selected hairstyle is included in a GLB; rigid bob tips can approach shoulders in large head turns. Makeup is texture recoloring, not freehand painting.

Two-person practice uses swept anatomical hand/foot contacts and independent partner instances. It is authored reaction animation, not a ragdoll or complete combat game. Six stationary attacks are supported; blocks, throws, swords and jump attacks are not paired yet. Legacy covered-body targets use skeletal estimates. Fine facial hits use a head target. Partners retain default body/outfit profiles. Local voice depends on the device and does not appear in silent video or GLB export. NPCs and paired-session state are excluded from primary-avatar GLB/preset export. Editing the body/outfit or choosing a different action ends practice.

This is a test version, not a full body/cloth collision simulator. Large body changes can expose garment intersections. The old Salsa (`Dance sway · legacy`) right arm and the self-hug now use checked paths around the torso; this is a targeted correction, not general collision physics. Nabi's skirt may intersect the legs during wide steps; her crop-jacket has a small existing seam fold at extreme firmness. The Asian man's mouth has a small lower-lip gap while open. Lip lick and Blow air are stylized approximations, not a speech or tongue-collision system. Some floor poses leave a small knee gap.

New cheek/tongue morphs and ordinary materials export in GLB. Timed face actions and Life expression cues are studio logic and are not automatically baked into animation clips. Export includes body motions loaded in the session. Shy cheek tint and touch deformation are runtime effects.

Model, motion and dependency credits: [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

## Plan repair release
Floor playlists now prevent unsafe contact-state jumps and offer Add recovery. Shirt-length controls are enabled only for compatible selected tops. Hidden swords no longer leave unusable sword clips in exports; export reports any omitted motions. Initial paired fitting now displays its true preparation phase and HD timing guidance. All eight plans remain scoped test implementations, with remaining portability and visual refinements tracked in source documentation.

## Protective wrist repair
Head recoil and Protect nose, mouth and left/right eye now inherit the solved forearm orientation, eliminating the accidental half-turn at the wrist. All thirteen rigs use corrected baked tracks; unrelated motion and ready endpoints are preserved. Broader joint review remains a separate ongoing pass.

## Wrist and arm motion update
Flamenco and solo-invitation wrist twists are corrected on affected rigs. Boxing hook and Muay Thai style elbow use coherent arm frames through guard transitions. Body/foot tracks remain preserved. The release also adds solo motion mirroring, a portable game-GLB export, reviewed lower-lash visibility and restrained back-sleep breathing. Full integration suite: 1,056 passing tests; final changed-motion suite: 93 passing tests. The separate sleep-turn self-clearance repair is still being evaluated.

## Lite movement refinement
Backflip, YMCA and Turn have reviewed arm/wrist corrections on supported Lite avatars. Side-sleep rolls use a clear upper-hand path and a reachable relaxed palm; connected floor endpoints and other body/foot tracks are preserved. Existing HD assets remain unchanged. Actual skinned-surface, continuity, endpoint, framing and browser checks accompany these changes. This is scoped authored-motion repair, not a general body/cloth collision engine. Shoulder/collar garment distortion and paired-contact fitting remain separate work. The target for future visual detail is a Lite body with selective face refinement, not a whole-body HD replacement.

## Lite stance contact
Verified standing gestures now fit both soles after body-proportion changes, preserving foot orientation and leg lengths. This bounded preview correction excludes jumps, single-foot support, floor and paired actions, imported rigs and full-HD models. Export retains the authored portable asset and restores the live preview. Classic/Haru captured-dance support metadata remains a separate audit item.

## Lite Robot wrist repair
Robot dance uses relaxed forearm-relative palms on eight modern Lite rigs, with neutral hands clear of the thighs. The original raised-shoulder poses and short staccato timing are retained. Other clips, legs and HD assets are unchanged.

## Korean gymnast face proportions
The Lite Korean gymnast has refined cheek, jaw, nose and lip proportions with baked lower lashes, preserving body controls, the bind rig and all animations. Backflip camera bounds also retain source-motion extents. Full-HD assets remain unchanged; measured face ratios are fitting evidence, not a claim of exact identity.

## Male tee collar clearance
The Asian, lean Asian and blond male tees now fit the neck and upper collar with matched skin weights and body morphs. Export retains the fitted garment. This scoped correction leaves sleeve and underarm folds for a separate pass.

## Paired hug fitting and cancellation
Supported Lite standing hugs use calibrated arm frames and checked surface clearance. Fitting runs in a worker with progress, cancellation and repeat-pair caching. Unsupported or infeasible pairs are rejected with an explanation; this is not general whole-body collision simulation.

## Godot import helper
Shots now includes a Godot import helper that preserves customized morph defaults, including negative body settings. Three representative Lite exports were verified in native Godot runtime and editor imports. The included guide describes animation-optimization tradeoffs and app-only behavior that is not exported.

## Child pose palm and wrist repair
Modern Lite Child pose keeps palms flat and wrists connected. A bounded, restored preview correction maintains hand support for tested body settings; authored arm changes export normally. Other clips, native rigs and full-HD assets remain unchanged.

## Magnetic foot heading correction
Original Nabi and Haru now have a source-specific correction to a short excessive foot twist in Magnetic, with false near-ground support flags removed. The authored sole tilt, ankle path, planted poses and other clips are preserved.

## Male sleeve fit
Asian, lean Asian and blond male tees have a bounded geometry correction that reduces raised-arm cut-through without extra triangles or per-frame work. It is preserved in GLB exports. Deep YMCA folds and some extreme body settings still need further garment/contact work.

## Forward jump wrist refinement
Reviewed modern Lite forward jumps now reduce excessive palm roll while preserving hand direction, arm motion and the existing ankle corrections. The blond man’s left hand remains unchanged after a rejected candidate; corrected tracks export normally.

## Hat tilt supporting hand
Updated Nabi, the blonde and the two Lite ponytail models keep their supporting left hand outside the hip during Hat tilt. The right-hand gesture is preserved; reviewed left-arm tracks export normally. This is a bounded pose repair, not general collision simulation.

## Lite self-hug arm repair
Eight modern Lite avatars have a loose self-embrace with separated arm paths and improved wrist continuity. Source body/leg/finger motion and classic/Haru/HD packs are preserved. Selected large/short-arm settings can still overlap the torso; this is not general collision simulation.

## Smoother male hat gesture
Asian and blond male Hat tilt gestures use a smoothed right-arm path that reduces overfolded elbow creases while preserving the palm direction. The lean male shares the Asian source. This bounded change retains existing fingers and does not solve every garment fold.

## Blonde collar and shoulder fit
The Lite blonde tee receives a small one-time collar and shoulder fit with matched skin weights and body morphs. It removes the reviewed collar cut-through and is retained in portable GLB exports. No extra triangles or per-frame work are added; raised-sleeve folds and the Nabi jacket remain separate work.

## Lite sleep entry and recovery
Ten Lite motion sources keep their hands outside the thighs while lowering to the floor and rising. Only bounded arm curves change; body, legs, fingers, support masks and the other seven sleep clips are retained. Combined large-body settings and clothing folds remain separate fitting work.

## Male gesture finger refinement
Asian, lean Asian and blond men now have relaxed grouped right fingers in nine reviewed empty-hand gestures. The change removes folded-through fingertip fragments, preserves body and other animation channels, and exports as ordinary animation. Hat tilt and microphone gestures remain separate contact work.

## Body-adjusted ponytail sleep fitting
Move > Life offers an explicit cancellable floor fit for the refined ponytail Lite avatar. A worker verifies the current body through all nine floor motions before applying a cached preview correction. Defaults remain unchanged; unsupported settings decline, and exported clips retain their authored motion. This is scoped fitting, not general cloth or collision simulation.

## Male microphone gesture clearance
Asian, lean Asian and blond men use a reviewed hand path and relaxed grouped fingers in the empty-hand microphone gesture. This keeps the sampled hand clear of the face and palm while preserving original clips and prior repairs. Corrected curves export normally; stylized wrist bends and existing shoulder clothing cuts remain.

## Nabi central jacket back repair
Updated Nabi receives a small verified back-panel patch on primary and partner loads. It adds only132 triangles net, retains the existing body, face, rig and31 embedded clips, and exports as normal geometry. Front/side shoulder cuts remain. This release also corrects sleep-fit invalidation when visible held equipment changes.

## Male hat gesture hand refinement
Asian, lean Asian and blond men now use relaxed grouped fingers and a reviewed low-hand path in Hat tilt, composed with the earlier elbow fix. Sampled body settings and Idle transitions retain hand clearance, and corrected curves export normally. Existing wrist creases and some sleeve folds remain.

## Portable animation timestamp repair
Studio and game GLB exports now use strictly increasing animation sample times. Near-identical float32 duplicate keys are merged on export copies only, preserving live playback and all clips; conflicting keys fail clearly. Verified on all floor packs and actual ponytail and original Nabi browser exports.

## Original Nabi default sleep hands
Original Nabi uses reviewed hand paths during Lie down and Rise in her default body and skirt. The small motion dataset loads only with floor motions; unsupported body or clothing changes retain the authored movement. Both exports preserve all clips and the accepted default hand paths. Other avatars and source packs are unchanged; general cloth collision fitting remains unfinished.

## Lite gymnast eye refinement
Korean gymnast Lite has a modest eye-width and spacing refinement with preserved closed eyelids. It adds no triangles, retains all original animations and other avatars, and adds about12KB. Actual Studio face controls, portable exports and a Godot runtime check pass. Inherited corner lash tufts remain; fitted image ratios do not establish exact identity.

## Private worker skin coordinates
Body fitting workers now retain the exact mounted skin coordinates and morph state of the displayed avatar. Invalid mount transforms reject safely. The ordinary ponytail floor fit and portable export pass after this correction; source animations and models are unchanged.

## Body-adjusted self-hug fitting
Move > Life offers a cancellable self-hug fit for Blonde Lite in her default outfit. It verifies the current body in a worker, with reviewed Idle transitions, caching and safe invalidation after body edits. The correction is a solo1x preview; exports retain all authored animations. Unsupported profiles decline, and general collision handling remains unfinished.

## Original Nabi slim-profile floor support
Original Nabi has bounded foot and hand support for the exact reviewed slim-small body with her default skirt outfit. A small table loads only for an eligible solo floor pose; default and other body settings retain their existing behavior. All nine floor actions and both exports are checked. Exports retain authored clips and label the support preview-only. General body fitting, garment folds and the existing Idle transition snap remain separate work.

## Stronger cheek makeup
Cheek pinkness now extends to150percent while preserving the original0to100percent appearance. The shared range survives presets and editable/game GLB exports. Actual Lite masks, reset, actor isolation and Shy composition are checked; no model triangles or per-frame makeup work are added.

## Calibrated hand-rule diagnostics
Ten Lite sources now have measured bilateral wrist and grouped-finger profiles with explicit ownership for contact poses, transitions and paired actions. Read-only diagnostics distinguish wrist bend, roll and grouped digits without rewriting the animation. Unknown or changed rigs decline; this foundation does not claim universal collision prevention or independent little-finger control.

## Bounded gymnast chin height
Korean gymnast Lite now has a Chin height slider with a small vertical adjustment of up to about3mm, preserved in presets and both GLB exports. Other avatars and the original jaw width/roundness ranges are unchanged. Two wider-jaw candidates were rejected for angular outlines; the requested extended jaw range remains unfinished.

## Regional touch and surface tracking
Press/Pull limits now blend the actual skin weights at the chosen point, and the remote-pad marker follows the shader-deformed surface while retaining its original skin attachment. Multi-material hits qualify the actual touched material. Three Lite avatars pass ordinary Press/Pull/release and phone layout checks. This remains a visual effect: the experimental collision guard is not enabled and strong overlapping dents or nearby layers are not universally protected.

## Measured static bed preview
Move > Life offers a static back-rest bed preview for Ponytail Lite in her original body and outfit. A measured pillow supports the visible hair, the lying avatar is framed around controls, and Exit restores the previous motion and camera. Bed and temporary pose are excluded from both GLB exports. Other avatars, pose combinations, relaxed hands, crawling and bed transitions are not yet supported.

## Bounded torso spring demo
Play Single offers an optional Torso spring demo for Korean gymnast Lite with her default body and outfit. Separate 0–0.16 N Press/Pull controls drive one reviewed torso patch while Idle is paused, with a maximum generalized amplitude of4mm. Release springs back and Done restores the previous scene. Existing visual touch stays available; both GLB exports retain source geometry and motions and label the spring preview-only. This is not whole-body tissue or arbitrary-contact physics.

## Lite overarm throw preview
Move > Sports offers one original overarm throw for Korean gymnast Lite in her default body and outfit. Its 25KB motion pack loads on request, and an illustrative ball follows clip time through held and released phases. The ball is preview-only; the reviewed animation is included in both exports for its qualified profile. Imported animations remain ordinary clips even if they share the Sports name. Chest pass and male throw candidates failed contact checks and are not included.

## Measured side-rest bed poses
Move > Life > Bed pose now offers Back rest, Left side and Right side for original Ponytail Lite. Each static pose uses measured mattress and pillow support, preserves the authored joints and retains the original body/outfit requirement. Exit restores the prior camera and motion. Both GLB exports preserve all original clips and omit the bed preview. Arbitrary arm/leg composition, crawling and bed entry remain unfinished.
