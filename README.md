# Echo for Android

Download the latest APK from **[GitHub Releases](https://github.com/GianCarlozxc/EchoRelease/releases/latest)**.

Current version: **1.7.9** · Android 8.0 or later · Package `com.dev.music`.

Echo includes a dark music player, search, albums and singles, playlists, related playlist recommendations, lyrics, offline downloads, gallery photos, and a fullscreen player opened from the lock-screen media card.

## Install

1. Download `Echo-1.7.9.apk` from the release assets.
2. Open the APK on your Android phone and allow installation from your browser or file manager when prompted.
3. If Echo is already installed with the same signing key, install the update over it to preserve your library.

`SHA256SUMS.txt` contains the APK checksum.

## Development build and account connection

This APK is the current **debug-signed development build**. Its account service is configured as `http://127.0.0.1:8787`, which requires the existing PC account server and an adb reverse connection. An Internet-hosted account service is not configured in this APK; downloading it alone does not provide public sign-in access. Music lookup and streaming require an Internet connection; downloaded audio can play offline.

## Source

The source project is maintained in [GianCarlozxc/Echo](https://github.com/GianCarlozxc/Echo). Repository access depends on the owner's permissions. This repository contains release information; APK binaries are attached to releases.

No app tests were run for this publication. The APK was built successfully and previously installed on the development phone; new playlist recommendations are awaiting manual testing.
