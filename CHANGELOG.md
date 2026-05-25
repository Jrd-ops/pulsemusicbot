# Changelog

All notable updates to Pulse are documented here.

---

## [2.4] — 2025-05

### Added
- **Discord invite card** on support page — shows live member count and server banner
- **Admin panel** — staff can view, reply to, and close support tickets from the web dashboard
- **Ticket message live view** — real-time message feed inside each ticket panel

### Fixed
- Mobile ticket table overflow on narrow screens
- Ticket rows now fully clickable on touch devices

---

## [2.3] — 2025-04

### Added
- **Soundboard** — upload and fire custom audio clips mid-playback with auto-ducking
- Soundboard management UI at `/dashboard/soundboard`
- Waveform trimmer for clip editing

### Changed
- Playback limits now enforced with a clear in-channel notification on expiry

---

## [2.2] — 2025-03

### Added
- **Pitch shift** (`/pitch`) — shift by semitones in real time
- **Tremolo effect** (`/tremolo`) — configurable frequency and depth
- **Fair queue mode** — round-robin per user instead of pure FIFO

### Fixed
- Seek command now handles `+/-` relative offsets correctly

---

## [2.1] — 2025-02

### Added
- **Web dashboard** — manage playlists, soundboard, and subscription from the browser
- **Trial token redemption** — redeem `XXXX-XXXX-XXXX` tokens via dashboard

### Changed
- Dashboard built with Next.js App Router and Discord OAuth login

---

## [2.0] — 2025-01

### Added
- **Lavalink audio backend** — significantly improved audio quality and stability
- **Spotify support** — tracks, albums, and playlists via LavaSrc plugin
- **Persistent queues** (Basic+) — queue saved across bot restarts
- **Custom playlists** (Pro+) — create, manage, and auto-play server playlists
- **8D audio** (`/eightd`) — rotating spatial effect
- **Slow reverb** (`/slowreverb`) — lofi mode
- **Vaporwave** (`/vaporwave`) — slowed + pitched-down

### Changed
- All commands migrated to Discord slash command format
- Plan system introduced: Free, Basic, Pro, Premium

---

## [1.x] — Legacy

Original release with YouTube and SoundCloud playback, basic queue control, and audio effects.
