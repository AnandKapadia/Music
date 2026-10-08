# Middle Flute Airy - Body 450

A **listening trial, awaiting user feedback**, saved on 2026-10-08 as one of two comparison versions. It starts from the original **Middle Flute Airy** sound currently on Kudmayi track 3 and adds a gentle **450 Hz, +1 dB, Q 0.71** parametric boost as the final insert.

The paired version is **Middle Flute Airy - Harmonics 900**. The two boosts are alternatives: the 900 Hz version does **not** also contain the 450 Hz boost. “Body” and “Harmonics” describe the comparison intent; whether a frequency affects a fundamental or harmonic depends on the note played.

## Saved processing

| Order | Effect | State / settings |
| --- | --- | --- |
| 1 | Compressor | Bypassed |
| 2 | AUHipass | Bypassed |
| 3 | PlatinumVerb | On; predelay 28 ms; decay 2.30 s; high cut 6000 Hz; spread 100%; dry 100%; wet 25% |
| 4 | Single Band EQ — Parametric | On; 1700 Hz; +1.5 dB; Q 0.51 |
| 5 | Single Band EQ — High Shelf | On; 4450 Hz; +1.5 dB; Q 0.71 |
| 6 | Single Band EQ — Parametric | On; **450 Hz; +1.0 dB; Q 0.71** |

These trials use the original **+1.5 dB high shelf**, not the −1 dB Softer Air shelf. They do not include the Bass Flute - Warm Body 350 Hz boost. Earlier saved presets remain unchanged.

The current session Ambience control displayed **10%** before the comparison edits. Native routing is `Ambience/0.2s Long Ambience`, with send scalar `0.08503936976194382`. The scalar is preserved exactly and is not a percentage or dB value. It matches the original Middle Flute Airy native patch despite the differing observed UI percentage; both the observed display and saved payload are recorded without inferring a conversion.

Additional reverb send and master echo/reverb sends remain zero. Noise gate is off. Compressor and AUHipass are bypassed; no compression or limiting is added. PlatinumVerb's dry/wet controls are independent.

## Recall and compare

1. The local Kudmayi project contains the same audio regions on the original, Body 450 and Harmonics 900 comparison tracks. Keep the accompaniment unchanged and **unmute only one flute version at a time**.
2. All three flute versions were matched at **−2.8 dB**, centered. Leave monitoring off during recorded playback and compare the same passage.
3. To isolate this preset's EQ change, bypass its final **450 Hz Single Band EQ**, then enable it again. Other EQ and reverb settings stay in place.
4. For later recall, select **Library → User Patches → Middle Flute Airy - Body 450**. The native patch was saved with **mute on**, so unmute the desired track after recall. Monitor only one track if using it live.
5. On another Mac, copy the entire `.patch` folder to `~/Music/Audio Music Apps/Patches/Audio/`. Reopen GarageBand if needed.

The presets use mono Scarlett input 1 and the M160 capture setup. Hardware gain, routing and physical placement were not freshly checked for this comparison. The recording's flute key/register is not independently established in these settings files.

## Preservation

The source session is **Kudmayi - Original Pitch - Middle Flute Airy.band**, stored locally. Its recording regions, backing and all audio stay out of Git. The artistic reference inherited from Middle Flute Airy is the [Ranjha flute cover](https://www.youtube.com/watch?v=N9OOJjfTjM8), especially 0:05–0:15; its production chain is unknown, and the assistant has not directly auditioned its audio.

`Middle Flute Airy - Body 450.patch` is a byte-for-byte copy of the native saved User Patch. `settings.json` records verified controls; `manifest.sha256` verifies the three small native files. The native channel name may retain “Bansuri Csharp M160 - Ranjha Smooth Presence”; the Library title identifies this comparison version.
