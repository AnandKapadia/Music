# Bass Flute

**User-approved on 2026-10-08** as the retained bass-flute sound: “I do like this, can you save this as the bass flute option? Only retain the middle and the bass, all the middle settings are not needed”.

This is the accepted Outer Lift Bass tonal chain, saved under the simple name **Bass Flute**. The original **Middle Flute Airy** is the other retained sound and remains unchanged. The bass bansuri's exact key was not confirmed for this save.

## Saved processing

| Order | Effect | State / settings |
| --- | --- | --- |
| 1 | Compressor | Bypassed |
| 2 | AUHipass | Bypassed |
| 3 | PlatinumVerb | On; predelay 28 ms; decay 2.30 s; high cut 6000 Hz; spread 100%; dry 100%; wet 25% |
| 4 | Single Band EQ — Parametric | On; 1700 Hz; +1.5 dB; Q 0.51 |
| 5 | Single Band EQ — High Shelf | On; 4450 Hz; +1.5 dB; Q 0.71 |
| 6 | Single Band EQ — Low Shelf | On; **300 Hz; +3.0 dB; Q 0.71** |
| 7 | Single Band EQ — High Shelf | On; **6000 Hz; +1.5 dB; Q 0.71** |

The last two shelves distinguish the tonal chain from the original middle-flute sound. There is no 350 Hz, 450 Hz or 900 Hz trial boost in this preset. The 6000 Hz shelf is additional to the retained 4450 Hz shelf.

Current session Ambience displayed **10%**. Native routing is `Ambience/0.2s Long Ambience`, with send scalar `0.08503936976194382`. The scalar is not a percentage or dB value; the saved native payload and observed UI display are recorded separately. Additional reverb send and master echo/reverb sends are zero. Noise gate is off; no compression or limiting is applied. PlatinumVerb's dry and wet values are independent controls.

## Recall

1. Select a mono audio track and choose **Library → User Patches → Bass Flute**. It is installed on this Mac.
2. Use mono Scarlett input 1 for the M160. The patch was saved **unmuted**, with **monitoring off** for playback. For live playing, enable monitoring on only the desired mic track; keep Scarlett direct mic monitoring muted to avoid doubling.
3. The user set the flute fader to **0 dB** before this final save. Set accompaniment balance separately and check recording headroom. Hardware gain, master level and physical placement are not part of this tone preset.
4. On another Mac, copy the entire `Bass Flute.patch` folder to `~/Music/Audio Music Apps/Patches/Audio/`, then reopen GarageBand if needed.

Keep the M160 outside the direct breath stream. Hardware gain and routing were not freshly checked for this save. A preset does not reproduce differences in breath, flute, distance or room.

## Preservation

The source is the local **Kudmayi - Original Pitch - Middle Flute Airy.band** session. Recordings, backing and projects remain local and are excluded from Git. Intermediate sound-library folders and native User Patches were copied and hash-verified in an ignored local archive under `.audio-work/retired-presets/` before retirement. Their earlier tracked versions remain available in Git history; the active library now has only **Middle Flute Airy** and **Bass Flute**.

The inherited artistic reference is the [Ranjha flute cover](https://www.youtube.com/watch?v=N9OOJjfTjM8), especially 0:05–0:15. Its production chain is unknown, and the assistant has not directly auditioned its audio. User approval of this bass sound is not an exact-match claim.

`Bass Flute.patch` is a byte-for-byte copy of the final native saved User Patch. `settings.json` records verified controls, and `manifest.sha256` verifies the three small native files. The native channel name is **Bass Flute**.
