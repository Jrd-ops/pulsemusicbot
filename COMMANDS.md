# Pulse Bot — Full Command Reference

> Full docs at [pulsemusicbot.org/commands](https://www.pulsemusicbot.org/commands)

All commands use Discord slash command syntax (`/command`).

---

## 🎵 Music

| Command | Arguments | Description |
|---|---|---|
| `/play` | `<title \| URL>` | Play a song from YouTube, Spotify, or SoundCloud. Adds to queue if music is already playing. |
| `/search` | `<query>` | Search YouTube and choose from top results. |
| `/queue` | `[page]` | View the current queue. Paginated for long queues. |
| `/nowplaying` | | Show the current song with progress bar, requester, and source. |
| `/skip` | | Vote to skip the current song. |
| `/remove` | `<position>` | Remove a song from the queue by position. |
| `/repeat` | `[off \| all \| single]` | Set repeat mode — off, loop queue, or loop current track. |
| `/history` | | Show the last 10 recently played tracks. Auto-DJ picks are tagged 🤖. |
| `/replay` | `[position]` | Re-queue a track from the history. Defaults to the most recent. |
| `/playlist` | `<create \| play \| add \| addsong \| view \| list \| remove \| delete>` | Manage custom playlists. Pro & above. |

---

## 🎛️ Audio Effects

| Command | Arguments | Description |
|---|---|---|
| `/bass` | `<0–200 \| off>` | Bass boost. 100 is default, 200 is maximum. `off` to reset. |
| `/nightcore` | | Toggle Nightcore mode — faster and higher pitched. |
| `/eightd` | | Toggle 8D audio — rotating spatial effect. |
| `/slowreverb` | | Toggle slow reverb (lofi mode). |
| `/vaporwave` | | Toggle vaporwave mode. |
| `/tremolo` | `[frequency] [depth]` | Apply tremolo effect — rhythmic volume oscillation. |
| `/pitch` | `<semitones \| off>` | Shift pitch -12 to +12 semitones. `off` to reset. |

---

## 🎤 DJ Kara & Auto-DJ *(Pro & Premium)*

| Command | Arguments | Description |
|---|---|---|
| `/autodj` | `[vibe] [action] [voice]` | Enable DJ Kara. Set a vibe (e.g. `lofi`, `hip-hop`), use `action:off` to disable, or `voice:False` to silence her. |
| `/morelikethis` | | Lock DJ Kara onto the currently playing track and keep finding similar music. |

---

## 🎚️ DJ / Queue Control

| Command | Arguments | Description |
|---|---|---|
| `/skipto` | `<position>` | Skip directly to a position in the queue. *DJ role required.* |
| `/pause` | | Pause or resume the current song. |
| `/stop` | | Stop playback and clear the queue. |
| `/volume` | `<0–150>` | Set playback volume. 100 is default. |
| `/crossfade` | | Toggle crossfade fading between tracks. |
| `/radio` | | Pick and stream a live radio station. |
| `/soundboard` | | Show your personal soundboard clips and fire one mid-playback. Basic & above. |

---

## ⚙️ Server Admin

| Command | Arguments | Description |
|---|---|---|
| `/redeem` | `<token>` | Redeem a trial token for this server. |

---

> 💬 Need help? Join [discord.gg/pulsemusicbot](https://discord.gg/pulsemusicbot) or visit [pulsemusicbot.org/support](https://www.pulsemusicbot.org/support)
