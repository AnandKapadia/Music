# Music settings repository

The user requested a private personal GitHub repository for the EQ, reverb, ambience, and sound settings developed together. Save accepted new sounds and commit/push their settings when this repository is available.

- GitHub repository: `AnandKapadia/Music`, renamed from `flute` on 2026-10-09 at the user's request. Keep it private. Local checkout remains `/Users/anand/Documents/flute`.
- `Sentral Music/` holds the separate vocal/guitar production notes. Ian is the vocalist on its Layla recording. Do not conflate these settings with flute presets. Offline production entries may contain notes and settings without a native `.patch`; clearly identify what is and is not saved in GarageBand.

- Never stage or upload recordings, tracks, accompaniment, reference audio, exports, `.band` projects, processing caches, models, `.audio-work`, or `.audio-tools`.
- Keep `.gitignore` as a default-deny allowlist. Use explicit staged paths; never force-add an ignored file.
- Store each sound in `Sound Library/<name>/` with `README.md`, `settings.json`, the native `.patch` directory, and `manifest.sha256`.
- A GarageBand patch contains settings only. Inspect any new native preset before staging it: only the expected small preset files belong in the repository.
- Before every push, inspect `git diff --cached --stat`, `git diff --cached --name-only`, and `git ls-files`; verify that only intended settings/documentation/preset files are included. Never push a public fallback or change repository visibility.
- Preserve the user's original takes and older accepted presets locally. Do not infer approval for a new tone from file validation alone.
- The full studio history is in untracked `Studio Guide (local).md`; broader shared project context is in `/Users/anand/Documents/ChatGPT/Music/AGENTS.md`.
- This repository is a sound library, not an automatic background upload process. No recurring task is required or configured.
