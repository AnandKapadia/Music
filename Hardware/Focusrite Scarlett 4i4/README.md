# Bass Flute — Focusrite settings

Saved in Focusrite Control 2 on **2026-10-08** as **Bass Flute - GarageBand - 68 dB**. This is the interface setup for the existing Bass Flute sound; it does not add another tonal preset.

## Input gain

| Input | Gain | 48V | Inst | Air | Clip Safe |
| --- | --- | --- | --- | --- | --- |
| Analogue 1 — flute / M160 | **68 dB** | Off | Off | Off | Off |
| Analogue 2 — unused | 12 dB | Off | Off | Off | Off |

Inputs 1 and 2 are unlinked. Rear inputs 3 and 4 remain line inputs. The live input 1 gain was saved as found; no gain adjustment was made for this snapshot.

## Monitoring and outputs

| Mix A source | Level | State |
| --- | --- | --- |
| Analogue 1 — direct flute | -12 dB | **Muted** |
| Analogue 2 | -128 dB | Down; unmuted |
| Analogue 3/4 — piano | 0 dB | Stereo linked; unmuted |
| Playback 1/2 — GarageBand | -12 dB | Stereo linked; unmuted |
| Playback 3/4 and 5/6 | -128 dB | Down; stereo linked; unmuted |

All pans are centered and no channels are soloed. **Headphones and outputs 1/2 receive Mix A**. Outputs 3/4 receive Mix B, with Playback 3/4 at 0 dB and its other channels down at -128 dB. Loopback receives Mix C, with Playback 1/2 at 0 dB and its other channels down at -128 dB.

Keep direct Analogue 1 muted while monitoring the processed flute through GarageBand. Enable input monitoring on only one mono input 1 flute track.

## Playback and recording volume

In GarageBand, manually set the **Bass Flute track fader to -10 dB for playback or -4.0 dB while recording**. These are the user's preferred listening levels. The fader affects playback and software monitoring; it does not change the raw input recording level. The **68 dB Focusrite preamp gain** controls the captured signal separately. No automatic switching has been configured.

## Recall and backup

The named preset is saved in Focusrite Control 2 on this Mac and can be recalled from its saved presets. `Bass Flute - GarageBand - 68 dB.xml` is a byte-for-byte backup of that native preset. `settings.json` describes its values and records the native local filename and preset directory; `manifest.sha256` verifies the XML.

The live UI displayed **44.1 kHz**, but the native XML contains no sample-rate field. The XML also does not store GarageBand track levels/effects or physical headphone/output knob positions. Confirm those separately when restoring the setup. A restore from the repository backup has not been performed as part of this save.

Only the native preset XML and readable settings are included. The global Focusrite application settings file, unrelated connections, recordings and audio projects are excluded.
