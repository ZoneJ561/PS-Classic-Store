# PS Classic Store

Download the latest PlayStation Classic Store build from [Releases](https://github.com/ZoneJ561/PS-Classic-Store/releases/latest).

## Install or upgrade from version 0.1.43 or earlier

1. Shut down the PlayStation Classic and back up its AutoBleem USB drive.
2. On the USB drive, remove `Apps/PS Classic Store` if it already exists. Keep `System/PS Classic Store` so your catalogs, covers, downloads, and private settings remain.
3. Extract `PS-Classic-Store-USB-<version>.zip` to the USB root.
4. Safely eject the drive, boot AutoBleem, and open PS Classic Store.

After this one-time upgrade, open **About** and press **Triangle** to check for future app updates. If one is available, press Triangle again to download and install it. Close and reopen the Store to use the new version. The updater verifies the release size and SHA-256 and keeps the previous app version as a fallback.

This public repository contains release metadata and files needed to install the app. The Store's own C/C++ source is not published here. `Third-Party-Source.zip` provides source and licenses for the bundled third-party tools.
