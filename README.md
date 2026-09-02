# Interview prep

Personal question bank with follow-along audio. Single-page app, no build step.

- `index.html` — the app (questions are embedded in the page)
- `audio/` — one MP3 per answer plus `timings.json` (sentence start times in ms)

Audio was generated with `edge-tts` using the `en-GB-SoniaNeural` voice.
If `audio/timings.json` is absent the page falls back to browser speech synthesis.

Marked `noindex` so it stays out of search results.