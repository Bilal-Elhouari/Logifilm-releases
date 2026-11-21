# Logifilm — Downloads

Crew, contracts and payroll management for film productions.

This repository only hosts the **Logifilm installers and update files**. It contains no source code.

## Download

Open the [latest release](https://github.com/Bilal-Elhouari/Logifilm-releases/releases/latest) and download:

| System | File |
|---|---|
| **Windows** | `Logifilm.Setup.x.y.z.exe` |
| **macOS** (Apple Silicon: M1 and later) | `Logifilm-x.y.z-arm64.dmg` |

The other files (`latest.yml`, `latest-mac.yml`, `.zip`, `.blockmap`) are used by the app's automatic updates — you don't need to download them.

## Install

### Windows
1. Run the downloaded `.exe` file.
2. Follow the installer.

### macOS
1. Open the `.dmg` file.
2. Drag **Logifilm** into **Applications**.
3. On first launch, if macOS says *"Logifilm is damaged and can't be opened"*, open **Terminal** and run:

   ```bash
   xattr -cr /Applications/Logifilm.app
   ```

   The app is not damaged: it is simply not signed with an Apple certificate.

## Updates

Logifilm checks for updates automatically. Use the **Updates** button at the bottom right of the app to check, download and install a new version.

A licence key is required to use Logifilm.

© Logifilm — All rights reserved.
