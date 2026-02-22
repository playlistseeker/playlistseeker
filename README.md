# PlaylistSeeker

<p align="center">
  <img src="https://github.com/playlistseeker/playlistseeker/blob/main/header.JPG?raw=true" alt="PlaylistSeeker header" width="720" />
</p>

<p align="center">
  <a href="https://github.com/playlistseeker/playlistseeker/releases/latest">
    <img alt="Latest Release" src="https://img.shields.io/github/v/release/playlistseeker/playlistseeker?display_name=tag&sort=semver" />
  </a>
  <img alt="Platform" src="https://img.shields.io/badge/macOS-Apple%20Silicon-black?logo=apple&logoColor=white" />
</p>

PlaylistSeeker is a macOS app for music lovers who dig on YouTube and download through Soulseek.

Paste a playlist, let it search, and build your local collection faster.

## Download (just click this)

- [PlaylistSeeker-1.1.0-arm64.dmg](https://github.com/playlistseeker/playlistseeker/releases/download/v1.1.0/PlaylistSeeker-1.1.0-arm64.dmg)

## Install (2 minutes)

1. Download the DMG.
2. Open it.
3. Drag `PlaylistSeeker.app` into `Applications`.
4. First launch on unsigned builds: right-click app, then `Open`.

## What's New In v1.1

- You can now start/stop each playlist independently.
- New missing-file handling: the app remembers it was downloaded before, marks it as missing, and offers one-click re-download.
- Search Monitor is clearer with quick selection preferences: bitrate, file size, speed, and queue status.
- Column resizing and overall layout behavior improved.
- Missing videos in playlists that return `[Deleted video]` are handled correctly.
- Login/create flow hardened: bounded timeouts, clearer error codes, no infinite loading state.

## Quick Use

1. Connect your Soulseek account.
2. Add a YouTube playlist URL.
3. Select a playlist in the left panel.
4. Press Start Queue for that playlist.
5. Use `Report` in-app if something looks wrong.

## Upgrades

- Replacing `/Applications/PlaylistSeeker.app` keeps your local data and settings.
- Credentials stay in macOS Keychain.

## Privacy

- Credentials are stored locally (Keychain).
- Playlist and track data stay local unless you send a report.

## Support

- Issues: [GitHub Issues](https://github.com/playlistseeker/playlistseeker/issues)
- Optional support: [Buy Me a Coffee](https://buymeacoffee.com/playlistseeker)

## Source Availability

This repository is currently a release/support channel, not a full open-source codebase.
