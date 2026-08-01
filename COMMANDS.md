# Pulse Bot — Full Command Reference

> Full docs at [pulsemusicbot.org/commands](https://www.pulsemusicbot.org/commands)

All commands use Discord slash command syntax (`/command`). 52 top-level commands, several with their own subcommands.

---

## 🎵 Music

| Command | Arguments | Description |
|---|---|---|
| `/play` | `[query]` | Play a song, URL, or playlist. Adds to queue if music is already playing. |
| `/playnext` | `<query>` | Play a song next, jumping the queue. *DJ only.* |
| `/search` | `<query>` | Search YouTube and select a song to play. |
| `/queue` | | Show the current music queue. |
| `/skip` | | Vote to skip the current song. |
| `/remove` | `<position>` | Remove a song from the queue by position. |
| `/shuffle` | | Shuffle the songs you've added to the queue. |
| `/seek` | `<position>` | Seek to a position in the current track, e.g. `1:30`, `+10`, `-30`. |
| `/nowplaying` | | Show the currently playing song. |
| `/history` | | Show the last 10 recently played tracks. |
| `/replay` | `[position]` | Re-queue a track from the history. Defaults to the most recent. |
| `/lyrics` | `[song]` | Show the lyrics of the current or a given song. |
| `/playlist` | `<create \| delete \| add \| addsong \| remove \| play \| list \| view>` | Manage your personal playlists. |

---

## 🎛️ Audio Effects

Stack effects, go wild, reset with `/clearfilters`. All *DJ only*.

| Command | Arguments | Description |
|---|---|---|
| `/bass` | `[level]` | Set bass boost level, 0–200 (0 = off). |
| `/nightcore` | | Toggle nightcore mode — faster and higher pitch. |
| `/vaporwave` | | Toggle vaporwave mode — slower and lower pitch. |
| `/tremolo` | | Toggle tremolo effect — rhythmic volume oscillation. |
| `/eightd` | | Toggle 8D spatial audio effect. |
| `/slowreverb` | | Toggle slow + reverb lofi effect. |
| `/pitch` | `[semitones]` | Shift pitch by semitones, -12 to +12. |
| `/distortion` | `[level]` | Set distortion/saturation level, 0 = off, 1–100 = intensity. |
| `/lowpass` | `[cutoff]` | Low-pass filter — muffle high frequencies. 0 = off, 200–18000 Hz. |
| `/clearfilters` | | Remove all active audio filters. |

---

## 🎚️ DJ / Queue Control

| Command | Arguments | Description |
|---|---|---|
| `/pause` | | Pause or resume the current song. |
| `/stop` | | Stop playback and clear the queue. |
| `/volume` | `[level]` | Set or show the current volume, 0–150. |
| `/skipto` | `<position>` | Skip to a specific position in the queue. |
| `/forceskip` | | Force-skip the current song without a vote. *DJ only.* |
| `/forceremove` | `<user>` | Remove all of a user's songs from the queue. *DJ only.* |
| `/movetrack` | `<from> <to>` | Move a track to a different queue position. *DJ only.* |
| `/repeat` | `[off \| all \| single]` | Set repeat mode. *DJ only.* |
| `/crossfade` | | Toggle crossfade fading between tracks. *DJ only.* |
| `/radio` | | Pick and play a live radio station. *DJ only.* |

---

## 🎤 DJ Kara & Auto-DJ *(Pro & Premium)*

| Command | Arguments | Description |
|---|---|---|
| `/autodj` | `[vibe] [action] [voice]` | Keep the music going automatically based on history or a vibe (e.g. `lofi`, `hip-hop`, `charts`). `action:off` disables it, `voice:False` silences Kara. |
| `/morelikethis` | | Anchor Auto-DJ to the currently playing track and find similar music. |
| `/request` | `<song> <dedication>` | Request a song with a dedication — Kara reads it out on air before the track plays. |
| `/shoutout` | `<message>` | Drop a quick shoutout — Kara might give it a nod at the next chapter. |
| `/show` | `<add \| list \| remove>` | Schedule a recurring radio show that Kara hosts, with a name, time, day, vibe, and timezone. |

---

## 📊 Listening Stats

| Command | Arguments | Description |
|---|---|---|
| `/wrapped me` | | Your personal listening recap for the last 30 days. |
| `/wrapped server` | | The whole server's recap — top tracks, top requesters, most dedicated listener. |
| `/wrapped match` | `<user>` | Taste-compatibility score between you and another listener. |

---

## 🔊 Soundboard

| Command | Arguments | Description |
|---|---|---|
| `/soundboard` | | Play your personal soundboard clips in voice. *Basic & above.* |
| `/clip` | `<name> [seconds] [emoji]` | Save what just played as a soundboard clip. |

---

## 👋 Welcome Messages

| Command | Arguments | Description |
|---|---|---|
| `/welcome channel` | `<channel>` | Choose where greetings are posted (turns them on). |
| `/welcome message` | `<text>` | Set the greeting text. Use `{user}` `{username}` `{server}` `{count}` as placeholders. |
| `/welcome test` | | Post the greeting now, as if you had just joined. |
| `/welcome status` | | Show the current greeting setup. |
| `/welcome off` | | Turn greetings off. |

---

## ⚙️ Server Admin

| Command | Arguments | Description |
|---|---|---|
| `/settings` | | View Pulse's current settings for this server. |
| `/setdj` | `[role]` | Set the DJ role for this server (omit to clear it). |
| `/settc` | `[channel]` | Lock music commands to one text channel (omit to unlock). |
| `/setvc` | `[channel]` | Lock the bot to one voice channel (omit to unlock). |
| `/setskip` | `[percent]` | Set the vote-skip percentage for this server. |
| `/queuetype` | `<fair \| linear>` | Switch between fair (round-robin per user) and linear (first-come-first-served) queue modes. |

---

## 🆘 General

| Command | Arguments | Description |
|---|---|---|
| `/help` | | Show all Pulse commands. |
| `/about` | | About Pulse Music Bot. |
| `/vote` | | Vote for Pulse on top.gg for a temporary bigger queue limit. |
| `/redeem` | `<token>` | Redeem a trial token for this server. |

---

> 💬 Need help? Join [discord.gg/pulsemusicbot](https://discord.gg/pulsemusicbot) or visit [pulsemusicbot.org/support](https://www.pulsemusicbot.org/support)
