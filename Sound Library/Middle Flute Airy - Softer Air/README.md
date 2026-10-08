# Middle Flute Airy - Softer Air

Saved on 2026-10-08 for the request “a little less breathy.” The user subsequently said **“I like this, I think it needs more body on the deep side.”** This confirms the softer-air direction while requesting a separate refinement for low-register body. The original approved **Middle Flute Airy** preset remains unchanged.

The saved Softer Air native patch and effect values are preserved. The next refinement is saved separately as **Bass Flute - Warm Body**; the user clarified that the instrument is a bass bansuri, with its key unconfirmed in this session.

## What changed

The high shelf at **4450 Hz** was reduced from **+1.5 dB to −1.0 dB**, a 2.5 dB reduction, with Q **0.71** unchanged. This is intended to soften upper-frequency breath detail while retaining the current fullness, presence and reverb. It was the only processing control changed for this version. The user liked this direction; no exact reference match is claimed.

## Saved processing

| Order | Effect | State / settings |
| --- | --- | --- |
| 1 | Compressor | Bypassed |
| 2 | AUHipass | Bypassed |
| 3 | PlatinumVerb | On; predelay 28 ms; decay 2.30 s; high cut 6000 Hz; spread 100%; dry 100%; wet 25% |
| 4 | Single Band EQ — Parametric | On; 1700 Hz; +1.5 dB; Q 0.51 |
| 5 | Single Band EQ — High Shelf | On; 4450 Hz; **−1.0 dB**; Q 0.71 |
| 6 | Channel EQ | On; Factory Default display; visually flat 0 dB response; low/high cuts off; master gain 0 dB |

The extra Channel EQ was already present in the Kudmayi session and was preserved. Its full state is stored in the native patch; individual band frequency/Q values were not transcribed.

Ambience displayed **5%** (Smart Control value 0.04800000521871779, about 4.8%) before this edit and remains there. Its native routing is `Ambience/0.2s Long Ambience`, with send scalar `0.07086615264415741`. The scalar is not a percentage or dB value. The approved original preset has 12% ambience, so switching between the original saved patch and this variant also changes that pre-existing session difference.

Additional reverb send and master echo/reverb sends are zero. Noise gate is off; no compression or limiting is applied. PlatinumVerb's dry and wet controls are independent.

## Recall and compare

1. Select the flute track and choose **Library → User Patches → Middle Flute Airy - Softer Air**. It is installed on this Mac.
2. To isolate the change in an A/B comparison, keep this patch loaded and alternate its high-shelf gain between −1.0 dB and +1.5 dB. Restore −1.0 dB for this saved trial. Avoid changing listening level between comparisons.
3. The original **Middle Flute Airy** remains available as a separate preset, including its original 12% ambience and earlier chain.
4. On another Mac, copy the entire `.patch` folder to `~/Music/Audio Music Apps/Patches/Audio/`. Reopen GarageBand if needed.

The current session uses mono Scarlett input 1, centered pan, monitoring on and feedback protection off for headphones. Flute fader −3.7 dB, backing −19.5 dB and master 0 dB were already set before this task; the accompaniment was left unchanged. Recheck recording headroom and listening balance separately. Hardware gain and routing are not part of the patch and were not freshly verified. Keep the M160 outside the direct breath stream.

## Provenance and preservation

The source is the local **Kudmayi - Original Pitch - Middle Flute Airy.band** session. Its project, backing and any recordings remain local and are excluded from Git. A full pre-change project backup is stored locally under `Documents/ChatGPT/Music/.audio-work/backups/`.

The artistic reference remains the [original Ranjha flute cover](https://www.youtube.com/watch?v=N9OOJjfTjM8), especially 0:05–0:15, but its production chain is unknown and the assistant has not directly auditioned the audio.

`Middle Flute Airy - Softer Air.patch` is a byte-for-byte copy of the native saved User Patch. `settings.json` records verified controls; `manifest.sha256` verifies the three small native preset files. The native channel name may still read “Bansuri Csharp M160 - Ranjha Smooth Presence.”
