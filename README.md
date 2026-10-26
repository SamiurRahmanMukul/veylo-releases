# Veylo app releases

Downloads and update files for the Veylo apps: the **desktop app** (Windows, macOS and Linux) and the **Android app**. The iPhone app is coming soon.

This repository only hosts release files. It contains no source code.

## Download

The easiest way is the Veylo download page, which always links to the newest version for your device: https://veylo-chat-app.onrender.com/download

| App                             | Release tag          | Files                                                      |
| ------------------------------- | -------------------- | ---------------------------------------------------------- |
| Desktop (Windows, macOS, Linux) | `v<version>`         | `veylo-desktop-<version>.exe`, `.dmg`, `.AppImage`, `.deb` |
| Android                         | `android-v<version>` | `veylo-android-<version>.apk`                              |
| iPhone                          | Coming soon          | App Store                                                  |

- **Older versions:** see [Releases](../../releases).
- GitHub's "latest" release is always the desktop app. Android builds are separate `android-v…` releases and are never marked "latest", so the two never get in each other's way.

## Updates

- **Desktop:** the app checks here and updates itself.
- **Android:** install the newer `.apk` over the old one. Your account and chats stay, because they live on the Veylo server.

## Installing the Android app

1. Download the `.apk` on your phone and open it.
2. If Android asks, allow your browser to **install unknown apps**, then tap **Install**.
3. If Play Protect warns that the app isn't from the store, choose **Install anyway**.
4. Open Veylo, sign in, and allow notifications so calls can ring.

Veylo is not on Google Play yet. When it is, the download page will link to the store.

## First time opening the desktop app?

The desktop installers aren't signed with a paid developer certificate yet, so your system may warn you the first time:

- **macOS:** open Veylo from Applications. If it can't be opened, go to System Settings → Privacy & Security and click **Open Anyway**.
- **Windows:** if SmartScreen appears, click **More info**, then **Run anyway**.
- **Linux:** make the AppImage executable (`chmod +x veylo-desktop-*.AppImage`) and run it, or install the `.deb` with `sudo apt install ./veylo-desktop-*.deb`.
