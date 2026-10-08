# Bass Flute - Warm Body

A **listening trial, awaiting user feedback**, saved on 2026-10-08. The user liked the preceding Softer Air sound and requested “more body on the deep side,” then clarified that the name should be for a **bass flute**. The bass bansuri's key was not confirmed in this session.

## What changed

A broad **350 Hz, +2 dB, Q 0.71** parametric EQ replaces the previously flat final Channel EQ. It is intended to add low-register body while preserving the softer breath detail and current reverb. This was the sole new processing edit for the Warm Body trial.

The **Middle Flute Airy** and **Middle Flute Airy - Softer Air** native presets remain available and unchanged. Softer Air's documentation now records the user's positive feedback and request for this next refinement.

## Saved processing

| Order | Effect | State / settings |
| --- | --- | --- |
| 1 | Compressor | Bypassed |
| 2 | AUHipass | Bypassed |
| 3 | PlatinumVerb | On; predelay 28 ms; decay 2.30 s; high cut 6000 Hz; spread 100%; dry 100%; wet 25% |
| 4 | Single Band EQ — Parametric | On; 1700 Hz; +1.5 dB; Q 0.51 |
| 5 | Single Band EQ — High Shelf | On; 4450 Hz; −1.0 dB; Q 0.71 |
| 6 | Single Band EQ — Parametric | On; **350 Hz; +2.0 dB; Q 0.71** |

Ambience displayed **10%** (Smart Control value 0.1000000059604645) before this edit and was preserved. The user had independently changed it since Softer Air was saved. Native routing is `Ambience/0.2s Long Ambience`, with send scalar `0.07086615264415741`. The UI value and native scalar are documented separately: the scalar is not a percentage or dB value, and it happens to match the prior saved Softer Air patch despite the different UI display. The complete native patch was copied unchanged.

Additional reverb send and master echo/reverb sends are zero. Noise gate is off; no compression or limiting is applied. PlatinumVerb's dry and wet controls are independent.

## Recall and compare

1. Select the flute track and choose **Library → User Patches → Bass Flute - Warm Body**. It is installed on this Mac.
2. To isolate the body change, bypass only the final **350 Hz Single Band EQ**, then enable it again for this saved sound. Keep the same phrase and listening level for the comparison.
3. Switching to the older saved Softer Air preset also recalls its earlier ambience state, so it is not an isolated EQ comparison.
4. On another Mac, copy the entire `.patch` folder to `~/Music/Audio Music Apps/Patches/Audio/`. Reopen GarageBand if needed.

The session uses mono Scarlett input 1, centered pan, monitoring on and feedback protection off for headphones. Flute fader −2.8 dB, backing −19.5 dB and master 0 dB were already set before this refinement. The accompaniment and recordings were preserved. Recheck recording headroom and listening balance separately. Hardware gain and routing are not part of the patch and were not freshly verified. Keep the M160 outside the direct breath stream.

## Provenance and preservation

The source is the local **Kudmayi - Original Pitch - Middle Flute Airy.band** session. Its project, backing and any recordings remain local and are excluded from Git. The full pre-change project backup is `Documents/ChatGPT/Music/.audio-work/backups/Kudmayi - before bass warm body 20261008-114457.band`.

The artistic reference inherited from Middle Flute Airy is the [original Ranjha flute cover](https://www.youtube.com/watch?v=N9OOJjfTjM8), especially 0:05–0:15. Its production chain is unknown, and the assistant has not directly auditioned the audio.

`Bass Flute - Warm Body.patch` is a byte-for-byte copy of the native saved User Patch. `settings.json` records verified controls; `manifest.sha256` verifies the three small native preset files. The native channel name may still read “Bansuri Csharp M160 - Ranjha Smooth Presence”; the Library name identifies the new bass-flute variant.
