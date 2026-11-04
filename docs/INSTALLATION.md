# Install LocalConvert

Download official builds from [AlexRacing98/LocalConvert Releases](https://github.com/AlexRacing98/LocalConvert/releases).

## Android

**Requires Android 8.0 or newer.** Google Play Services are not required.

1. Download [LocalConvert-1.9.1.apk](https://github.com/AlexRacing98/LocalConvert/releases/download/Official_Release/LocalConvert-1.9.1.apk) on your Android device.
2. Open the downloaded APK and follow Android’s installation prompts.
3. Open **LocalConvert**, then choose a tool from Home or Tools.

The app works locally. Camera access is used for QR scanning; files and images are selected through the device’s pickers. You do not need a LocalConvert account.

## Windows

**Requires 64-bit Windows 10 version 1809 or newer, or Windows 11.**

1. Download [LocalConvert-Windows-1.9.2-portable.zip](https://github.com/AlexRacing98/LocalConvert/releases/download/windows-v1.9.2/LocalConvert-Windows-1.9.2-portable.zip).
2. Extract the **entire ZIP** to a normal folder.
3. Open the extracted **LocalConvert** folder.
4. Run **LocalConvert.exe**.

Keep the `_internal` folder beside the executable. Do not move only the EXE or try to run it inside the ZIP. The included runtime means no separate Python or Microsoft Office installation is needed. This build has no Windows publisher signature.

### Updating Windows

Close the running app, extract the newer download into its own folder, and run its **LocalConvert.exe**. Preferences and results are stored separately under `%LOCALAPPDATA%\LocalConvert`.

### Saving results

Choose **Save a copy** after a conversion to export the result to a location you select. Recent results appear in History. Removing a history entry does not delete its file.

### Common Windows questions

| Problem | What to check |
| :-- | :-- |
| Missing DLL or runtime files | Extract the full ZIP again. Keep `_internal` with the EXE. |
| A tool’s action button is lower down | Scroll within the main content area; longer forms include previews and output options. |
| No camera image | Check that a webcam is connected and available to desktop apps. Start with camera number 0, then try another number. Hardware compatibility is not yet fully tested. |
| The bug-report button does not open email | Configure a default email app, or email the address in [Support](../SUPPORT.md). |
| Currency rates are old | Import a newer daily ECB-format XML file or enter a manual rate. Rates are not fetched automatically. |

## Verify a download

These SHA-256 checksums identify the current published files. Compare the downloaded file’s checksum with the value below if you want to verify it.

| File | SHA-256 |
| :-- | :-- |
| `LocalConvert-1.9.1.apk` | `d7fd63907d8e56808e7b0c868348e6fc0c1656fdaefd424b8ff3f60ebcb8916f` |
| `LocalConvert-Windows-1.9.2-portable.zip` | `40bffbd18581384a37997cdf7426dd19efdfaf8c0f61a604b7776145a8af1ce3` |

Need more help? See [Support](../SUPPORT.md).
