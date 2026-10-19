# Echo for Android

Download the latest APK from **[GitHub Releases](https://github.com/GianCarlozxc/EchoRelease/releases/latest)**.

Current version: **1.8.12** · Android 8.0 or later · Package `com.dev.music`.

Echo includes a dark music player, search, albums and singles, playlists, related playlist recommendations, lyrics, offline downloads, gallery photos, and a fullscreen player opened from the lock-screen media card.

## Install

1. Download `Echo-1.8.12.apk` from the release assets.
2. Open the APK on your Android phone and allow installation from your browser or file manager when prompted.
3. If Echo is already installed with the same signing key, install the update over it to preserve your library.

`SHA256SUMS.txt` contains the APK checksum.

## Development build and account connection

Echo 1.8.1 connects to the public [Echo account service](https://echo-accounts-giancarlozxc.easyperch3.chatgpt.site) over HTTPS. Anyone can sign up with a username, password, and country; no PC or adb connection is required. Existing accounts and active sessions were migrated, preserving account IDs and local libraries on update. Account identity and country work across phones; playlists, likes, downloads, and gallery photos stay on each phone. Music lookup and streaming require Internet; completed audio downloads can play offline. This APK retains the existing debug signing key for compatible development updates.



## Update inside Echo

After installing version 1.8.0, open **Profile → Settings → App updates** to check for future releases. An **App updates** link is also available on the login screen. Echo downloads the APK inside the app and checks its checksum, identity, version, and signing certificate. Android asks for permission and approval to install the update; no GitHub browser visit is needed. Cancelling installation keeps the verified APK ready to retry.


Version 1.8.9 adds an in-app update prompt with Update and Later choices while Echo is open. Update starts downloading and opens App updates; Later postpones the same version for 24 hours. Install 1.8.9 once to receive prompts for subsequent releases.

Version 1.8.10 adds a + button beside Your playlists in Library to create an empty playlist.

Version 1.8.11 checks for updates immediately when Echo opens or returns, then every 30 seconds while open. The prompt appears directly after detection. Automatic checks use update.json; network speed and publication caching can affect detection. Later still postpones that version for 24 hours.

Version 1.8.12 excludes songs in your saved recommendation history when refreshing Trending, mood picks, and playlist recommendations. If no new songs are found, it shows fewer songs or an empty state rather than recycling old songs.
