# Flute sound library

Two retained bansuri sounds for the beyerdynamic M160 and Scarlett setup. This settings repository stays private in the personal GitHub account.

| Sound | Use | Status |
| --- | --- | --- |
| [Middle Flute Airy](<Sound Library/Middle Flute Airy/README.md>) | Original middle-flute sound, developed with C# middle bansuri | Approved from take #03 on 2026-10-07; unchanged |
| [Bass Flute](<Sound Library/Bass Flute/README.md>) | Accepted bass-flute sound with 300 Hz low shelf +3 dB and additional 6000 Hz high shelf +1.5 dB | Approved on 2026-10-08 |

Recall either sound in GarageBand through **Library → User Patches**. Each entry includes the native patch, readable instructions, verified settings and checksums. Hardware gain, mic placement, monitoring and accompaniment balance need separate checks.

## Bass Flute volume and Focusrite setup

The preferred **Bass Flute track fader** is **-10 dB for playback** and **-4.0 dB while recording**. Change it manually after recalling the sound; no automatic switching is configured. The native tonal patch remains unchanged and retains its historical 0 dB fader. These listening levels do not change the raw recorded input.

The [Focusrite hardware settings](<Hardware/Focusrite Scarlett 4i4/README.md>) include a native **Bass Flute - GarageBand - 68 dB** preset, its readable gain/routing settings and a checksum. Input 1 gain is **68 dB**, with 48V, Inst, Air and Clip Safe off. Headphones use Mix A, with direct flute muted and GarageBand Playback 1/2 at -12 dB. Hardware gain and the two GarageBand volume profiles are separate controls. This adds a hardware snapshot while retaining exactly the two tonal sounds above.

At the user's request, intermediate experiments were removed from the active sound library and GarageBand User Patches. Hash-verified copies remain locally under `.audio-work/retired-presets/`; older tracked settings remain in Git history. Only the two choices above remain active. The original Middle Flute Airy patch is unchanged.

Recordings, tracks, GarageBand projects, accompaniment, exports, reference audio, retired local archives and audio-processing work files stay on this Mac and are excluded by the default-deny `.gitignore`. No audio is part of this library.

The complete studio guide remains locally in [Studio Guide (local).md](<Studio Guide (local).md>). It is intentionally untracked and available only in the local folder.

When the user accepts another change, update the appropriate named sound or add a distinct option only as requested. Verify the saved preset, audit the staged settings-only paths, then commit and push. Preserve replaced presets locally or in Git history.
