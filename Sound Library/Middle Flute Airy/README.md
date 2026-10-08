# Middle Flute Airy

Approved from **take #03** on 2026-10-07: “I love the sound of this.” C# middle bansuri recorded through the beyerdynamic M160 into Scarlett input 1. The sound keeps the natural low-note body and adds broad presence, a little upper-frequency air, hall reverb, and short ambience.

## Reference target

The user confirmed **0:05–0:15 of the original [Ranjha – Flute Cover by Divyansh Shrivastava](https://www.youtube.com/watch?v=N9OOJjfTjM8)** as the desired flute sound. This is the target for further comparison; it does not establish an exact sonic match or reveal the reference’s production chain, which remains unknown. The assistant has not directly auditioned the audio.

**Middle Flute Airy remains the approved take #03 preset.** Documenting this target leaves every saved effect value and the native patch unchanged.

## Saved processing

The insert order matters. Compressor and AUHipass remain in the patch but are bypassed.

| Order | Effect | State / settings |
| --- | --- | --- |
| 1 | Compressor | Bypassed |
| 2 | AUHipass | Bypassed |
| 3 | PlatinumVerb | On; predelay 28 ms; decay 2.30 s; high cut 6000 Hz; spread 100%; dry 100%; wet 25% |
| 4 | Single Band EQ — Parametric | On; 1700 Hz; +1.5 dB; Q 0.51 |
| 5 | Single Band EQ — High Shelf | On; 4450 Hz; +1.5 dB; Q 0.71 |

Ambience Smart Control is **12%**, routed to `Ambience/0.2s Long Ambience`. The native send scalar is `0.08503936976194382`; it is not a percent or dB value. Additional reverb send is zero. Master echo/reverb sends are zero, and the noise gate is off. No compression or limiting is applied. PlatinumVerb's dry and wet values are independent controls, not a single crossfade.

## Recall in GarageBand

1. Select an empty mono audio track. Open Library (`Y`) and choose **User Patches → Middle Flute Airy**. It is already installed on this Mac.
2. On another Mac, copy the entire `Middle Flute Airy.patch` folder into `~/Music/Audio Music Apps/Patches/Audio/`, then reopen GarageBand if it does not appear in User Patches. The patch uses built-in Apple effects and ambience resources.
3. Select the Scarlett as input/output, use mono input 1, and check that the mic is monitored by only this track. Keep the Scarlett's direct mic monitoring muted when using GarageBand effects.
4. The approved take used a centered track at 0 dB. Set the backing level by ear; its fader is not part of this sound preset. Hardware gain and master processing are separate from the patch.

The M160 preamp was last observed at 44 dB with 48V, Air, Inst, and Clip Safe off; these hardware values were not freshly rechecked for this save. Keep the microphone outside the direct breath stream and check headroom before a new take. A patch cannot reproduce differences in breath, flute, distance, or room.

## Source and preservation

Source filename: `Bansuri Csharp M160 - Ranjha Smooth Presence#03.wav`. The source recording stays in the local GarageBand project and is not included here.

`Middle Flute Airy.patch` is a byte-for-byte copy of the saved User Patch. `settings.json` documents verified controls; `manifest.sha256` checks the three native preset files. The native patch preserves the rest of the saved plug-in state and may retain the older internal channel name “Bansuri Csharp M160 - Ranjha Smooth Presence”; the Library preset name is **Middle Flute Airy**.
