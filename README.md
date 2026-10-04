# How to Install WhatMates on Mac

WhatMates is distributed as a ZIP file (`WhatMates-1.0.52-arm64.zip`) that contains a DMG installer (`WhatMates-1.0.52-arm64.dmg`). A DMG (Disk Image) acts like a virtual disk that holds the app.

> The `arm64` in the file name means this build is for Macs with Apple silicon (M1, M2, M3, M4 and later). To check your Mac, click the Apple menu → **About This Mac** and look for "Chip".

## Steps

1. **Unzip the download**
   Find `WhatMates-1.0.52-arm64.zip` in your **Downloads** folder and double-click it. macOS extracts it, producing `WhatMates-1.0.52-arm64.dmg` in the same folder.

2. **Open the DMG**
   Double-click `WhatMates-1.0.52-arm64.dmg`. macOS verifies it and mounts it as a virtual disk. A Finder window opens, and the disk also appears in the Finder sidebar.

3. **Install the app**
   Drag the **WhatMates** icon onto the **Applications** folder in the window.

4. **Eject the disk image**
   Once copying finishes, eject the DMG:
   - Click the **eject icon** next to the WhatMates disk in the Finder sidebar, or
   - Right-click the disk and choose **Eject**.

5. **Clean up (optional)**
   Move the `.zip` and `.dmg` files to the Trash to save space.

6. **Launch WhatMates**
   Open **Launchpad**, or go to **Applications** in Finder and double-click **WhatMates**.

## First Launch: Security Prompts

The first time you open an app downloaded from the internet, macOS may show a warning.

- **"WhatMates is an app downloaded from the internet. Are you sure you want to open it?"** Click **Open**.
- **"WhatMates can't be opened because it is from an unidentified developer"** (or cannot be verified):
  1. Click **Done** or **Cancel** on the warning.
  2. Open **System Settings → Privacy & Security**.
  3. Scroll down to the Security section and click **Open Anyway** next to WhatMates.
  4. Enter your password if prompted, then click **Open**.

> Only bypass these warnings for software you trust and downloaded from the official source.

## Troubleshooting

| Problem | Solution |
|---|---|
| ZIP won't extract | Re-download the file; it may be incomplete. |
| DMG won't open | Re-download the ZIP and extract it again. |
| "Damaged and can't be opened" | Re-download from the official source and make sure the download finished. |
| App won't run / wrong architecture | The `arm64` build only runs on Apple silicon Macs. Intel Macs need an `x64` or Intel build. |
| Can't drag app to Applications | You may need admin rights. Authenticate when prompted, or use an admin account. |
| App won't open after install | Check **System Settings → Privacy & Security** for a blocked-app notice. |
| Disk won't eject ("in use") | Quit any app using the disk, then try again. |

## Uninstalling WhatMates

1. Open **Applications** in Finder.
2. Drag **WhatMates** to the **Trash** (or right-click → **Move to Trash**).
3. Empty the Trash.

Some apps leave support files in `~/Library/Application Support/` and `~/Library/Preferences/`. You can remove these manually for a complete cleanup.
