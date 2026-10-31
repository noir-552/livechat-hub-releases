# LiveChat Hub — releases

This repository contains **only app releases** of LiveChat Hub (Android APK, macOS, Windows, Linux). The source code is private and is not published here.

Download from [Releases](https://github.com/noir-552/livechat-hub-releases/releases). Builds marked *Pre-release* are test builds.

- **Android:** `LiveChatHub-…-vc<N>.apk`
- **macOS (Apple Silicon):** `LiveChatHub-…-macos-arm64.dmg` — first open: right-click → Open.
- **Windows 10/11 x64:** `LiveChatHub-…-windows-x64-setup.exe` — SmartScreen: More info → Run anyway.
- **Linux:** `LiveChatHub-…-linux-x64.AppImage` or `…-linux-arm64.AppImage` — make executable and run.

The apps check this repository for updates on start and install only after you tap **Unduh & pasang**. Android downloads are checked against the SHA-256 digest GitHub publishes and must be the same app with a newer version (Android also requires the same signing key). Desktop updates (`desktop/latest.json`) must carry a signature made with the project's private update key, verified by the app before installing.
