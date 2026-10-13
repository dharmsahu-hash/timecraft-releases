# TimeCraft by [KnowledgeWala](https://knowledgewala.com/?utm_source=timecraft&utm_medium=github&utm_campaign=cross_promo)

**Free time & focus tracker for Windows, Mac, Linux and Android.** Click a topic to start a timer, set hour goals, and see in plain words where your time really goes. Everything stays in one file on your computer: no account, no tracking, no ads.

## Download and install

Open **[Releases → latest](../../releases/latest)** and pick your file under **Assets**.

| Your computer | File | Steps |
|---|---|---|
| **Windows** 10 / 11 (recommended) | `TimeCraft_<version>_windows_x64-setup.exe` | 1. Download. 2. Double-click. 3. If Windows says "protected your PC": **More info → Run anyway**. 4. **Next → Install → Finish**. No admin password. Adds a Start-menu entry and can add a desktop shortcut. |
| Windows, no install | `TimeCraft_<version>_windows_x64.exe` | Double-click to run from anywhere (a USB stick, a folder). |
| **Mac**, M1/M2/M3/M4 | `TimeCraft_<version>_macos_apple-silicon.zip` | 1. Download and double-click the zip. 2. Drag **TimeCraft** to Applications. 3. First time only: **right-click → Open → Open**. |
| **Mac**, Intel | `TimeCraft_<version>_macos_intel.zip` | Same as above. |
| **Linux** 64-bit (Ubuntu 22.04+ or similar) | `TimeCraft_<version>_linux_x64.tar.gz` | 1. Download. 2. Run `tar xzf TimeCraft_*_linux_x64.tar.gz`. 3. Run `./TimeCraft` (or double-click it). |

No admin password and no Python needed. Uninstalling (Windows **Settings → Apps**) never deletes your data. (Not sure which Mac? Apple menu → **About This Mac**: "Chip: Apple" = Apple silicon.)

## Android

Open **[TimeCraft for Android 1.2.2](../../releases/tag/android-v1.2.2)** and download `TimeCraft_1.2.2_android.apk` under **Assets**. It needs Android 8.0 or newer. (The **Releases → latest** link above goes to the computer versions; Android has its own release.)

1. Download the file on your phone and open it.
2. If Android asks, allow your browser (or Files app) to **install unknown apps**, then go back and tap **Install**. If Play Protect warns that the app is not from the Play Store, choose **More details → Install anyway**. TimeCraft is not on the Play Store.
3. Open **TimeCraft**.

**Update (your data is safe):** download the newer `.apk` and install it over the old one. Android keeps your data; before a new version changes the data file it also saves a safety copy next to it. Do not uninstall first: uninstalling deletes the data on the phone. Before any big change, use **Settings → Your data & usage → Back up now**.

**Bring your computer data to the phone:** on the computer use **Your data & usage → Back up now**, copy the `.db` file to the phone, then **Settings → Import from desktop** in the app. Do this once; importing the same file again adds the sessions twice.

To be told about new versions, open **Settings → About TimeCraft** and switch on **Check for updates once a day**. It only asks this page which Android version is newest, sends nothing about you and never installs anything; **Download** just opens this page. Off by default.
## What you get

- One-click timers per topic, with pause and resume, and recovery if your computer shuts down mid-session
- Daily goal and streak, plus targets for any topic and date range, with honest pace advice
- Reports and a day-by-day breakdown, exportable to CSV
- A **Thought for today** (quote and tip), written insights that work offline, and optional AI insights with your own free key

## Update (your data is safe)

Download the newest file and replace the old one. Your data lives in your user folder, not in the app, so nothing is lost; before a new version changes your data file it also saves a safety copy next to it (`timecraft.db.bak-…`).

To be told about new versions, open **About & support** and tick **Check for updates once a day**. It only asks this page which version is newest, sends nothing about you, and never installs anything by itself: **Download** just opens this page. Off by default.

| Where your data is | |
|---|---|
| Windows | `%APPDATA%\TimeCraft\timecraft.db` |
| Mac | `~/Library/Application Support/TimeCraft/timecraft.db` |
| Linux | `~/.local/share/TimeCraft/timecraft.db` |
| Android | Private to the app on the phone. Use **Your data & usage → Back up now** to copy it out. |

Back up or move to another computer by copying that one file, or use **Your data & usage → Back up now**. That screen also shows what is stored, lets you export every session to CSV, and copy a short summary to share with a friend.

## Tell us what you think

- **[Share feedback](../../issues/new?template=feedback.yml)** · **[Suggest a feature](../../issues/new?template=feature-request.yml)** · **[See other people's ideas](../../issues)** (a free GitHub account is needed; please don't include personal information, these pages are public)
- Email: [dknitk@gmail.com](mailto:dknitk@gmail.com?subject=TimeCraft)

## Support TimeCraft

TimeCraft is free and always will be. If it helps you, **About & support** in the app has a QR code to scan with PhonePe or any UPI app. Entirely optional.

## More from KnowledgeWala

- **[KnowledgeWala](https://knowledgewala.com/?utm_source=timecraft&utm_medium=github&utm_campaign=cross_promo)**: learning resources and free tools
- **[TeacherCircle](https://teacherscircle.co.in/?utm_source=timecraft&utm_medium=github&utm_campaign=cross_promo)**: find a teacher near you in India
- **[PCDoctor](https://github.com/dharmsahu-hash/pcdoctor-releases)**: plain-words PC health for Windows

This repository holds downloads and release notes only. © 2026 [KnowledgeWala](https://knowledgewala.com/?utm_source=timecraft&utm_medium=github&utm_campaign=cross_promo). Free to use for personal, educational or professional use.
