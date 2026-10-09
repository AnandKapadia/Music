# Music

Music settings and production notes at [AnandKapadia/Music](https://github.com/AnandKapadia/Music).

For vocal and guitar productions, see [Sentral Music](<Sentral Music/README.md>), starting with **Layla — Ian on vocals**. The flute sound library below retains the two bansuri sounds for the beyerdynamic M160 and Scarlett setup.

The local checkout remains in `Documents/flute`; the GitHub repository was renamed from `flute` to `Music` on 2026-10-09.

## Flute sound library

| Sound | Use | Status |
| --- | --- | --- |
| [Middle Flute Airy](<Sound Library/Middle Flute Airy/README.md>) | Original middle-flute sound, developed with C# middle bansuri | Approved from take #03 on 2026-10-07; unchanged |
| [Bass Flute](<Sound Library/Bass Flute/README.md>) | Approved Kesariya tone with gentle compression, warm EQ and reverb | Version 1.2.1: requested less air and slightly more reverb; listening confirmation pending |

Recall either sound in GarageBand through **Library → User Patches**. Each entry includes the native patch, readable instructions, verified settings and checksums. Hardware gain, mic placement, monitoring and accompaniment balance need separate checks.

## Bass Flute recall and recreation

The Bass Flute patch now includes the approved gentle compressor: **-18 dB threshold, 1.8:1 ratio, 26 ms attack, +1 dB makeup**. The latest requested adjustment reduces the final 6 kHz shelf from +1.5 to 0 dB and raises PlatinumVerb wet from 25% to 28%. All other processing is retained. The [Bass Flute guide](<Sound Library/Bass Flute/README.md>) also records the Kesariya backing balance, pitch adjustment, fades and mastering recipe needed to recreate the finished mix. These song-specific settings remain separate from the reusable flute patch.

## Bass Flute volume and Focusrite setup

The preferred **Bass Flute track fader** is **-10 dB for playback** and **-4.0 dB while recording**. The updated native patch saves the -10 dB playback level. Switch manually to -4.0 dB for recording and back to -10 dB afterward; no automatic switching is configured. These listening levels do not change the raw recorded input.

The [Focusrite hardware settings](<Hardware/Focusrite Scarlett 4i4/README.md>) include a native **Bass Flute - GarageBand - 68 dB** preset, its readable gain/routing settings and a checksum. Input 1 gain is **68 dB**, with 48V, Inst, Air and Clip Safe off. Headphones use Mix A, with direct flute muted and GarageBand Playback 1/2 at -12 dB. Hardware gain and the two GarageBand volume profiles are separate controls. This adds a hardware snapshot while retaining exactly the two tonal sounds above.

At the user's request, intermediate experiments were removed from the active sound library and GarageBand User Patches. Hash-verified copies remain locally under `.audio-work/retired-presets/`; older tracked settings remain in Git history. Only the two choices above remain active. The original Middle Flute Airy patch is unchanged.

Recordings, tracks, GarageBand projects, accompaniment, exports, reference audio, retired local archives and audio-processing work files stay on this Mac and are excluded by the default-deny `.gitignore`. No audio is part of this library.

The complete studio guide remains locally in [Studio Guide (local).md](<Studio Guide (local).md>). It is intentionally untracked and available only in the local folder.

When the user accepts another change, update the appropriate named sound or add a distinct option only as requested. Verify the saved preset, audit the staged settings-only paths, then commit and push. Preserve replaced presets locally or in Git history.
