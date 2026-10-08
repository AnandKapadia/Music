# Flute sound library

Two retained bansuri sounds for the beyerdynamic M160 and Scarlett setup. This settings repository stays private in the personal GitHub account.

| Sound | Use | Status |
| --- | --- | --- |
| [Middle Flute Airy](<Sound Library/Middle Flute Airy/README.md>) | Original middle-flute sound, developed with C# middle bansuri | Approved from take #03 on 2026-10-07; unchanged |
| [Bass Flute](<Sound Library/Bass Flute/README.md>) | Accepted bass-flute sound with 300 Hz low shelf +3 dB and additional 6000 Hz high shelf +1.5 dB | Approved on 2026-10-08 |

Recall either sound in GarageBand through **Library → User Patches**. Each entry includes the native patch, readable instructions, verified settings and checksums. Hardware gain, mic placement, monitoring and accompaniment balance need separate checks.

At the user's request, intermediate experiments were removed from the active sound library and GarageBand User Patches. Hash-verified copies remain locally under `.audio-work/retired-presets/`; older tracked settings remain in Git history. Only the two choices above remain active. The original Middle Flute Airy patch is unchanged.

Recordings, tracks, GarageBand projects, accompaniment, exports, reference audio, retired local archives and audio-processing work files stay on this Mac and are excluded by the default-deny `.gitignore`. No audio is part of this library.

The complete studio guide remains locally in [Studio Guide (local).md](<Studio Guide (local).md>). It is intentionally untracked and available only in the local folder.

When the user accepts another change, update the appropriate named sound or add a distinct option only as requested. Verify the saved preset, audit the staged settings-only paths, then commit and push. Preserve replaced presets locally or in Git history.
