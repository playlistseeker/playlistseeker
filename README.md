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

- Queue control is now per playlist. Start/pause one playlist without affecting others.
- Sidebar playlist controls are easier to use.
- Search-term editing no longer gets interrupted by queue refreshes.
- Deleted tracks stay deleted after playlist refresh.
- Unavailable YouTube items like `[Deleted video]` or `n/a` are skipped.
- New yellow state: `Downloaded before, file missing` with manual `Re-download`.
- Optional largest-file mode now avoids very long outlier matches.
- Browser view is cleaner: resizable columns and hideable inspector.
- Login/create flow now fails fast with clear timeout/network messages.

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
