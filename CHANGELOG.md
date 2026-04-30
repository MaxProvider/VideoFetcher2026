# Changelog

All notable changes to Video Fetcher 2026.

## [1.0.0] — 2026-04-30

### Added
- Initial public release
- 1-5 parallel download slots with live VU speed meters
- Channel/profile scraper with quick range buttons (1-500, 501-1000, etc.)
- Already-owned detection — Layer 1 (filename ID match) and Layer 2 (yt-dlp output)
- Queue persistence between sessions with automatic restore on startup
- Pre-scan queue against local folders before downloading
- Failed URL logging with retry support
- Speed limiter dropdown in status bar (Unlimited to 100 KB/s, colour-coded)
- Right-click activity log — Copy Line, Copy Selection, Select All, Open File, Delete File
- Automatic .info.json metadata saving (optional)
- System tray integration with right-click controls
- Configurable close behaviour (ask, minimise to tray, exit)
- Cross-platform support — Linux x86_64 and Windows x64 from single source
- Windows: yt-dlp and ffmpeg bundled inside executable
- Ed25519 public-key licence system with machine-tied keys
- Shareware model — free version with limits, lifetime licence to unlock all
- Nuitka-compiled native executables for both platforms
- Comprehensive in-app help system (F1)
- Keyboard shortcuts throughout

### Companion Apps
- MetaFetch — free metadata fetcher for existing video libraries
- Stash Info JSON Importer — free Stash plugin for metadata import
