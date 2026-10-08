# Bass Flute

**Version 1.2.1 — requested adjustment, 2026-10-08.** The user requested a tad less airiness and a little more reverb. The final 6000 Hz shelf is now **0 dB** (previously +1.5 dB), and PlatinumVerb wet is **28%** (previously 25%). Listening approval of this revision is pending.

The updated **Bass Flute** patch retains the gentle production compressor and **−10 dB playback fader**. All processing except those two values remains unchanged. **Middle Flute Airy** remains unchanged; these are the two active sounds.

## Saved processing

| Order | Effect | State / settings |
| --- | --- | --- |
| 1 | Compressor | On; threshold **−18 dB**, ratio **1.8:1**, attack **26 ms**, makeup **+1 dB** |
| 2 | AUHipass | Bypassed |
| 3 | PlatinumVerb | On; predelay 28 ms; decay 2.30 s; high cut 6000 Hz; spread 100%; dry 100%; wet 28% |
| 4 | Single Band EQ — Parametric | On; 1700 Hz; +1.5 dB; Q 0.51 |
| 5 | Single Band EQ — High Shelf | On; 4450 Hz; +1.5 dB; Q 0.71 |
| 6 | Single Band EQ — Low Shelf | On; 300 Hz; +3.0 dB; Q 0.71 |
| 7 | Single Band EQ — High Shelf | On; 6000 Hz; 0 dB; Q 0.71 |

PlatinumVerb's dry and wet controls are independent. The noise gate is off; no limiter is used. Native payload comparison confirms only the final shelf gain and reverb wet level changed; reverb decay remains 2.30 seconds.

The project UI displays **Ambience 10%, Reverb 20%, master Echo/Reverb 0**. Reverb refreshed from 0% to 20% after the direct PlatinumVerb Wet edit; no macro or send was adjusted. The saved native patch separately contains `Ambience/0.2s Long Ambience` send scalar `0.07086613029241562` and `Small Hall/1.6s Short Vocal Hall` send scalar `0.1445668488740921`. These native scalars are not percentages or dB values. Preserve the native patch to retain its routing; do not replace its nonzero saved Small Hall send with a claimed zero. Both native sends are unchanged from version 1.2.0.

## Recall and record

1. Select a mono audio track and choose **Library → User Patches → Bass Flute**. The patch is installed on this Mac and saves center pan, Scarlett input 1 and the **−10 dB playback level**.
2. For recording/live playing, manually change the fader to **−4.0 dB** and enable monitoring on only the desired mic track. Return to **−10 dB** for playback. Switching is manual; the patch is saved with monitoring off, unmuted and not soloed.
3. Use the saved **Focusrite “Bass Flute - GarageBand - 68 dB”** preset. Its input 1 gain is 68 dB; 48V, Inst, Air and Clip Safe are off. Mix A feeds headphones, direct Analogue 1 is muted, and Playback 1/2 is at −12 dB. Hardware settings remain separate and unchanged; see [hardware settings](<../../Hardware/Focusrite Scarlett 4i4/README.md>).
4. On another Mac, copy the entire `Bass Flute.patch` folder to `~/Music/Audio Music Apps/Patches/Audio/`, then reopen GarageBand if necessary.

The track fader affects playback and software monitoring, not dry recording gain. The saved sound uses the **beyerdynamic M160**, kept outside the direct breath stream. Keep flute, playing level, mic distance and room consistent when recreating the result.

## Historical recipe: approved Kesariya export (1.2.0)

The earlier approved export used **Bass Flute 1.2.0**, before this air/reverb adjustment. To recreate that exact sound, restore `Sound Library/Bass Flute/Bass Flute.patch` from Git commit `d1e3d40ba415940f17e3b66cb308e372098a9439` or the local pre-adjustment backup. Use the local **Kesariya - Bass Flute - Production Mix.band** project and Bass Flute take #12. Its flute fader is **−10 dB**, accompaniment **−13 dB**, and project master **0 dB**. The backing uses **AUPitch +20 cents**, Effect Blend 100%, Smoothness 50%, Tightness 50%, quality Maximum; the flute has no pitch correction. That pitch offset fits this performance and must be checked separately for future takes.

Disable GarageBand **Auto Normalize / Export projects at full volume** for the native export, then restore the prior preference afterward. The finished export uses **0–77 seconds**, raised-cosine fades of **0.04 seconds in** and **73–77 seconds out**, and **+6.16 dB gain after the native export**, yielding **−16 LUFS**. Do not add this gain to an already auto-normalized file. Final WAV is stereo 24-bit/44.1 kHz; MP3 is 320 kbps. Measured WAV true peak is about **−4.69 dBFS**, with no clipping and no limiter. These fades and master gain are an export recipe, not part of the track patch. Measure new performances before reusing that gain.

## Preservation and verification

The previous patch is backed up locally before replacement and remains available in Git history. Audio, recordings and GarageBand projects stay local and are excluded from Git. `settings.json` records the controls and the Kesariya recipe; `manifest.sha256` verifies the three small native patch files.

The current native patch is verified to differ from 1.2.0 in exactly the two requested settings. Compressor, other EQ/reverb parameters, bypass states, fader and native sends are unchanged.

Version **1.2.0** passed a fresh recall and solo-render match to the approved native flute export (77 seconds; RMS difference −161.95 dBFS). That historical result does not claim that the current, intentionally changed 1.2.1 patch matches the older export. Listening feedback on 1.2.1 has not yet been received. No assistant direct audio audition is claimed.
