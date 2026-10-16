# Echo for Android

Download the latest APK from **[GitHub Releases](https://github.com/GianCarlozxc/EchoRelease/releases/latest)**.

Current version: **1.8.5** · Android 8.0 or later · Package `com.dev.music`.

Echo includes a dark music player, search, albums and singles, playlists, related playlist recommendations, lyrics, offline downloads, gallery photos, and a fullscreen player opened from the lock-screen media card.

## Install

1. Download `Echo-1.8.5.apk` from the release assets.
2. Open the APK on your Android phone and allow installation from your browser or file manager when prompted.
3. If Echo is already installed with the same signing key, install the update over it to preserve your library.

`SHA256SUMS.txt` contains the APK checksum.

## Development build and account connection

Echo 1.8.1 connects to the public [Echo account service](https://echo-accounts-giancarlozxc.easyperch3.chatgpt.site) over HTTPS. Anyone can sign up with a username, password, and country; no PC or adb connection is required. Existing accounts and active sessions were migrated, preserving account IDs and local libraries on update. Account identity and country work across phones; playlists, likes, downloads, and gallery photos stay on each phone. Music lookup and streaming require Internet; completed audio downloads can play offline. This APK retains the existing debug signing key for compatible development updates.

## Source

The source project is maintained in [GianCarlozxc/Echo](https://github.com/GianCarlozxc/Echo). Repository access depends on the owner's permissions. This repository contains release information; APK binaries are attached to releases.

No app tests were run for this publication. The APK built successfully. No tests were run and version 1.8.5 was not installed on the phone; install it manually. This release removes the duplicate About Echo row from Profile; About Echo remains in Settings. Echo also attempts to reopen after a successful in-app update, with an update notification as fallback when allowed. Android may prevent automatic reopening. Play Protect warnings are separate and are not bypassed or resolved by this feature.

## Update inside Echo

After installing version 1.8.0, open **Profile → Settings → App updates** to check for future releases. An **App updates** link is also available on the login screen. Echo downloads the APK inside the app and checks its checksum, identity, version, and signing certificate. Android asks for permission and approval to install the update; no GitHub browser visit is needed. Cancelling installation keeps the verified APK ready to retry.