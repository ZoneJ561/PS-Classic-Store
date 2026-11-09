# PS Classic Store

![PS Classic Store banner](banner.png)

PS Classic Store is a catalog browser and downloader for the PlayStation Classic running AutoBleem 2. Browse your own PS1 game, ROM, and app catalogs from one controller-friendly app.

## Download

[Download PS Classic Store 0.1.48 for USB](https://github.com/ZoneJ561/PS-Classic-Store/releases/download/v0.1.48/PS-Classic-Store-USB-0.1.48.zip)

There is **one ZIP**. Its `Apps/` folder is ready to drag onto the root of an AutoBleem USB drive. The ZIP includes the app and required third-party notices and source; it does not contain games, populated download catalogs, account cookies, kernel files, or Wi-Fi changes. An artwork lookup lets the app fetch ROM covers on demand.

## Built-in App Updates

Open **About** and press **Triangle** to check for a newer app version. If one is available, press Triangle again to download and install it. Close and reopen the Store to start the new version. The download is checked against the published size and SHA-256 before a separate USB version folder is activated. Your current version stays available if an update fails.

## Features

- Browse separate **NPS PSX**, **PSX Games**, **ROMs**, **Apps**, **Installed**, **Sources**, and **Packages** sections.
- Search listings, filter regions and ROM systems, and view game details and cover art. ROMs use 3D box, cabinet, cartridge, or front-cover art from the [LaunchBox Games Database](https://gamesdb.launchbox-app.com/) when available. NPS and PSX games can display region-matched 3D CD box art supplied in the catalog; other covers remain available as a fallback. Older emulator entries appear under Apps.
- Download PS1 disc archives, catalog ROMs, and apps from user-supplied HTTPS TSV feeds.
- Queue downloads, follow progress, and cancel an active job.
- Convert supported PS1 packages to BIN/CUE files for AutoBleem.
- Support up to 32 catalog feeds. Catalog URLs refresh when the app opens.
- Stage and verify downloads before installing them. Existing game and app folders are protected from silent replacement.

## Getting Started

1. Shut down the PlayStation Classic and back up its AutoBleem USB drive.
2. For a first install or an upgrade from 0.1.43 or earlier, remove only the old `Apps/PS Classic Store` folder if present. Keep `System/PS Classic Store` so your catalogs, covers, downloads, and private settings remain.
3. Extract the release ZIP to the **USB root**, merging its `Apps/` folder.
4. Safely eject the drive, boot AutoBleem, and open **PS Classic Store** from Apps.

Users with the updater can move to 0.1.48 directly from **About**, without copying the ZIP from a PC. The installed version appears on the About page.

## Add Catalogs

The ZIP includes blank catalog templates with column headers only. **No downloadable game entries are preloaded.** Add your own TSV files under `System/PS Classic Store/sources/` on the USB, or add HTTPS TSV URLs under `System/PS Classic Store/sources.d/`. Game lists and downloaded content in `System/PS Classic Store` are kept when the app updates.

## Project Updates and Support

- Follow the creator on Instagram: [@god1ynigga](https://www.instagram.com/god1ynigga/)
- Support development: [Venmo](https://venmo.com/u/godlynigga)
