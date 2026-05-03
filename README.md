# Video Fetcher 2026

**Batch video downloader for Linux & Windows — powered by yt-dlp**

[Download](https://videofetcher.co.uk/downloads.html) · [Purchase Licence](https://videofetcher.co.uk/purchase.html) · [How To](https://videofetcher.co.uk/howto.html) · [Website](https://videofetcher.co.uk)

---

## Features

- 1 to 5 parallel download slots with VU speed meters
- Pause and resume downloads
- Channel/profile scraper with quick range buttons (batches of 500)
- Already-owned detection — skip files you already have
- Queue persistence between sessions
- Speed limiter — status bar dropdown, colour coded
- Right-click activity log — copy, open file, delete file
- Automatic .info.json metadata saved alongside each video
- Windows: yt-dlp and ffmpeg bundled — zero dependencies
- Linux: uses system yt-dlp and ffmpeg

---

## Download

| Platform | Link | Notes |
|----------|------|-------|
| Linux x86_64 | [Download](https://videofetcher.co.uk/files/VideoFetcher2026) | Requires yt-dlp and ffmpeg |
| Windows x64 | [Download](https://videofetcher.co.uk/files/VideoFetcher2026.exe) | Everything bundled, just double-click |

---

## Free vs Licensed

| Feature | Free | Licensed |
|---------|:----:|:--------:|
| Download videos | ✓ | ✓ |
| Queue persistence | ✓ | ✓ |
| Activity log | ✓ | ✓ |
| Download slots | 1 | Up to 5 |
| Download speed | 2 MB/s | Unlimited |
| Scraper | 10 URLs | Unlimited |
| Queue size | 10 URLs | Unlimited |
| Quick range buttons | ✗ | ✓ |
| Price | Free | £12.99 one-time |

[Purchase a lifetime licence](https://videofetcher.co.uk/purchase.html) — one payment, no subscription, no expiry.

---

## Installation

### Linux
```bash
wget https://videofetcher.co.uk/files/VideoFetcher2026
chmod +x VideoFetcher2026
./VideoFetcher2026
```

### Windows
Download VideoFetcher2026.exe and double-click. No installation needed.

---

## Companion Apps

**MetaFetch** (free) — fetches missing .info.json metadata for existing video libraries.
https://videofetcher.co.uk/metafetch.html

**Stash Info JSON Importer** (free) — imports .info.json metadata into Stash media manager.
https://videofetcher.co.uk/plugins.html

---

## Tech Stack

- Python 3 / PyQt6
- yt-dlp + ffmpeg
- Nuitka (compiled to native C)
- Ed25519 public-key licensing
- Linux x86_64 + Windows x64

---

## Links

- Website: https://videofetcher.co.uk
- Downloads: https://videofetcher.co.uk/downloads.html
- Purchase: https://videofetcher.co.uk/purchase.html
- Contact: david@videofetcher.co.uk

---

Copyright 2026 David Smith - videofetcher.co.uk
