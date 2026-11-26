# Changelog

Release downloads are available on the [Releases page](https://github.com/AlexRacing98/LocalConvert/releases).

## Windows 1.9.8 — November 26, 2026

- Added offline English and Simplified Chinese privacy policies, explicit Agree/Reject choices, and Withdraw agreement in Settings.
- Added AVIF, JPEG XL and HEIC/HEIF input support, including 10-bit inputs, across image tools, Images to PDF and QR image scanning. No codec download is required.
- Added background image checks and clearer messages for damaged or oversized files. Mixed batches retain valid images, and failed replacements keep the previous selection.
- Image exports remain standard 8-bit color. Existing PDF compression and large-image protections are retained.

[Download Windows 1.9.8](https://github.com/AlexRacing98/LocalConvert/releases/tag/windows-v1.9.8)

## Android 1.9.8 — November 23, 2026

- Added explicit Agree and Reject privacy choices, with English and Simplified Chinese policies available offline.
- Added Withdraw agreement in Settings and renewed agreement for the revised policy.
- Updated developer information in both policy languages.
- Published the AppGallery-signed APK. Older GitHub builds use a different signing key; see the [updating instructions](docs/INSTALLATION.md#updating-android).

[Download Android 1.9.8](https://github.com/AlexRacing98/LocalConvert/releases/tag/android-v1.9.8)

## Android 1.9.6 — November 14, 2026

- Added offline TIFF, AVIF, JPEG XL, HEIC and HEIF input support across Images to PDF, every image conversion/editing tool, previews and QR image scanning, including 10-bit AVIF/HEIC/HEIF files.
- Expanded file selection and added an optional folder route for image conversion/editing tools when system pickers hide uncommon formats.
- Added memory safeguards and corrupt-file checks; a failed replacement keeps the previous valid image in single-image tools.
- Includes earlier Android fixes for large TIFF imports and unusually wide or tall PDF page exports.
- Image exports remain standard 8-bit PNG/JPEG/WebP. HEIC/HEIF software decoding requires ARM. Modern inputs have 32 MiB / 16 MP limits, sampled to at most 6 MP.
- No new permissions, network access or Google Play dependency.

[Download Android 1.9.6](https://github.com/AlexRacing98/LocalConvert/releases/tag/android-v1.9.6)

## Windows 1.9.3 — November 5, 2026

- Added Explorer file drops to Images to PDF and checks that reject oversized images before decoding.
- Limited memory use for large image batches and very wide or tall PDF page renders. PDF compression skips oversized embedded images and transparency masks.
- Cleared stale crop and watermark previews when a replacement fails to load.

[Download Windows 1.9.3](https://github.com/AlexRacing98/LocalConvert/releases/tag/windows-v1.9.3)

## Windows 1.9.2 — November 4, 2026

- Fixed PDF compression skipping transparent images, including photo PDFs created by LocalConvert; added CMYK/palette image handling.
- Preserved selectable text and image transparency, and optimized shared images only once.
- Added original/output byte counts, percentage saved, and optimized-image counts. Outputs less than 1% smaller are rejected with guidance.
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

[Download Windows 1.9.1](https://github.com/AlexRacing98/LocalConvert/releases/tag/windows-v1.9.1)

### Android

- Version 1.9.1 includes the **AlexRacing98 All Rights Reserved** notice.
- The existing 45-tool toolkit, personalized welcome message, themes, saved-output history, and adaptive recommendations remain available.
- No Google Play Services required.

[Download Android 1.9.1](https://github.com/AlexRacing98/LocalConvert/releases/tag/Official_Release)

## Repository presentation

- Added platform download links, interface previews, installation instructions, tool documentation, privacy notes, support information, and issue forms.
- Application binaries are distributed as release assets; this repository does not publish the application source.
