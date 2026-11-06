# Install Total Rush

Download **[Total Rush 0.2.1](https://github.com/YooTommy-CH/total-rush/releases/tag/v0.2.1)**.

## macOS Apple Silicon

1. Download and open `TotalRush-0.2.1-macOS-arm64.dmg`.
2. In the custom installer window, drag **Total Rush** to **Applications**. Eject the disk after copying.
3. Open **Total Rush.app** from Applications.

The app is native ARM64, uses Metal, and is Developer ID signed and Apple notarized. Rosetta is not required. The macOS ZIP remains available as an alternative and for automatic updates.

## Windows 10/11 x64

1. Download `TotalRush-Windows-x64.zip` and extract it into a dedicated folder.
2. Keep the executable, data folder and libraries together.
3. Open `Total Rush.exe` inside the `Total Rush` folder.

The build uses Direct3D 11 and targets x64. Automated tests on Windows Server 2022 verify native startup and simulation. Graphics and physical controllers on Windows 10/11 still need PC testing.

## Language

The game starts in **English** by default. Choose **Settings → Interface → Language** to select English or Italian, then **Apply and save**. Back discards pending settings changes; restoring defaults selects English again.

## Update from the game

If you are upgrading from **0.1.0**, install the current version manually once: the older packages had different names.

From 0.1.1 onward, the game checks for the latest stable release at startup. Select **Update now**, wait for verification, and let the game close and reopen. **Updates** in the main menu also lets you check manually.

The previous installation is kept for recovery. Rush career saves remain separate from the earlier simulation's saves. Your personal soundtrack library is not replaced.

## Personal soundtrack

No music is bundled. On the **Soundtrack** page, select one folder containing your MP3 files and a separate folder containing PNG/JPG/JPEG artwork. Names must match exactly, excluding the extension. If they differ, choose the track's **Artwork** button and assign an image from the gallery. Manual assignments are saved.

The library works offline and crossfades between tracks. **Rescan** detects changes. Disconnecting does not delete your original files.
