<div align="center">
  <img src="https://www.pulsemusicbot.org/logo.png" alt="Pulse" width="80" />

  # Pulse — Free Discord Music Bot with an AI DJ
</div>

> **Play music in Discord from Spotify, YouTube and SoundCloud — with a live AI radio host, real-time audio effects, a synced Discord Activity, a phone-friendly Remote, and a full web dashboard.**

[![Invite Pulse](https://img.shields.io/badge/Invite%20Pulse-Add%20to%20Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://www.pulsemusicbot.org/invite)
[![Website](https://img.shields.io/badge/Website-pulsemusicbot.org-fc00ff?style=for-the-badge)](https://www.pulsemusicbot.org)
[![Support Server](https://img.shields.io/badge/Support-Discord%20Server-00dbde?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/pulsemusicbot)
[![Commands](https://img.shields.io/badge/Commands-50%2B-8b5cf6?style=for-the-badge)](./COMMANDS.md)

---

## What is Pulse?

Pulse is a **feature-rich Discord music bot** designed for servers that actually care about sound quality. It supports playback from the biggest music platforms, a suite of real-time audio effects, persistent custom playlists, and a live AI radio host — DJ Kara — who plans themed sets and talks between tracks like a real station.

You're not stuck controlling it from Discord's chat box either: launch a fully synced player from any voice channel's **Activities** picker, or drive the whole thing from your phone with the **Pulse Remote** — install it as an app, and never even open Discord.

No bloat. No fake uptime. Just great music.

---

## ✨ Features

### 🎤 DJ Kara — AI Voice DJ *(Pro & Premium)*
The standout feature. Pulse keeps the music going forever — no empty queues, no awkward silences. And DJ Kara never shuts up.

- **Smart track selection** — finds music related to what's currently playing, matching genre and mood automatically
- **AI voice announcements** — DJ Kara announces every track with chaotic British energy and zero filter
- **Vibe mode** — `/autodj vibe:lofi` locks the session into a genre or mood
- **DJ Builder** — write Kara a custom voice and personality for your server; she stays in character across every chapter, intro, and dedication
- **On-air dedications** — `/request` queues a song with a message and Kara reads it out live before the track plays, proper call-in radio style
- **Scheduled shows** — `/show add` books Kara to host a recurring themed set at a set time, day, and timezone
- **More Like This** — `/morelikethis` anchors DJ Kara to the exact track playing
- **Per-server learning** — remembers what your server enjoys and weights future picks accordingly
- Works across queued playlists too — not just when the queue runs out
- `/autodj action:off` or `/autodj voice:off` to silence Kara (coward)

### 🎮 Discord Activity *(Basic and above)*
Launch a fully synced player from any voice channel's **Activities** picker — no separate app, no tab-switching. Everyone in the channel sees the same queue, live emoji reactions, and milestone celebrations together.

### 📱 Companion Remote
Control Pulse from your phone without ever opening Discord. Install it as a PWA, pick a server, and get full playback controls, queue reordering, the soundboard, and audio filters — all from your pocket.

### 🎧 Multi-Platform Playback
- **YouTube** — search or paste a link
- **Spotify** — tracks, albums, and playlists
- **SoundCloud** — search and direct links
- **Direct URLs** — MP3, FLAC, streams

### 🎛️ Audio Effects (Real-Time)
Stack effects, go wild, reset with `/clearfilters`.

| Effect | Command | Description |
|---|---|---|
| Bass Boost | `/bass` | 0–200% — from subtle warmth to earth-shaking |
| 8D Audio | `/eightd` | Rotating spatial effect |
| Nightcore | `/nightcore` | Speed & pitch up |
| Slow Reverb | `/slowreverb` | Lofi / dreamy reverb tail |
| Vaporwave | `/vaporwave` | Slowed, pitched-down retro feel |
| Tremolo | `/tremolo` | Rhythmic volume oscillation |
| Distortion | `/distortion` | Saturation — subtle warmth to absolute destruction |
| Low-Pass | `/lowpass` | Muffle high frequencies — from underwater to barely-there |
| Pitch Shift | `/pitch` | -12 to +12 semitones |

### 🎼 Queue & Playback Control
- `/play`, `/playnext`, `/skip`, `/stop`, `/pause`
- `/queue` — paginated queue view
- `/shuffle` — shuffle your entries
- `/seek` — jump to any timestamp
- `/movetrack` — drag tracks to a new position
- `/repeat` — off / loop queue / loop track
- `/volume` — 0–150%
- `/lyrics` — show lyrics for the current or any song
- `/history` and `/replay` — recently played tracks, one tap to re-queue

### 📋 Custom Playlists (Pro & Premium)
- Create and name your own playlists
- Add tracks from any source
- Set a server default — auto-plays when Pulse joins
- Persistent across sessions

### 🔊 Soundboard
Upload short audio clips (up to 30 seconds) and fire them mid-playback — the track ducks out, the clip plays, and it ducks back in. Works from Discord *and* from the Remote. Manage clips at [pulsemusicbot.org/dashboard/soundboard](https://www.pulsemusicbot.org/dashboard/soundboard).

### 📊 Wrapped & Listening Stats
- `/wrapped me` — your personal 30-day recap: top tracks, top artists, when you listen most
- `/wrapped server` — the whole server's recap: top tracks, top requesters, most dedicated listener
- `/wrapped match` — a taste-compatibility score between you and another listener
- Milestone celebrations when your server hits a listening streak

### 👋 Welcome Messages
Greet new members automatically when they join — `/welcome channel`, `/welcome message` with `{user}`/`{server}`/`{count}` placeholders, and `/welcome test` to preview it.

### 🌐 Web Dashboard
A full admin panel at [pulsemusicbot.org/dashboard](https://www.pulsemusicbot.org/dashboard):
- Manage playlists
- Upload and trim soundboard clips
- View subscription and usage
- Redeem trial tokens

### 🛡️ Server Controls
- Lock commands to a specific text or voice channel
- Set a DJ role for queue management permissions
- Configure vote-skip thresholds
- Fair queue mode (round-robin per user)

---

## 🚀 Getting Started

1. **[Invite Pulse](https://www.pulsemusicbot.org/invite)** to your server
2. Make sure Pulse has permission to **view channels**, **send messages**, and **connect to voice**
3. Type `/play` followed by a song name or URL — that's it
4. Want to control it without opening Discord? Sign in at [pulsemusicbot.org/remote](https://www.pulsemusicbot.org/remote)

---

## 💳 Plans

| Plan | Price | Highlights |
|---|---|---|
| **Free** | £0 | 5 queued tracks, unlimited playback, vote skip |
| **Basic** | £2.99/mo | 25 tracks, all effects, radio, Spotify import, 10 soundboard clips |
| **Pro** | £5.99/mo | 75 tracks, custom playlists, DJ Kara AI voice DJ, 20 soundboard clips |
| **Premium** | £9.99/mo | 150 tracks, 2 servers, DJ Kara AI voice DJ, 40 clips, custom Discord role |

**30-day free Premium trial — no card required.** Start at [pulsemusicbot.org](https://www.pulsemusicbot.org).

---

## 📖 Command Reference

Full slash command documentation: **[pulsemusicbot.org/commands](https://www.pulsemusicbot.org/commands)**

Or see [`COMMANDS.md`](./COMMANDS.md) in this repo — 50+ commands across music, effects, DJ Kara, playlists, soundboard, scheduled shows, and server admin.

---

## 🆘 Support

- **Discord:** [discord.gg/pulsemusicbot](https://discord.gg/pulsemusicbot)
- **Help Centre:** [pulsemusicbot.org/support](https://www.pulsemusicbot.org/support)
- **Email:** support@pulsemusicbot.org

---

## 🔗 Links

| | |
|---|---|
| 🌐 Website | [pulsemusicbot.org](https://www.pulsemusicbot.org) |
| ➕ Invite Bot | [pulsemusicbot.org/invite](https://www.pulsemusicbot.org/invite) |
| 💬 Discord | [discord.gg/pulsemusicbot](https://discord.gg/pulsemusicbot) |
| 📋 Commands | [pulsemusicbot.org/commands](https://www.pulsemusicbot.org/commands) |
| 📱 Remote | [pulsemusicbot.org/remote](https://www.pulsemusicbot.org/remote) |
| 📊 Dashboard | [pulsemusicbot.org/dashboard](https://www.pulsemusicbot.org/dashboard) |

---

*Keywords: discord music bot, free discord music bot, discord bot spotify, discord bot youtube, discord audio effects, discord bass boost bot, discord nightcore bot, discord 8d audio, discord distortion filter, discord low pass filter, discord soundboard bot, discord playlist bot, discord music bot 2025, discord music bot 2026, discord music bot commands, discord bot free, discord ai dj bot, discord voice dj bot, ai dj discord, discord auto dj bot, discord activity music bot, discord activities bot, discord remote control bot, discord bot pwa, control discord bot from phone, discord scheduled radio show bot, discord dj scheduler, discord welcome bot, discord wrapped bot, discord listening stats bot*
