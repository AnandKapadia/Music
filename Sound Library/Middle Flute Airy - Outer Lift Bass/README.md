# Middle Flute Airy - Outer Lift Bass

A **listening trial, awaiting user feedback**, saved on 2026-10-08 after the user requested trying Outer Lift with a bass boost. It duplicates **Middle Flute Airy - Outer Lift** and raises its **300 Hz low shelf from +1 dB to +3 dB**, retaining Q **0.71**. This is a 2 dB increase to that shelf; the other settings are unchanged.

The earlier Outer Lift version and all previous presets remain available. “Bass” in this variant name refers to the added bass boost; it does not establish the key or size of the flute in the comparison recording.

## Saved processing

| Order | Effect | State / settings |
| --- | --- | --- |
| 1 | Compressor | Bypassed |
| 2 | AUHipass | Bypassed |
| 3 | PlatinumVerb | On; predelay 28 ms; decay 2.30 s; high cut 6000 Hz; spread 100%; dry 100%; wet 25% |
| 4 | Single Band EQ — Parametric | On; 1700 Hz; +1.5 dB; Q 0.51 |
| 5 | Single Band EQ — High Shelf | On; 4450 Hz; +1.5 dB; Q 0.71 |
| 6 | Single Band EQ — Low Shelf | On; **300 Hz; +3.0 dB; Q 0.71** |
| 7 | Single Band EQ — High Shelf | On; 6000 Hz; +1.5 dB; Q 0.71 |

There is no 450 Hz or 900 Hz comparison boost. The original 4450 Hz high shelf remains active alongside the additional 6000 Hz high shelf.

Current session Ambience displayed **10%**. Native routing is `Ambience/0.2s Long Ambience`, with send scalar `0.08503936976194382`. The scalar is not a percent or dB value; native payload and observed UI display are recorded separately. Additional reverb send and master echo/reverb sends remain zero. Noise gate is off; no compression or limiting is added. PlatinumVerb's dry/wet controls are independent.

## Recall and compare

1. In the local Kudmayi project, **Airy - Outer Lift Bass** uses the same flute regions and timing as the comparison versions. Keep the accompaniment unchanged and **unmute only one flute version at a time**.
2. This version and Outer Lift are centered at **−2.8 dB**, with monitoring off for recorded playback. Compare the same passage at the same listening level.
3. For an isolated bass A/B test, switch the 300 Hz low-shelf gain between **+1 dB** and **+3 dB**; restore +3 dB for this version. Bypassing the shelf would compare against zero boost instead of the previous +1 dB.
4. For recall, choose **Library → User Patches → Middle Flute Airy - Outer Lift Bass**. The native patch was saved with **mute on**; unmute the desired track after recall.
5. On another Mac, copy the entire `.patch` folder to `~/Music/Audio Music Apps/Patches/Audio/`, then reopen GarageBand if needed.

The preset uses mono Scarlett input 1 and the M160 capture setup. Hardware gain, routing and placement were not freshly checked. The new bass version has not yet received listening approval; neither did the request for it imply approval of Outer Lift.

## Preservation

The source session is **Kudmayi - Original Pitch - Middle Flute Airy.band**, stored locally. Recordings, backing and projects stay out of Git. The inherited artistic reference is the [Ranjha flute cover](https://www.youtube.com/watch?v=N9OOJjfTjM8), especially 0:05–0:15; its production chain is unknown, and the assistant has not directly auditioned its audio.

`Middle Flute Airy - Outer Lift Bass.patch` is a byte-for-byte copy of the native saved User Patch. `settings.json` records verified controls; `manifest.sha256` verifies the three small native files. The native channel name is **Airy - Outer Lift Bass**.
