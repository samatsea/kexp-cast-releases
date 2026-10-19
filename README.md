# KEXP Cast

A Mac menu bar player for [KEXP 90.3 FM](https://www.kexp.org): live radio and
the two-week archive, the song feed with album art, stars (with an optional
Spotify playlist), show downloads, and Yamaha MusicCast speakers.

This repository holds **released builds only**: the signed and notarized app,
the [changelog](CHANGELOG.md), and the update feed (`appcast.xml`) the app
checks. The source code lives elsewhere.

## Install

1. Download the latest **KEXP-Cast-x.y.z.dmg** from [Releases](../../releases/latest).
2. Open it and drag **KEXP Cast** onto the Applications folder.
3. Open KEXP Cast from Applications. It lives in the menu bar (look for KEXP’s
   four-bar logo).

(The .zip on each release is what the app’s updater uses. If you install from
the zip instead, unzip it by double-clicking in Finder: some other unzip apps
damage the app’s signature and macOS will refuse to open it.)

Requires macOS 14 or later. Works on Apple Silicon and Intel Macs.

## Updates

KEXP Cast updates itself. New versions download in the background, and a
banner at the top of the app says when one is ready. Click **Restart to
update**, or it installs the next time the app quits. Settings → Updates has
**Check for updates** and an option to be asked before downloading.

Every update is notarized by Apple and signed with the developer's key; the app
refuses anything else.

KEXP Cast is an independent fan project and isn't affiliated with KEXP.
Support the station at [kexp.org/donate](https://www.kexp.org/donate).
