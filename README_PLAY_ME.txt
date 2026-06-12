# Violet Lanterns: A Cozy Corner Romance
Violet Lanterns v2.0.2 — iPhone Landscape Big Sprite Build

## How to play
Open `index.html` in Google Chrome on your laptop.

## What works in this build
- Main menu
- New Game / Continue
- Prologue scene
- Dialogue box and click-to-advance
- Multi-choice dialogue
- Hidden stat changes
- Arden warm and teasing sprites
- Background changes
- CG Gallery placeholder
- Endings menu placeholder
- Relationship Status screen
- Achievements screen
- Chapter 2 shrine / balcony / midnight café routes
- Stat-gated choices
- Batch 2 backgrounds and Arden expression sprites
- Chapter 3 morning café scenes
- Lantern festival route setup
- Ryokan / hot spring setup scene
- Batch 3 backgrounds and Arden outfit sprites
- More achievements and hidden route memory
- Extra Chapter 1 branches
- More gallery unlocks
- Save/load with 6 slots
- Autosave
- Export/import save code
- Backlog
- Settings placeholder
- Audio folder prepared for future sound files

## Notes
This is the v1.0 RC2. It keeps the v0.9 comfort polish and adds release notes, QA checklist, menu polish, and save migration/normalization.
Future versions can add:
- More chapters
- More CGs
- More Arden expressions
- Music and ambience files
- Ending logic
- Achievements
- More polished UI animations


## New in v0.5
- Dedicated special CG art added:
  - Coffee Beside the Rain
  - Violet Steps Confession
  - Lanterns After Rain
  - Festival Smile
  - Ryokan Steam and Violet Light
  - Mischief Under the Lanterns
- Full-screen CG viewer added.
- CG Gallery now prevents viewing locked CGs.
- CG unlocks are global and persist across New Game runs.
- Special CG moments now appear during gameplay when unlocked.


## New in v0.6
- Batch 5 art added:
  - Secret Lantern Garden background
  - Storm Room background
  - Departure Platform background
  - Warm Ending CG
  - Bittersweet Ending CG
  - True Violet Ending CG
- Chapter 4: The Secret Lantern Garden added.
- Storm-room emotional choice scene added.
- Real ending calculation added.
- Ending Gallery now unlocks endings globally.
- Ending CGs unlock and can be opened from the gallery.
- Warm, Bittersweet, Mischief Preview, and True Violet ending states exist.


## New in v0.7
- Arden sprites are smaller by default.
- Sprites now sit more to the side, leaving more background visible.
- Added Sprite Side button in the VN top bar.
- Added sprite size and sprite side controls in Settings.
- Added scene-aware sprite layout support for future builds.
- Reserved bigger visual impact for dedicated CG moments instead of everyday dialogue.


## New in v0.8
- Voice framework added.
- Arden lines can now use real audio files later.
- Browser text-to-speech fallback added for Arden as a prototype.
- Replay Voice button added to the VN top bar.
- Press V to replay the current/previous Arden voice line.
- Voice volume, voice mute, auto voice, and browser TTS fallback settings added.
- Voice Script screen added.
- Export Voice Script as JSON or CSV from inside the game.
- Audio folder structure added:
  - audio/voice/arden/
  - audio/music/
  - audio/ambience/
  - audio/sfx/

## Real voice file naming
For Arden, drop MP3 files into:
  audio/voice/arden/

Use the pattern:
  <scene_id>_<line_number>.mp3

Example:
  prologue_2.mp3

If the file is missing and browser TTS fallback is enabled, the game will use Chrome/browser speech synthesis temporarily.


## New in v0.9
- Ending Results screen added after each ending.
- New Game+ button added.
- Route Hints screen added.
- Skip Mode foundation added.
  - Top bar Skip button.
  - Press S to toggle Skip.
  - Skip stops at choices and CG popups.
- Press H to open Route Hints.
- Clear All Data button added in Settings.
- Ending Chaser achievement now unlocks when an ending is reached.
- CG popup flow improved: after closing an in-story CG, the next line renders cleanly.
- Small QA pass for endings, gallery flow, route hints, and replay comfort.


## New in v1.0 RC
- Release Candidate menu polish.
- Release Notes screen added.
- QA Checklist screen added.
- Build version and save schema added to saves.
- Save normalization/migration improved for older prototype saves.
- Main menu now identifies this as the stable private release candidate.
- Added RELEASE_CANDIDATE_NOTES.txt.
- JavaScript syntax checked during build.

## Recommended next step after v1.0 RC
Transparent Arden sprite cleanup.


## New in v1.0 RC2
- Main menu layout hotfix.
- Menu buttons now sit inside a dedicated menu panel instead of floating near the title.
- Added responsive layout rules so the title and menu do not overlap on smaller laptop screens.
- Story, saves, gallery, endings, voice framework, and route logic were left unchanged.


## New in v1.2 Transparent-Friendly Sprite Rebuild
- Built from stable v1.0 RC2, not the broken v1.1 cutout attempt.
- Replaced Arden's eight main dialogue sprites with a rebuilt transparent-friendly sprite set.
- Original RC2 sprite files backed up in assets/sprites/arden_original_backup_rc2/.
- Added assets/sprites/arden_v1_2_sprite_preview.png.
- Added assets/sprites/arden_v1_2_sprite_manifest.json.
- Story, saves, endings, route logic, CG gallery, menu layout, and voice framework remain intact.


## New in v1.2.1 Sprite Transparency Hotfix
- Removed the visible white/pale background from the approved Arden sprite set.
- Kept the same Arden look from v1.2.
- Added assets/sprites/arden_pre_hotfix_backup/.
- Added assets/sprites/arden_v1_2_1_transparency_preview.png.
- Added assets/sprites/arden_v1_2_1_transparency_manifest.json.
- No new sprite art was created for this hotfix.


## New in v1.2.3 Single Sprite Transparency Rebuild Test
- Rebuilt one sprite only from the clean original source image.
- Target sprite: arden_warm_neutral.png
- Added assets/sprites/single_sprite_rebuild_backup/.
- Added assets/sprites/single_sprite_transparency_rebuild_comparison.png.
- Added assets/sprites/single_sprite_rebuild_dark_preview.png.
- Added assets/sprites/single_sprite_transparency_rebuild_manifest.json.
- All other sprites remain unchanged.
- No new image generation was used for this rebuild test.


## New in v1.2.4 Full Sprite Transparency Rebuild Rollout
- Applied the successful transparency rebuild method to Arden's full main dialogue sprite set.
- Rebuilt each sprite from its clean original source image.
- Added assets/sprites/full_rebuild_rollout_backup/.
- Added assets/sprites/full_sprite_rebuild_rollout_preview.png.
- Added assets/sprites/full_sprite_rebuild_rollout_manifest.json.
- No new image generation was used for this rollout.


## New in v1.3 Mischief Route Expansion
- Expanded Mischief from a preview ending into a playable route path.
- Added Festival Side Path mischief scenes.
- Added final Mischief route-lock scene.
- Added Mischief Lantern Game scene.
- Added full Mischief Ending.
- Added 10 new Mischief achievements.
- Updated route hints, ending results text, release notes, and QA notes.
- No new image generation was used.


## New in v1.4 Warm Route Expansion
- Expanded Warm from a short ending into a fuller playable route path.
- Added warm Morning Café branch.
- Added final Warm route-lock scene.
- Added Late Inn Kitchen scene.
- Added Warm Lantern Promise scene.
- Expanded the Warm Ending.
- Added 10 new Warm achievements.
- Updated route hints, ending result text, QA notes, and release notes.
- No new image generation was used.


## New in v1.5 True Violet Route Expansion
- Expanded True Violet from a short ending into a fuller playable route path.
- Added pre-lock truth confession.
- Added True Violet route-lock scene.
- Added Garden Return / Witness / Scared-but-Stayed branches.
- Added Lantern of Names scene.
- Added named-truth branches.
- Added Storm Confession scene.
- Added Final Door scene.
- Expanded the True Violet Ending.
- Added 8 new True Violet achievements.
- Updated route hints, ending result text, QA notes, and release notes.
- No new image generation was used.


## New in v1.6 Route QA + Ending Balance Pass
- Rebalanced ending selection logic.
- Added routeDecisionDetails() to explain route outcomes.
- Added final-anchor protection for Warm, Mischief, and True Violet.
- Added expanded route-lock priority.
- Made avoidance flags clearly force Bittersweet.
- Added score pills and reasoning to Route Hints.
- Added Route QA Snapshot to Ending Results.
- Added route balance diagnostics to QA Checklist.
- Added V1_6_ROUTE_BALANCE_MATRIX.json.
- Added V1_6_STATIC_QA_VALIDATION_REPORT.txt.
- No new image generation was used.


## New in v1.7 Bittersweet Route Expansion
- Expanded Bittersweet from a short ending into a fuller playable route path.
- Added Bittersweet route-lock scene.
- Added station walk / not-ready / quiet-departure branches.
- Added departure platform choice scene.
- Added door-left-open / lantern-left-behind / honest-goodbye branches.
- Expanded the Bittersweet Ending.
- Added 7 new Bittersweet achievements.
- Updated route hints, ending result text, QA notes, and release notes.
- Added V1_7_BITTERSWEET_ROUTE_MAP.json.
- No new image generation was used.


## New in v1.8 Full Route QA Replay Pass
- Added Route Replay QA screen.
- Added route test shortcuts for Warm, Mischief, True Violet, and Bittersweet.
- Added Gallery / unlock audit shortcut.
- Added Clear QA Progress shortcut for clean-room testing.
- Added QA snapshot counts for CGs, endings, and achievements.
- Added V1_8_ROUTE_REPLAY_QA_GUIDE.json.
- Added V1_8_FULL_ROUTE_QA_REPLAY_CHECKLIST.txt.
- Added V1_8_STATIC_QA_VALIDATION_REPORT.txt.
- No new image generation was used.


## New in v1.9 Voice + Audio Integration Prep
- Added audio folder structure.
- Injected voiceId fields into Arden dialogue lines.
- Added recorded voice lookup with browser TTS fallback.
- Added Audio Settings screen.
- Added Voice Audit screen.
- Added volume controls.
- Added ambience slots.
- Added V hotkey / Replay Current Arden Line support.
- Exported Arden voice scripts:
  - V1_9_ARDEN_VOICE_SCRIPT.csv
  - V1_9_ARDEN_VOICE_SCRIPT.txt
- Added audio manifests:
  - V1_9_AUDIO_MANIFEST.json
  - V1_9_AUDIO_ASSET_MANIFEST.json
  - assets/audio/voice_manifest.json
  - assets/audio/audio_manifest.json
- Arden lines prepared: 214
- No new image generation was used.


## New in v1.9.1 Ambient + SFX Starter Pack
- Added actual starter ambience/SFX files.
- Added rain, storm, festival, train platform, café/kitchen, and secret garden ambience.
- Added soft menu theme starter.
- Added lantern chime, choice SFX, achievement chime, page turn, and soft button tap.
- Added SFX playback for choices, unlocks, achievements, endings, and advance clicks.
- Added ambience and SFX test buttons to Audio Settings.
- Fixed current voice replay and ambience helper references from v1.9.
- Recorded Arden voice is still not included yet.
- No new image generation was used.


## v1.9.1a Audio Settings Menu Hotfix
- Audio Settings, Voice Audit, and Route Replay QA are now visible from the main menu.
- Missing panel containers and render hooks were restored.
- v1.9.1 sound files remain intact.


## New in v1.9.2 Ambient Realism + Full Story Continuity Hotfix
- Rebuilt ambience loops to be longer, softer, and more natural-feeling.
- Rebalanced SFX so they are less harsh.
- Added fade-aware ambience switching between scenes.
- Fixed normal story continuity so Chapter 2 now continues into Chapter 3 instead of stopping at the old preview placeholder.
- Added V1_9_2_PLAYTHROUGH_LENGTH_ESTIMATE.txt.
- Added V1_9_2_AUDIO_REALISM_MANIFEST.json.
- No new image generation was used.


## New in v1.9.3 Foley UI + Organic Click SFX Pass
- Replaced generic starter clicks with warmer foley-style sounds.
- Added wooden UI taps, ceramic choice ticks, paper rustles, lantern glass chimes, achievement shimmers, mischief ticks, and rain-glass taps.
- Added multiple variations and randomized playback so repeated clicks feel less mechanical.
- Updated Audio Settings with new SFX test buttons.
- Preserved v1.9.2 ambience realism and full story continuity hotfix.
- No new image generation was used.


## New in v1.9.4 Audio Balance QA
- Added an Audio QA / Sound Test screen.
- Added quick tests for foley SFX and ambience.
- Added Cozy, Quiet, Ambience Focus, and SFX Check audio presets.
- Added scene-by-scene ambience mapping.
- Reduced default sound levels to be gentler over a full playthrough.
- Added V1_9_4_SCENE_SOUND_MAP.json and V1_9_4_SCENE_SOUND_MAP.csv.
- Preserved v1.9.3 foley SFX, v1.9.2 ambience realism, and full story continuity.
- No new image generation was used.


## New in v1.9.5 External Foley + License-Safe Audio Replacement Pass
- Added a Kenney CC0 external SFX bank for online playback.
- Added local organic SFX fallback, so the game still works offline.
- Added notification-specific sounds for save, load, errors, route locks, CG unlocks, achievements, and endings.
- Added Audio Settings toggles for external CC0 SFX and fallback behavior.
- Added LICENSES_AUDIO.txt.
- Added V1_9_5_EXTERNAL_AUDIO_DOWNLOAD_LIST.csv for future offline EXE packaging.
- This build references external online audio URLs; it does not embed third-party binary audio files locally.
- No new image generation was used.


## New in v1.9.6 Local Acoustic Audio Identity Pack
- Replaced the sci-fi-ish shimmer layer with a warmer local acoustic identity.
- Added bundled local acoustic ambience, music, and SFX under assets/audio/local/acoustic/.
- The game now uses local acoustic assets by default.
- Optional external CC0 SFX mode remains available but is off by default.
- Added tools/vendor_external_audio.py to download reviewed CC0/royalty-safe source files into local vendor folders on your own machine.
- Added V1_9_6_EXTERNAL_VENDOR_SOURCES.json and updated LICENSES_AUDIO.txt.
- This ZIP does not embed downloaded third-party binary audio files; it includes safe vendor tooling for future offline EXE packaging.


## New in v1.9.6a Audio Runtime Wiring Hotfix
- Local acoustic audio is forced by default.
- Old saved external-SFX settings are migrated back to local acoustic defaults.
- Added Enable Local Acoustic Sound on the main menu.
- Added Enable Sound in the gameplay top bar.
- Added Reset Local Acoustic Defaults and Run Local Audio Diagnostic.
- Audio tests now give feedback if browser playback is blocked.
- All v1.9.6 local acoustic WAV files are preserved.


## New in v1.9.7 Real Local Audio Vendor Pack
- Uses uploaded real audio packs locally.
- Converts selected OGG files to MP3 runtime copies for iPhone/browser compatibility.
- Runtime SFX now uses Kenney CC0 UI/Interface sounds first.
- Runtime ambience now uses OpenGameArt CC0 rain and wind-chime loops.
- Generated Python sounds are fallback only.
- Café and train ambience are intentionally silent until real matching ambience files are provided.
- Added V1_9_7_REAL_LOCAL_AUDIO_VENDOR_MANIFEST.json.
- Added V1_9_7_UPLOADED_AUDIO_INVENTORY.csv.


## New in v1.9.8 Real Local Music Integration Pack
- Added real local music tracks from uploaded MP3 files.
- Added scene-aware music selection and fade transitions.
- Music is enabled by default at low volume.
- Added Music Library and Music QA Tour in Audio QA.
- Added V1_9_8_REAL_LOCAL_MUSIC_MANIFEST.json.
- Added V1_9_8_MUSIC_INVENTORY.csv.
- Added V1_9_8_SCENE_MUSIC_MAP.csv.
- Added LICENSES_MUSIC.txt.
- Existing v1.9.7 real local SFX/ambience remains intact.


## New in v1.9.8a Slim Download Pack
- Smaller playable ZIP.
- Removed source/original audio folders and older nonessential docs.
- Removed generated acoustic fallback audio from packaged assets.
- Compressed runtime music and long ambience files.
- Kept real local SFX, ambience, scene music, routes, gallery, and endings.


## New in v1.9.8c Festival Outfit Continuity Hotfix
- Added festival-scene outfit continuity logic.
- Festival scenes now use only festival-safe Arden sprites.
- Wrong non-festival outfit leakage is blocked in Lantern Festival / Festival Side Path scenes.


## New in v1.9.8b Music Balance + Track Fit Pass
- Rebalanced scene music loudness with per-slot volume multipliers.
- Warm route now favors a softer romantic track fit.
- Mischief route now uses a more playful fit.
- Station / bittersweet scenes use quieter reflective music logic.
- Festival outfit continuity fix from v1.9.8c is preserved.


## New in v1.9.8d Kimono / Onsen Outfit Continuity Pass
- Extended festival kimono continuity into secret garden and late-night continuation scenes.
- Added a ryokan / onsen-safe outfit resolver so hot spring scenes keep the covered outfit.
- Prevented scene-driven sprite swaps from breaking outfit immersion during kimono / onsen moments.
- Preserved the v1.9.8b music balance and track-fit tuning.


## New in v1.9.9 Café + Train Ambience Completion / Final Audio Polish
- Added café/kitchen ambience: `assets/audio/local/final_ambience/cafe_kitchen_rainy_room_mix.mp3`.
- Added train/platform ambience: `assets/audio/local/final_ambience/train_platform_rainy_station_mix.mp3`.
- Both ambience loops are built from existing real local vendor material already in the project, not the old generated acoustic pack.
- Added ambience slot volume multipliers for better balance under music.
- Softened default music and SFX levels slightly.
- Preserved v1.9.8d kimono/onsen outfit continuity and v1.9.8b music fit improvements.


## v2.0 RC1 — Release Candidate Cleanup + Credits Pass
- Main menu cleaned for normal player flow.
- Developer/QA panels moved under Developer Tools.
- Credits & Sources screen rewritten.
- Old internal build reports removed from the root folder.
- v1.9.9 audio polish, v1.9.8d outfit continuity, and v1.9.8b music balance are preserved.


## v2.0 RC2 — Ending Reward Gallery Framework
- Added four Ending Reward CG placeholder slots:
  - Warm Ending Reward
  - Mischief Ending Reward
  - True Violet Ending Reward
  - Bittersweet Ending Reward
- Matching reward slots unlock automatically when each ending is reached.
- CG Gallery now separates Ending Rewards from Story CGs & Backgrounds.
- Ending Results now includes a Special Reward Unlocked card.
- Actual fan-service CG art can replace the placeholder files later without changing unlock logic.


## v2.0 RC3 — Mischief Reward CG Integration Pass
- Integrated the approved Mischief Ending Reward CG.
- The Mischief route now unlocks a real reward image instead of a placeholder.
- Warm, True Violet, and Bittersweet rewards still use placeholders for now.


## v2.0 RC3.1 — Reward Gallery Polish Pass
- Added dedicated Ending Rewards screen.
- Added main-menu Ending Rewards button.
- Added reward progress tracking and final-art status badges.
- Improved locked-state copy and reward navigation.
- Mischief reward is marked Final CG Live.
- Warm, True Violet, and Bittersweet reward slots remain ready for final art.


## v2.0 RC4 — Warm Reward CG Integration Pass
- Integrated the approved Warm Ending Reward CG.
- Warm route now unlocks a real reward image instead of a placeholder.
- Warm and Mischief are both marked Final CG Live.
- True Violet and Bittersweet still use placeholders for now.


## v2.0 RC5 — True Violet Reward CG Integration Pass
- Integrated the approved True Violet Ending Reward CG.
- True Violet route now unlocks a real reward image instead of a placeholder.
- Warm, Mischief, and True Violet are marked Final CG Live.
- Bittersweet still uses its placeholder for now.


## v2.0 RC6 — Bittersweet Reward CG Integration Pass
- Integrated the approved Bittersweet Ending Reward CG.
- Bittersweet route now unlocks a real reward image instead of a placeholder.
- Warm, Mischief, True Violet, and Bittersweet are all marked Final CG Live.
- The Ending Rewards set is now complete.


## Violet Lanterns v2.0 — Final Presentable Release Build
- Main menu cleaned and fix-pass wording removed.
- Release Notes and Developer Tools moved into Extras.
- Ending Result screen cleaned to feel player-facing.
- All four Ending Reward CGs are Final CG Live.
- This is the clean private v2.0 build.


## Violet Lanterns v2.0.1 — iPhone Mobile Fit Build
- Added proportional layout rules for iPhone and narrow mobile screens.
- Main menu, dialogue box, sprites, choices, panels, galleries, and CG viewer now scale down for smaller displays.
- Added safe-area and dynamic viewport handling for Safari.
- Added manifest.webmanifest, iPhone app icon assets, and .nojekyll for GitHub Pages.
- All v2.0 content and final Ending Reward CGs are preserved.


## Violet Lanterns v2.0.2 — iPhone Landscape Big Sprite Build
- Tuned the iPhone/mobile layout for landscape-first play.
- Enlarged Arden's sprite scaling in landscape mode.
- Adjusted dialogue, choices, HUD, menu, panels, and CG viewer for landscape proportions.
- Manifest orientation set to landscape for Home Screen/PWA installs.
- v2.0.1 safe-area and Safari viewport fixes are preserved.
