# AI DJ Segment Player

One build, two ways to run it — the same single file (`index.html`) is the whole product:

- **In any browser (this site):** open the GitHub Pages URL and play from YouTube — search and playlists included. Best where you have internet.
- **On a TV-connected device (downloaded):** save `index.html` to the device and open it directly — no login, no internet needed. Your local audio/video files play fully offline.

## What it does

- Mark a start/end **segment** per song, so the set plays only the good parts — jump in mid-song or cut early to control the pace of the dance floor.
- **Dual-deck crossfade** (0s hard cut up to ~12s) with a cue queue, fullscreen show mode, and keyboard shortcuts (Space, arrow keys, R).
- **Mixed queues:** YouTube and local-file cues in one playlist, played straight through.
- **Named playlists** saved on the device (browser storage), with JSON export/import.

## YouTube setup (optional)

YouTube works from pasted links with no setup. For in-app search, add your own YouTube Data API v3 key under **Settings** — it is stored only in your browser on that device and never sent anywhere else.

## Notes

- Local files can't be stored in the page between sessions (browser security), so after a reload a local cue may ask you to re-link its file — one click.
- Current version: **v1.1.0**
