# Layla — Ian on vocals

Sentral Music · acoustic reference mix · 2026-10-09

The user accepted this mix with “Great!” and confirmed **Ian is the vocalist**. Guitar performer has not been identified. The production uses Ian's new vocal on GarageBand track 7 and the existing rhythm guitar on track 5. The older track 6 vocal is excluded.

Reference: [Eric Clapton — Layla (Acoustic Live), Unplugged](https://www.youtube.com/watch?v=EOs0qeiJyIg). The direction was fuller vocal body, a stronger guitar balance, subtle tuning, and restrained room reverb. The reference was analyzed using estimated vocal/band stems; no reference audio appears in the finished mix. This is a production reference, not an exact recreation of Clapton's voice or full band.

## Accepted production settings

| Stage | Settings |
| --- | --- |
| Vocal EQ | 75 Hz high-pass, 12 dB/octave; 185 Hz +1.5 dB/Q 0.70; 430 Hz −3 dB/Q 0.85; 1.8 kHz −2 dB/Q 0.75; 4.2 kHz high shelf +1 dB |
| Vocal dynamics | Slow phrase rides up to ±2.5 dB; compressor threshold −17 dB, ratio 2:1, attack 22 ms, release 140 ms |
| Guitar source EQ | Already present in the native stem: 75 Hz high-pass, 12 dB/octave/Q 0.71; 250 Hz −2.5 dB/Q 0.71 |
| Additional guitar EQ | 240 Hz +1 dB/Q 0.70; 2.3 kHz −1 dB/Q 0.90; 4.5 kHz high shelf −1.5 dB |
| Guitar dynamics | Compressor threshold −30 dB, ratio 1.5:1, attack 28 ms, release 150 ms |
| Balance | Median vocal approximately 4.5 dB above guitar during active singing, versus approximately 7.37 dB in the earlier mix |
| Room | Freeverb room size 0.32, damping 0.65, width 0.90; wet return filtered to 180–5800 Hz |
| Reverb levels | Wet RMS 19 dB below direct vocal and 23 dB below direct guitar; predelay 18 ms vocal / 10 ms guitar |

The room levels are measured return levels, not GarageBand wet-knob percentages. Full machine-readable settings are in [settings.json](settings.json).

## Tuning and timing

The guitar's estimated tuning was about +8 cents relative to A440. Selective PSOLA corrected 20 confident, sustained vocal note interiors, totaling 6.84 seconds including blends. Corrections moved 60% toward the nearest note relative to the accompaniment, capped at 18 cents, with 50 ms blends. Bends and unselected audio remain intact. Verification found a median correction error of 0.49 cents and maximum 1.35 cents.

No blanket pitch shift or performance nudge was applied. The raw vocal's existing GarageBand source offset is 111,412 samples (2.526349 seconds); this is a recording/source offset, not latency correction. Its native region ends at 239.369737 seconds. The guitar uses the native GarageBand render to preserve its follow-tempo behavior; its raw source must not be substituted at unchanged playback speed.

## Finished files and recall

The local output folder is `Documents/ChatGPT/Music/Exports/Layla - Acoustic Reference Mix/`:

- `Layla - Acoustic Reference Mix.wav` — full mix, 24-bit stereo WAV.
- `Layla - Acoustic Reference Mix.mp3` — full mix, 320 kbps MP3.
- `Layla - Acoustic Reference Mix - 45 second preview.mp3` — mix time 1:00–1:45.
- `Layla - Vocal - Aligned Stem.wav` — Ian's processed vocal.
- `Layla - Guitar - Aligned Stem.wav` — processed guitar.

Both full mixes run 4:05 at 44.1 kHz and measure −18.0 LUFS. True peaks are −1.80 dBTP for WAV and −1.78 dBTP for MP3, with no added digital clipping. Mastering adds 0.81 dB and a 4× oversampled lookahead limiter at −1.8 dB, 5 ms attack / 100 ms release, with latency compensation. Fades: 40 ms in and 4:00–4:05 out.

To edit this revision, import both aligned stems at bar 1 with unity faders and additional effects off. They include production effects and the common mastering gain, but precede the final mix limiter. The existing `Documents/ChatGPT/Music/Layla - Vocal and Guitar - Production.band` retains the earlier mix; these newer changes are offline renders, not a saved native GarageBand patch.

The raw microphone copy remains at `Documents/ChatGPT/Music/Recordings/Layla - Raw Vocal.wav`. Earlier mixes and original takes are preserved. The raw vocal contains some captured clipped peaks; the mix does not reconstruct missing waveform data. Focusrite settings and flute presets were not changed.

Reproduction scripts and detailed analysis remain local under `Documents/ChatGPT/Music/.audio-work/layla-reference/`: `tune_vocal.py`, `render_reference_mix.py`, `master_reference_mix.py`, and their JSON reports. Numerical checks passed; the assistant did not directly audition the audio. User acceptance is recorded above.
