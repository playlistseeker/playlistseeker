# PlaylistSeeker
From YouTube and Discogs rabbit holes to clean local files. Built for real diggers.


## What This Is

I spend way too much time on YouTube and Discogs finding music. That part's great. But then I've got 30+ tracks saved and I'm sitting there doing manual Soulseek searches one by one, fixing typos, waiting on retries, moving files around. For hours.

PlaylistSeeker is a macOS app I built to skip that part. You give it a YouTube playlist, it handles the Soulseek searching and downloading. That's basically it.

I love Soulseek. The community is incredible and it's the only place you'll find half the stuff I look for. I just got tired of the manual workflow around it when I'm working through long playlists.

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

---

## Download

Latest release (Apple Silicon):


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

Found a bug? Or got improvement suggestions? Use the button in the app. The app doesn't story any privacy info, hitting the button and typing will just send the feedback to a proton mail account :)
---

## Support

If this saved you time:

- Buy Me a Coffee: `https://buymeacoffee.com/YOUR_HANDLE`
- Ko-fi: `https://ko-fi.com/YOUR_HANDLE`

---

## License

ISC
