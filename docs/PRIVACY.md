# Privacy and local processing

## Files stay on your device

LocalConvert performs its conversion and analysis work on the device running the app. It does not upload files to a conversion server and does not require a LocalConvert account. The Android application does not request the Android internet permission. The Windows application does not include a conversion-service client, analytics, or an automatic update service.

## Preferences and recommendations

Your name, theme, and recommendations are stored locally. Recommendations use the most recent 128 opened tool IDs on that device. File contents, passwords, and QR contents are not part of that recommendation log. **Reset recommendations** starts the recommendations fresh without clearing your name, theme, or file history.

## Results and history

LocalConvert keeps recent result information so you can find your conversions again. On Windows, preferences, imported currency XML, and generated results are stored under `%LOCALAPPDATA%\LocalConvert`; Settings can open that folder. History lists up to 50 entries. Removing an entry does not delete its file, and old generated files are not automatically removed.

Exported or shared copies are managed by the destination you choose. A cloud-backed folder or a sharing destination can sync or upload files according to that service’s settings; that is separate from LocalConvert’s processing.

## Camera, QR codes, and clipboard

Camera access is used for QR scanning when you choose that feature. QR contents are displayed as text; links are not opened automatically. Windows camera frames are processed locally and are not saved by the scanner.

On Windows, generated passwords are not written to result files or history. If you copy one, LocalConvert clears the clipboard after two minutes when it still contains that same value. Other clipboard contents are under the control of Windows and any clipboard tools you use.

## External applications

**Report a bug** opens an email draft in your default mail app. You decide whether to send it and what to include. Sending email, opening a file in another app, opening a browser, and obtaining updated currency XML files use those external applications and their own settings.

## What these tools do—and do not do

- **Remove metadata** re-encodes the image without copying personal EXIF/GPS/XMP information. It does not remove information visibly present in the picture. Output dimensions and other technical format fields can remain.
- **Base64** changes the representation of bytes; it is not encryption.
- **SHA-256 and MD5** calculate checksums. MD5 is a legacy checksum and is not appropriate for password storage or security verification.
- **File operations** can create, copy, rename, or move files you select. Batch rename, sorting, and extraction use previews. They are not a backup system; completed changes remain if an operation is interrupted.

Please do not post personal documents, passwords, QR contents, location metadata, or private file paths in public GitHub issues. Use [Support](../SUPPORT.md) for private contact information.
