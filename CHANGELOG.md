# Changelog

Release downloads are available on the [Releases page](https://github.com/AlexRacing98/LocalConvert/releases).

## Windows 1.9.3 — November 5, 2026

- Added Explorer file drops to Images to PDF and checks that reject oversized images before decoding.
- Limited memory use for large image batches and very wide or tall PDF page renders. PDF compression skips oversized embedded images and transparency masks.
- Cleared stale crop and watermark previews when a replacement fails to load.
- All 27 packaged engine tests passed and all 45 tool screens opened.

[Download Windows 1.9.3](https://github.com/AlexRacing98/LocalConvert/releases/tag/windows-v1.9.3)

## Windows 1.9.2 — November 4, 2026

- Fixed PDF compression skipping transparent images, including photo PDFs created by LocalConvert; added CMYK/palette image handling.
- Preserved selectable text and image transparency, and optimized shared images only once.
- Added original/output byte counts, percentage saved, and optimized-image counts. Outputs less than 1% smaller are rejected with guidance.
- Verified a transparent-photo PDF reducing from 4,053,499 to 355,120 bytes (91.2%) at quality 40; savings vary by file and setting.
- All 22 packaged engine tests and all 45 packaged UI forms passed; 293 source UI assertions passed.
- Windows-only update. Android remains at 1.9.1.

[Download Windows 1.9.2](https://github.com/AlexRacing98/LocalConvert/releases/tag/windows-v1.9.2)

## 1.9.1 — November 1, 2026

### Windows

- First public portable Windows release, with the 45-tool catalog.
- Desktop sidebar, welcome page, tool search, history, and settings.
- Optional name, dark/light themes, and adaptive recommendations with a reset option.
- PDF, image, DOCX, file/ZIP, text/JSON, QR, password, Base64, checksum, and converter tools.
- Interactive crop selection, watermark previews, and previews before batch file changes.
- Lighter action-button backgrounds in light mode for clearer icon contrast.
- All 18 packaged functional tests passed; all 45 tool forms checked. Physical webcam testing is pending.

[Download Windows 1.9.1](https://github.com/AlexRacing98/LocalConvert/releases/tag/windows-v1.9.1)

### Android

- Version 1.9.1 includes the **AlexRacing98 All Rights Reserved** notice.
- The existing 45-tool toolkit, personalized welcome message, themes, saved-output history, and adaptive recommendations remain available.
- No Google Play Services required.

[Download Android 1.9.1](https://github.com/AlexRacing98/LocalConvert/releases/tag/Official_Release)

## Repository presentation

- Added platform download links, interface previews, installation instructions, tool documentation, privacy notes, support information, and issue forms.
- Application binaries are distributed as release assets; this repository does not publish the application source.
