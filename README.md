# Views

A fast, offline photo and video gallery for Android. Smooth on libraries of 50,000+ items, private by design.

**This repository only hosts the app (APK) and its description. The source code is not published.**

## Download

Get the latest APK from the [Releases](../../releases/latest) page.

**Requires Android 13 (API 33) or newer.** Tested on one device (Motorola Edge 60 Pro, Android 17), so treat it as
early software.

### Install

1. Download `views-<version>.apk` on your phone.
2. Open it. Android will ask you to allow installing apps from this source (your browser or file manager); allow it.
3. Play Protect may warn that the app is from an unknown developer. This is expected for apps outside the Play Store.
4. Open **Views** and grant access to photos and videos.

To check the download, compare its SHA-256 with the one in the release notes.

## Privacy

- **No internet permission.** The app cannot send anything anywhere. No analytics, no cloud, no ads.
- Your photos stay where they are. The app reads them through Android's media library.

## Features

- **Pictures timeline**: photos and videos grouped by day, pinned day headers, video duration badges and a
  fast-scroll handle with a month bubble. New camera photos appear without restarting.
- **Pinch to resize the grid** (2 / 4 / 6 columns, plus a month view).
- **Viewer**: swipe between photos, pinch and double-tap zoom (also on huge images), drag to dismiss, a filmstrip,
  and a details panel with date, file name, size, camera, exposure and location.
- **Video**: scrubber, mute, speed (0.25x to 2x), keep-screen-on and resume where you stopped.
- **GIFs, motion photos and Ultra HDR** are supported, with a "Motion and GIFs" collection.
- **Albums** are your phone's own folders: pin, reorder, sort, create, move photos between folders, and
  delete (to Trash).
- **Locked**: a private space opened with your fingerprint or screen lock; unlocking puts everything back.
- **Selection**: long-press then drag to select a range; share, favourite, move, lock, copy, trash.
- **Favourites, Videos, Trash** pages. Trash restores or deletes forever, with confirmation.
- **Search** by date, album, file name and type.
- **One-handed reach**: pull any grid down to bring the top within thumb reach.
- Material You colours, light and dark themes, four app icon styles (Dusk, Light, Midnight, Ocean).
- Opens photos and videos from other apps, even without media permission.

## Safe by design

- Original files are never edited in place; edits are saved as copies.
- Delete moves items to the system trash first, and permanent deletion only happens from Trash after confirming.
- Moving a photo keeps its date, name, favourite mark and metadata. Where Android refuses an in-place move, the
  photo is copied, checked byte for byte, and only then is the original removed.

Even so, this is a personal project: **keep a backup of photos you care about**, and note that uninstalling the app
erases anything inside Locked.

## Feedback

Open an [issue](../../issues) with your phone model, Android version and what happened.
