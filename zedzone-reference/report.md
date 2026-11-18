# Zed Zone — character look and animation reference

Source: "I Killed a Zombie, but Then This Thing Came Out of It | Zed Zone" (Gameoneer), https://youtu.be/dny1ABAMxqU, 1:21 long, watched at 1080p (1920 × 1080, 30 fps). Frames were stepped one video frame (1/30 s) at a time where noted.

Timestamps are mm:ss, with decimals where a single frame matters (00:20.97 = 20.97 s). All pixel measurements are in 1080p video pixels.

**Limits of this footage.** The clip is one daytime, overcast, snowy roadside fight. The player only uses a fire axe. There is no gunfire, reloading, night, interior, door or car anywhere in the clip, so everything that depends on those is marked "can't tell".

---

## 1. Scale

- **Player height on screen:** about 210–230 px, roughly 1/5 of the screen height (00:04, 00:40).
- **Ground tiles:** the pavement slabs at 00:04 are about 230 px from joint to joint, so the player is about one slab tall.
- **Fence:** the grey roadside rail fence at 00:40 is about 120 px tall on screen. The player standing in front of it is roughly 1.7–1.8× that.
- **Other objects:** the yellow utility trailer at 00:04–00:06 is about as tall on screen as the player. This is a rough reading from the full frame.
- **Door and car:** none appear in the clip, so I can't compare against them.
- **Zoom level:** the in-game zoom value isn't shown. The gameplay camera stays at one zoom from 00:00 to 01:16, following the player with some lag, so the player isn't always centred (00:11). At death (01:16.6–01:20) the camera zooms in roughly 6–7×.
- **Is it pixel art?** Yes. Square art pixels are clearly visible in the death close-up (01:17–01:20). There, one art pixel is about 18–20 screen px on the ground and on the vertical axe.
- **Art pixel size during play:** about 2–3 screen px per art pixel. The stepped edges on the sneakers at 00:04 are the clearest place to see it. Video compression blurs the edges, so I can't pin the size exactly.

## 2. Proportions

- **Head:** about 1/6 of body height without hair (00:04, 00:20.9). The player's big curly hair makes the head read larger, nearer 1/4.5 including the hair.
- **Legs:** hip to sole is about 40% of total height (00:04).
- **Shoulders:** in the back view at 00:11 and 00:40, shoulders plus the backpack span about 1/3 of the height. I couldn't measure bare shoulder width, because the backpack covers it.
- **Feet:** the white sneakers are drawn slightly large and chunky, which anchors the figure (00:04).
- **Overall look:** semi-realistic. Adult proportions are slightly stylised through the chunky shoes, big hair and oversized backpack. It is not chibi.

## 3. Camera angle

- **A hybrid view.** The ground, road markings, fences and snow patches are drawn close to straight down (00:08–00:16, 00:40). Characters are drawn **upright, as side or three-quarter views**, as if seen from the side, standing on that top-down ground (00:04, 00:17, 00:20.9).
- **Top of the head:** barely visible. You see the side of the head and the front or side of the body, not the scalp (00:20.87–00:20.97).
- **Shoulders:** read from the side, not from above.
- **Faces:** visible as a profile, with skin tone, a nose bump and a dark eye or eyebrow mark (00:20.87–00:20.97). There's no detailed facial feature work.
- **In short:** side-on to three-quarter characters, not top-down characters.

## 4. Facing and turning

- **Directions seen:**
  - Right-facing profile (00:00–00:02, 00:17, 00:20.9).
  - Left-facing profile (00:03, 00:05).
  - Back view walking up-screen (00:11, 00:40).
  - Back or away view while aiming (01:01.6).
  - I didn't see a clear front view facing down-screen.
  - So at least 4 directions, but I can't tell whether there are 4, 8, 16 or smooth facing.
- **Mirroring:** the left and right profiles look like mirror images. The backpack is behind the body in both, with the axe on the facing side (00:00 vs 00:03). I couldn't find an asymmetric detail to prove they are exact mirrors.
- **Aiming:**
  - The weapon and arms rotate separately from the body. At 01:01.60–01:01.73 the body faces up and away while the axe points up-right at a steadily changing angle.
  - The weapon passes through many in-between angles (00:20.87–00:20.97), which suggests a separate weapon part rotated by the engine rather than a few drawn frames.
  - The whole body also flips to face the target side (00:17–00:21, facing the zombie on the right).
- **Legs walking one way while the body aims another:** possibly, but not certain. Around 00:17–00:18.5 the player seems to drift down-left while facing right, but the camera lag makes it hard to confirm.

## 5. Animation

Counts are video frames at 30 fps. The game's own frame rate isn't known, so "distinct poses" is my count of visible pose changes.

### Player

- **Idle (00:00–00:01.5):** facing right with the axe on the back. I saw no visible change across 1.5 s, so I can't count idle frames.
- **Walk:**
  - One full stride (left and right step) takes about 0.4 s, or 12 video frames (00:04.87–00:05.37 side view, 00:11.0–00:11.4 back view).
  - The pose changes roughly every 1–2 video frames, so an estimated 6–8 distinct poses per stride.
  - The free arm swings forward with a loose fist (00:05.0).
  - The body leans slightly forward.
  - The hair streams backwards while moving (00:02, 00:05).
  - There's no obvious head bob.
- **Run:** I couldn't tell a sprint apart from a walk in this clip.
- **Overhead axe chop (00:20.53–00:21.17), about 0.6 s:**
  1. *Wind-up* (00:20.53–00:20.70, about 5 frames): the axe lifts from a low diagonal to straight up.
  2. *Hold* (00:20.70–00:20.83, about 4 frames): axe vertical.
  3. *Downswing* (00:20.87–00:20.97, 4 frames): the axe rotates forward through roughly 20°, 40°, 60° to horizontal, with the arms extending.
  4. *Impact* (00:20.97): the axe is horizontal and a blood burst appears at the zombie.
  5. *Follow-through* (00:21.00–00:21.07, 3 frames): the axe points down and forward, below the hands.
  6. *Recovery* (00:21.10+): back to vertical.
  - **How the swing is shown:** mostly by the rotating axe and the blood burst. The downswing frames (00:20.87–00:20.97) have no motion smear, but one frame on the return (00:21.10) shows a short dark smear arc beside the axe head (see the swing filmstrip, 10th frame).
- **Horizontal swing (01:02.20–01:02.33):** shown with a **dark curved smear arc** over the player's head at 01:02.333. Smears are dark and short-lived (one frame each time I saw one), not bright or white.
- **Shooting, recoil, muzzle flash, reload:** none in the clip. Can't tell.
- **Picking up or searching:** at 01:06, a dead body gets a green outline with "Butcher" and "Loot" prompts. No looting animation plays in the clip, so I can't describe it.
- **Getting hit:**
  - A red tendril strikes the player at 01:01.87–01:02.0.
  - The screen edge flashes red (01:02, 01:11–01:15).
  - An "I'm bleeding" text bubble appears above the player (00:56).
  - The HUD body diagram turns red on the torso (00:52).
  - I saw no clear flinch pose or white hit flash on the sprite.
- **Death (01:16.6–01:20.2):**
  - The camera zooms in hard, the image turns greyscale, and black bars appear.
  - The player collapses and ends lying on their side, with the axe on the ground beside them (01:19.5).
  - A "DEFEATED" screen follows (01:21).
  - I couldn't count the collapse frames through the camera move.

### Zombies

- **Walk:** hunched forward, head low, a shuffling, short-stepped gait (00:17–00:19). I couldn't count frames, because they are small and partly hidden by snow and grass.
- **Attack:** I didn't see a clear zombie melee pose.
- **Hit reaction:** the zombie rocks back while blood sprays from the head (00:20.97–00:21.3).
- **Knocked down:** the zombie drops low and folds over (00:23.5).
- **Death or transformation:** at 00:24–00:25 the yellow-coat zombie bursts into a red flesh mass, which rises as a red flesh creature with finger-like tendrils (00:25, 00:34). Later dead zombies lie flat and stay on the ground (00:38, 01:06).

## 6. Outline

- **Present:** yes, a dark, near-black outline. It's clearest on the axe (00:20.87–00:20.97, 01:17, 01:19.5) and around the sneakers and backpack (00:04).
- **Colour:** dark or near-black everywhere I could check. It is not a coloured (darker-hue) outline.
- **Thickness:** about 1 art pixel at gameplay zoom. In the death close-up (01:19.5), the outline on the diagonal axe looks thinner than one art pixel and runs smoothly along the diagonal instead of stepping. That suggests the engine draws it, not the sprite, but I can't confirm.
- **Coverage:** it appears on the outer silhouette. Inner edges, such as the arm over the jacket, aren't clearly outlined. It's hard to see against the black jacket.

## 7. Shading

- **Tones per colour:** roughly 3 for clothing (highlight, mid, shadow). The red backpack and brown trousers are the clearest examples (00:04, 00:05). Skin has about 2–3 tones (00:20.9).
- **Gradients:** shading looks soft and slightly painterly, not hard-banded. Some of that softness may come from the video compression.
- **Light direction:** from the right. Body shadows fall to the left and slightly up-screen (00:04, 00:20.9), and the right-hand edges of the backpack and trousers are lighter.
- **Rim light and dithering:** I saw no clear rim light. Dithering can't be confirmed through the compression.
- **Night or dark:** the clip is all daytime ("DAY 1" at 00:00), so I can't tell.

## 8. Colour

- **Ground:** desaturated olive, grey asphalt, dull brown grass, with white snow patches (00:08–00:46).
- **Player:**
  - Dark curly hair and medium-brown skin.
  - Black or very dark jacket and brown trousers.
  - White sneakers.
  - A large dark-red backpack and an orange-red fire axe.
  - The red and orange accents are the most saturated colours on screen (00:04, 00:05).
- **Zombies:**
  - A yellow coat with dark blood spots and a dark head (00:17–00:21).
  - Pale grey skin and hair in muted clothing (00:40).
  - Grey and dusty-pink clothing (00:38, 00:56).
  - Zombie skin reads as grey or grey-green.
- **How characters stand out:** saturated accents on otherwise muted clothing, the dark outline, and a soft shadow underneath. They read best on grey asphalt and snow, and least well against olive grass (00:11).

## 9. Gear on the body

- **Held weapon:** drawn in the hands (00:05, 00:17, 00:20). When not in use, it's carried on the back, diagonally across the backpack (00:00–00:02.5). The switch from back to hands happens between 00:02.5 and 00:05.
- **Switching weapons:** only the axe is used, so I can't tell whether other weapons are drawn differently. The HUD has slots for Primary 1 (the axe), Primary 2, Knife, Secondary, Skill and Throwable.
- **Backpack:** always visible on the body (00:00–01:16).
- **Hats, armour, clothing changes:** none seen, so I can't say whether characters work like a paper doll. The body diagram at 00:52 is a damage display, not an equipment view.

## 10. Shadows

- **Shape:** elongated, a stretched version of the silhouette (00:04, 00:20.9).
- **Direction:** to the left and slightly up-screen.
- **Softness:** soft-edged.
- **Darkness:** medium, semi-transparent dark grey.
- **Time of day:** the clip covers one time of day, so I can't tell whether shadows move.

## 11. Zombies

- **Distinct looks:** at least 3, plus one creature:
  - Yellow coat with a dark head (00:17–00:23).
  - Pale grey skin and hair (00:40).
  - Grey and pink clothing (00:38, 00:56).
  - A red flesh creature with long tendrils (00:25–01:16).
- **Build:** ordinary adult human builds, similar to the player.
- **Posture and gait:** hunched, with heads forward and low and a shuffling walk (00:17–00:19, 00:40).
- **Damage:** blood-spotted clothing (00:19). After hits they are covered in red (00:24). Exact wound detail can't be read at this zoom.

## 12. Combat effects

- **Blood spray:** a burst of dark-red pixel clusters on impact (00:20.97, 00:24).
- **Blood on the ground:** drops and splats stay on the ground and build up. By 01:10 the fight area is covered (00:38–01:16).
- **Hit flash:** none seen on sprites. The player's damage shows as a red screen-edge flash (01:02, 01:11–01:15).
- **Knockback:** the zombie drops after hits (00:23.5). I couldn't measure a clear slide-back distance.
- **What's left on the ground:** bodies stay where they fall (00:38). A lootable body gets a green outline (01:06).
- **Creature attack:** a long red tendril line from the flesh creature (00:34, 01:01.9).
- **Bullet tracers and muzzle flash:** none in the clip, so I can't tell.

## 13. Characters in the world

- **Tall grass:** it covers the lower legs. Grass blades are drawn in front of the player's legs (00:00–00:02), and the effect is also visible at 00:40.
- **Busy ground:** characters stay readable on grey asphalt and snow, but blend into olive grass (00:11).
- **Snow:** snow patches and falling snowflakes from 00:34 don't hide characters.
- **Dark:** there's no night or dark footage, so I can't tell.

## 14. The five things that most define the look

1. **Upright side and three-quarter characters on a straight-down world.** The figures stand up off the ground like side-view sprites (00:04, 00:20.9).
2. **Large, semi-realistic pixel figures.** About 1/5 of the screen tall (around 220 px), with fine art pixels (about 2–3 screen px each) and soft, near-painterly shading (00:04, 01:19.5).
3. **Muted clothing with one or two saturated accents.** The red backpack and orange axe pop against a desaturated ground, separated by a thin dark outline and a soft directional shadow (00:04).
4. **Weapons as separate rotating parts.** The weapon swings and aims through smooth angles in the hands, and sits stowed on the back when not in use (00:00, 00:20.87–00:21.1, 01:01.6).
5. **Heavy, persistent gore.** Blood bursts on every hit, splats build up on the ground, and bodies stay down (00:20.97, 00:38–01:16).

---

## Screenshots in this folder

Each file name starts with its timestamp. Images are cropped from the 1080p frames and enlarged with nearest-neighbour scaling, so the pixels stay sharp. Filmstrips put consecutive video frames side by side, left to right.

- `00m00s-player-idle-facing-right-in-tall-grass.png`
- `00m02s-player-walking-right-axe-on-back.png`
- `00m03s-player-standing-facing-left-axe-stowed.png`
- `00m04s-full-frame-zoom-reference.png`
- `00m04s-player-side-view-scale-vs-pavement-slabs.png`
- `00m04s-player-walk-cycle-side-filmstrip.png`
- `00m05s-player-walking-left-axe-in-hands.png`
- `00m11s-player-walking-up-back-view.png`
- `00m17s-player-axe-ready-and-yellow-zombie.png`
- `00m19s-zombie-yellow-coat-closeup-infected-label.png`
- `00m20s-axe-impact-frame-blood-spray.png`
- `00m20s-player-overhead-axe-swing-filmstrip.png`
- `00m23s-zombie-knocked-down.png`
- `00m24s-zombie-bursting-into-blood.png`
- `00m25s-flesh-creature-emerging.png`
- `00m34s-creature-tendril-attack-on-player.png`
- `00m38s-zombie-variety-standing-and-down.png`
- `00m40s-player-back-view-fence-and-pale-zombie.png`
- `00m52s-paper-doll-body-damage-hud.png`
- `00m56s-player-bleeding-and-zombies.png`
- `01m01s-axe-aimed-independently-of-body.png`
- `01m02s-horizontal-swing-smear.png`
- `01m06s-loot-highlight-on-corpse.png`
- `01m17s-death-closeup-greyscale-legs-and-axe.png`
- `01m19s-death-player-lying-down.png`
