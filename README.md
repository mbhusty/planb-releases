# PlanB — Android releases

Signed Android builds of **PlanB**, a Formula 1 companion app for iOS and
Android. This repository holds releases and nothing else — no source code.

- **Download the latest APK:** [PlanB-android.apk](https://github.com/mbhusty/planb-releases/releases/latest/download/PlanB-android.apk)
- **Every version, with release notes:** https://p1anb.vercel.app/download
- **iOS:** [App Store](https://apps.apple.com/app/id6503033841)
- **Release announcements:** [t.me/planb_app](https://t.me/planb_app)

## Installing

1. Download the APK. Your browser will warn you about the file type — that
   warning is about the source, not the file.
2. Open it. Android asks once for permission to install apps from that browser.
3. Updating works the same way: a new APK installs straight over the old one
   and keeps your settings.

Every build is signed with the same key, so updates install in place. Each
release lists a SHA-256 checksum you can verify before installing.

PlanB is not published on Google Play.

## What is in a release

| Asset | What it is |
|---|---|
| `PlanB-android.apk` | The build. The filename is the same in every release, so `/releases/latest/download/PlanB-android.apk` always resolves to the newest one. |
| `latest.json` | Version, build number, size, checksum and release notes for this build. The app reads it to offer an update. |
| `releases.json` | The same, for every release so far. The download page renders its history from this. |

## Not affiliated with Formula 1

PlanB is an independent project. It is not associated with, endorsed by, or
affiliated with Formula 1, the FIA, or any team or driver. All trademarks
belong to their respective owners.
