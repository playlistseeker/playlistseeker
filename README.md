# PlaylistSeeker

<p align="center">
  <img src="https://github.com/playlistseeker/playlistseeker/blob/main/header.JPG?raw=true" alt="PlaylistSeeker header" width="720" />
</p>

<p align="center">
  <img alt="macOS" src="https://img.shields.io/badge/macOS-000000?logo=apple&logoColor=white" />
  <img alt="Apple Silicon" src="https://img.shields.io/badge/Apple%20Silicon-arm64-000000?logo=apple&logoColor=white" />
  <img alt="Electron" src="https://img.shields.io/badge/Electron-191970?logo=electron&logoColor=white" />
</p>

<p align="center">
  <a href="https://buymeacoffee.com/playlistseeker">
    <img alt="Buy me a coffee" src="https://img.shields.io/badge/Buy%20me%20a%20coffee-FFDD00?logo=buy-me-a-coffee&logoColor=000000" />
  </a>
</p>

## What This Is

I spend way too much time on YouTube and Discogs finding music. That part’s great. The part that sucks is turning a long playlist into actual files.

PlaylistSeeker is a macOS app I built to skip that part. Paste a YouTube playlist, it handles the Soulseek searching and downloading.

I love Soulseek. The community is incredible and it’s the only place you’ll find half the stuff I look for. I just got tired of the manual loop.

## Workflow

```mermaid
flowchart LR
  A["YouTube playlist URL"] --> B["Track list"]
  B --> C["Search queue"]
  C --> D["Candidate matches"]
  D --> E["Download"]
  E --> F["Temp folder (incomplete)"]
  F --> G["Final folder (complete)"]
```

---

## Why I Built It

I buy records when I can. I go to shows. But I still need digital files for mixing and for listening when I'm not at home. Spotify doesn't carry most of what I dig for.

So the routine was: find tracks, save them, then spend the rest of the night doing repetitive searches. Building this was faster than doing that again for another 40-track playlist.

---

## Support Artists

This helps you organise your library. It's not a reason to stop buying music.

If a track hits, buy it. Bandcamp, Beatport, Juno, Discogs, wherever. Go to shows. Grab the vinyl when you can. Underground music only keeps going if people actually support it.

---

## Features

- Import YouTube playlists
- Automated Soulseek search queue with live status
- Smart retries with cleaned-up search terms
- Handles year noise and formatting junk
- Manual candidate selection when you need it
- Metadata panel
- In-app bug reporting

## Preview

![PlaylistSeeker app icon](iconplaylist.png)

---

## Download

Latest release (Apple Silicon):

- `PlaylistSeeker-1.0.0-arm64.dmg`
- GitHub Release: `YOUR_GITHUB_RELEASE_LINK`

---

## Install (macOS)

1. Download the DMG
2. Drag `PlaylistSeeker.app` to Applications
3. First launch: right-click → Open (unsigned, I'm not paying Apple $99/year for this)

---

## Usage

1. Connect your Soulseek credentials
2. Paste a YouTube playlist URL
3. Hit start
4. Statuses:
   - `Search queued`
   - `Searching`
   - `Downloading`
   - `No match yet` (retry scheduled)
   - `Downloaded`
5. Use **Search Now** or candidate controls to step in manually

---

## Good to Know

- Unsigned build. macOS will complain. Normal.
- YouTube embeds can be blocked in desktop apps, fallback preview is there
- Incomplete downloads stay in a temp folder until they're done
- Something broken? Hit the Report button

---

## Privacy

- Soulseek credentials stay on your machine
- Bug reports use environment variables for delivery, nothing hardcoded

---

## Roadmap

- Duplicate detection
- More metadata options
- Presets for different digging styles
- Update notifications

Side project. No timeline.

---

## Contributing

Found a bug? Got an idea?

Use the **Report** button in the app. It sends what you type to a Proton Mail inbox. No account needed.

---

## Support

If this saved you time, please buy me a coffee — it genuinely helps keep this project alive.

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20me%20a%20coffee-FFDD00?logo=buy-me-a-coffee&logoColor=000000)](https://buymeacoffee.com/playlistseeker)

- Buy Me a Coffee: `https://buymeacoffee.com/playlistseeker`

---

## License

ISC
