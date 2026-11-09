# PS Classic Store

![PS Classic Store banner](banner.png)

PS Classic Store is a catalog browser and downloader for the PlayStation Classic running AutoBleem 2. Browse your own PS1 game, ROM, app, and emulator catalogs from one controller-friendly app.

## Download

[Download PS Classic Store 0.1.45 for USB](https://github.com/ZoneJ561/PS-Classic-Store/releases/download/v0.1.45/PS-Classic-Store-0.1.45.zip)

There is **one ZIP**. Its `Apps/` folder is ready to drag onto the root of an AutoBleem USB drive. The ZIP includes the app and required third-party notices and source; it does not contain games, populated game lists, account cookies, kernel files, or Wi-Fi changes.

## Built-in App Updates

Open **About** and press **Triangle** to check for a newer app version. If one is available, press Triangle again to download and install it. Close and reopen the Store to start the new version. The download is checked against the published size and SHA-256 before a separate USB version folder is activated. Your current version stays available if an update fails.

## Features

- Browse separate **NPS PSX**, **PSX Games**, **ROMs**, **Apps**, **Installed**, **Sources**, and **Packages** sections.
- Search listings, filter regions and ROM systems, and view game details and cover art.
- Download PS1 disc archives, catalog ROMs, apps, and emulators from user-supplied HTTPS TSV feeds.
- Queue downloads, follow progress, and cancel an active job.
- Convert supported PS1 packages to BIN/CUE files for AutoBleem.
- Support up to 32 catalog feeds. Catalog URLs refresh when the app opens.
- Stage and verify downloads before installing them. Existing game and app folders are protected from silent replacement.

## Getting Started

1. Shut down the PlayStation Classic and back up its AutoBleem USB drive.
2. For a first install or an upgrade from 0.1.43 or earlier, remove only the old `Apps/PS Classic Store` folder if present. Keep `System/PS Classic Store` so your catalogs, covers, downloads, and private settings remain.
3. Extract the release ZIP to the **USB root**, merging its `Apps/` folder.
4. Safely eject the drive, boot AutoBleem, and open **PS Classic Store** from Apps.

Users who already have 0.1.44 can test the built-in update to 0.1.45 directly from **About**, without copying the ZIP from a PC.

## Add Catalogs

The ZIP includes blank catalog templates with column headers only. **No game entries are preloaded.** Add your own TSV files under `System/PS Classic Store/sources/` on the USB, or add HTTPS TSV URLs under `System/PS Classic Store/sources.d/`. Game lists and downloaded content in `System/PS Classic Store` are kept when the app updates.

## Project Updates and Support

- Follow the creator on Instagram: [@god1ynigga](https://www.instagram.com/god1ynigga/)
- Support development: [Venmo](https://venmo.com/u/godlynigga)

## About This Repository

This is the public release page for PS Classic Store, similar to the [PKGi Enhanced release page](https://github.com/ZoneJ561/PKGi-Enhanced). The Store's own C/C++ source and build workflow are maintained separately. Corresponding source and licenses for the bundled third-party tools are included **inside the single release ZIP** at `Apps/PS Classic Store/third-party-source/`.
