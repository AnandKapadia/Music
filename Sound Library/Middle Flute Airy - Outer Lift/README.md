# Middle Flute Airy - Outer Lift

A **listening trial, awaiting user feedback**, saved on 2026-10-08. The user felt the body was pretty good and requested another option lifting frequencies outside that area. This trial adds a small low-frequency shelf and an additional high-frequency shelf to the current original **Middle Flute Airy** sound.

## What changed

- **300 Hz low shelf, +1.0 dB, Q 0.71**.
- **6000 Hz high shelf, +1.5 dB, Q 0.71**.

The 450 Hz comparison insert was replaced by the low shelf while creating this track. There is **no 450 Hz or 900 Hz comparison boost** in this preset. The existing **1700 Hz +1.5 dB bell** and **4450 Hz +1.5 dB high shelf** remain, so the new 6000 Hz shelf is additional to the original high shelf. This is an independent option; the earlier original, Softer Air, Warm Body, Body 450 and Harmonics 900 presets remain unchanged.

## Saved processing

| Order | Effect | State / settings |
| --- | --- | --- |
| 1 | Compressor | Bypassed |
| 2 | AUHipass | Bypassed |
| 3 | PlatinumVerb | On; predelay 28 ms; decay 2.30 s; high cut 6000 Hz; spread 100%; dry 100%; wet 25% |
| 4 | Single Band EQ — Parametric | On; 1700 Hz; +1.5 dB; Q 0.51 |
| 5 | Single Band EQ — High Shelf | On; 4450 Hz; +1.5 dB; Q 0.71 |
| 6 | Single Band EQ — Low Shelf | On; **300 Hz; +1.0 dB; Q 0.71** |
| 7 | Single Band EQ — High Shelf | On; **6000 Hz; +1.5 dB; Q 0.71** |

The current session Ambience control displayed **10%** and was preserved. Native routing is `Ambience/0.2s Long Ambience`, with send scalar `0.08503936976194382`. The scalar is not a percentage or dB value; the native value and observed UI display are documented separately without inferring a conversion.

Additional reverb send and master echo/reverb sends remain zero. Noise gate is off. Compressor and AUHipass are bypassed; no compression or limiting is added. PlatinumVerb's dry and wet controls are independent.

## Recall and compare

1. The local Kudmayi project has **Airy - Outer Lift** as a separate comparison track, using the existing flute regions and unchanged timing. Keep accompaniment unchanged and **unmute only one flute version at a time**.
2. This version uses the same **−2.8 dB** fader and centered pan as the other comparison versions. Monitoring is off for playback. Compare the same passage at the same listening level.
3. To isolate this change, bypass both final shelf plug-ins, then enable both again. The earlier EQ and reverb remain in place.
4. For recall, choose **Library → User Patches → Middle Flute Airy - Outer Lift**. The native patch was saved with **mute on**; unmute the desired track after recall.
5. On another Mac, copy the entire `.patch` folder to `~/Music/Audio Music Apps/Patches/Audio/`. Reopen GarageBand if needed.

The preset uses mono Scarlett input 1 and the M160 capture setup. Hardware gain, routing and microphone placement were not freshly verified for this comparison. The recording's flute key/register is not independently established in these settings files. The user's comment about body does not select a favorite between the earlier 450 Hz and 900 Hz trials, and does not approve this new version before audition.

## Preservation

The source session is **Kudmayi - Original Pitch - Middle Flute Airy.band**, stored locally. Recordings, accompaniment and the project stay out of Git. The inherited artistic reference is the [Ranjha flute cover](https://www.youtube.com/watch?v=N9OOJjfTjM8), especially 0:05–0:15; its production chain is unknown, and the assistant has not directly auditioned its audio.

`Middle Flute Airy - Outer Lift.patch` is a byte-for-byte copy of the native saved User Patch. `settings.json` records verified controls; `manifest.sha256` verifies the three small native files. The native channel name is **Airy - Outer Lift**.
