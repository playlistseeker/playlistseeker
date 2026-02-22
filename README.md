# PlaylistSeeker

<p align="center">
  <img src="https://github.com/playlistseeker/playlistseeker/blob/main/header.JPG?raw=true" alt="PlaylistSeeker header" width="720" />
</p>

<p align="center">
  <a href="https://github.com/playlistseeker/playlistseeker/releases/latest">
    <img alt="Latest Release" src="https://img.shields.io/github/v/release/playlistseeker/playlistseeker?display_name=tag&sort=semver" />
  </a>
  <img alt="Platform" src="https://img.shields.io/badge/macOS-Apple%20Silicon-black?logo=apple&logoColor=white" />
  <img alt="App" src="https://img.shields.io/badge/App-Electron-191970?logo=electron&logoColor=white" />
</p>

Release channel for PlaylistSeeker desktop builds.

This repository is intended for binary releases, release notes, and support tracking.

## Source availability

PlaylistSeeker is currently distributed as prebuilt binaries.
This repository is not a full open-source project at this time.

## Latest release

- Current stable: **v1.1.0**
- Release page: [github.com/playlistseeker/playlistseeker/releases/latest](https://github.com/playlistseeker/playlistseeker/releases/latest)

## Download

- **For most users, just click this:** [PlaylistSeeker-1.1.0-arm64.dmg](https://github.com/playlistseeker/playlistseeker/releases/download/v1.1.0/PlaylistSeeker-1.1.0-arm64.dmg)
- Drag `PlaylistSeeker.app` to `Applications`.

## Install (macOS)

### DMG flow (recommended)

1. Download `PlaylistSeeker-1.1.0-arm64.dmg`.
2. Open the DMG.
3. Drag `PlaylistSeeker.app` to `Applications`.
4. First run on unsigned builds: right-click app -> `Open`.

## Upgrade policy

- Upgrades are safe-replace installs of `/Applications/PlaylistSeeker.app`.
- User data is preserved under `~/Library/Application Support/...`.
- Credentials remain in macOS Keychain.

## Verify download integrity

Checksums file (release asset):

- [PlaylistSeeker-1.1.0-arm64-SHA256SUMS.txt](https://github.com/playlistseeker/playlistseeker/releases/download/v1.1.0/PlaylistSeeker-1.1.0-arm64-SHA256SUMS.txt)

Then verify locally:

```bash
shasum -a 256 PlaylistSeeker-1.1.0-arm64.dmg
```

## Report issues

- Use GitHub Issues for bugs/feature requests.
- Use the in-app `Report` action if easier.
- Include app version, macOS version, and repro steps.

## Privacy

- Soulseek credentials are stored locally (Keychain).
- Playlist and track data remain local unless you explicitly submit a report.

## Support

If PlaylistSeeker saves you time, you can support development:

- [Buy Me a Coffee](https://buymeacoffee.com/playlistseeker)

## Legal

- Binaries are provided as-is for personal use.
- No warranty is provided.
