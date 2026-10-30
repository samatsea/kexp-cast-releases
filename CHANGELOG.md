# KEXP Cast changelog

Versions follow MAJOR.MINOR.PATCH. Each release also has a build number that
only goes up; that's what the updater compares.

## 0.5.6 — 2026-10-30

- **Outage notice:** when KEXP’s servers stop answering (or your Mac is
  offline), a notice under the tabs says so, instead of the feed and archive
  just sitting empty. The app keeps trying, and once KEXP is back the feed and
  archive reload by themselves.

## 0.5.5 — 2026-10-25

- **Finer volume control:** click the speaker icons at either end of the volume
  slider to turn it down or up a little (5% per click). Works for this Mac and
  for speakers.

## 0.5.4 — 2026-10-21

- The menu bar equalizer is calmer: quiet passages now look quiet instead of
  turning back up to full height after a few seconds, and only real peaks
  reach the top.

## 0.5.3 — 2026-10-21

- On the Radio tab, the colour from the album art now runs all the way up
  behind the header and tab bar again.

## 0.5.2 — 2026-10-21

- **Calmer tab bar:** the tab icons now stay in place. Picking a tab fades its
  name in where the icon was, instead of sliding everything over.

## 0.5.1 — 2026-10-21

- **New tab bar:** Settings moved out of the header and into the tabs. The
  selected tab shows its name; the others are icons only.
- The Feed tab is now called Radio.

## 0.5.0 — 2026-10-21

- **New layout:** the tabs now sit at the top, just under the controls. The
  player lives on the Feed tab, and Archive, Starred, Downloads and Settings
  each get the whole window.
- The Saved tab is now called Downloads.

## 0.4.4 — 2026-10-20

- **Fix:** listening through several archive shows in a row could leave the
  timeline stuck once you reached a show that was still on air when you started
  (it kept showing the earlier show). The app now re-checks the schedule and
  moves on correctly.
- **Fix:** the Archive tab’s list for today now updates by itself, so shows that
  finish airing while the app is open appear without reopening the tab.
- **Right-click the menu bar icon** (or Control-click) for Play/Pause, Open in
  Window, Check for Updates, and Quit.

## 0.4.3 — 2026-10-18

- **Easier-to-see volume control:** a white knob, KEXP-yellow fill and brighter
  speaker icons, so it stands out over bright album art.

## 0.4.2 — 2026-10-18

- A little breathing room at the top of the feed, so the newest song doesn’t
  touch the tab bar (it scrolls away as you scroll).
- “Check for updates” now sees a new version the moment it’s published, instead
  of up to 5 minutes later.

## 0.4.1 — 2026-10-18

- **Menu bar:** the icon is now KEXP’s four-bar logo mark all the time. When
  music plays, those same bars start moving with it, and settle back into the
  logo when you stop.
- **Speaker button:** now just the speaker icon and arrow; room names are in the menu
  (hover the button to see where it’s playing).

## 0.4.0 — 2026-10-17

- **Sonos:** KEXP Cast now plays on Sonos speakers as well as MusicCast. Pick a
  room (or several, to play them in sync) from the speaker menu — live or any
  archive show. Stereo pairs and subs show up as one room, Sonos volume works
  from the app, and the menu bar bars stay in time with the speaker.
- The speaker menu lists Sonos and MusicCast rooms separately. Rooms only sync
  within one brand, so picking the other kind switches over.

## 0.3.0 — 2026-10-17

- **New player layout:** volume, speaker picker, settings and pop-out now sit in
  the header. The current show (with Go live / From the top) is above the song,
  the song sits in its own card, and the playback controls are centred.
- **DJ notes moved to the feed:** click the quote button on any song to read its
  note. The player no longer grows and shrinks with long notes.
- The feed starts right under the tabs, and Settings opens from the gear.

## 0.2.2 — 2026-10-17

- **Fix:** the update banner’s buttons (Download, Restart to update, ✕) didn’t
  respond to clicks — the album-art backdrop below was catching them.
- “Check for updates” now always says what happened.

If you’re on 0.2.0 or 0.2.1: this update downloads by itself within a day and
installs when you quit KEXP Cast.

## 0.2.1 — 2026-10-17

- **Fix:** with the player popped out into its own window, clicking the menu bar
  icon showed the small “popped out” card floating inside a large empty window.
  The menu now fits the card (and goes back to full size when you pop back in).
- First update delivered through the new automatic updater.

## 0.2.0 — 2026-10-17

- **New name:** KEXP Bar is now KEXP Cast. Your settings, stars and speakers carry over.
- **Automatic updates:** new versions download in the background. A banner at the
  top of the app says when one is ready; click “Restart to update” or just let it
  install the next time the app quits. Settings has “Check for updates” and an
  option to be asked before downloading.
- **Menu bar:** the KEXP wordmark when idle; while playing, the four logo bars move
  with the music (timed to what your speakers are actually playing).
- **Pop-out window:** open the player in its own window from the top-right button;
  close it or press the pop-in button to put it back in the menu bar.
- **Speakers:** archive shows stream reliably to MusicCast (a minute buffered on the
  Mac, reconnects without repeating), clean handovers every 3 hours, and both
  speakers are found right after launch.
- New app icon from KEXP’s logo; roomier day picker in the Archive.

## 0.1.0 — 2026-10-17

First version (as KEXP Bar): live KEXP and the two-week archive, the song feed,
stars, show downloads, and Yamaha MusicCast speakers.
