# All 45 tools

Choose a category in the app or search by tool name on Windows. Processing happens locally. The tools support specific formats and workflows; LocalConvert is not a universal converter for every file type.

## PDF Tools · 7 tools

| Tool | What it does |
| :-- | :-- |
| **Images to PDF** | Combine photos into one document. |
| **PDF to images** | Export pages as images in a ZIP. |
| **Merge PDFs** | Combine PDFs in your chosen order. |
| **Split PDF** | Save every page as a separate PDF. |
| **Compress PDF** | Reduce embedded image file sizes. |
| **Rotate PDF** | Turn all pages or selected pages. |
| **Extract pages** | Save chosen pages in a new PDF. |

## Image Tools · 10 tools

| Tool | What it does |
| :-- | :-- |
| **Image converter** | PNG, JPEG or WebP. |
| **PNG to JPG** | Convert PNG pixels to JPEG. |
| **JPG to PNG** | Make a lossless PNG copy. |
| **WebP to PNG** | Convert WebP to a PNG image. |
| **PNG to WebP** | Create a compact WebP image. |
| **Resize image** | Set exact output dimensions. |
| **Crop image** | Drag the crop area or choose a ratio. |
| **Compress image** | Control JPEG or WebP quality. |
| **Remove metadata** | Remove EXIF, GPS and XMP details. |
| **Watermark image** | Add your own text watermark. |

## File Tools · 6 tools

| Tool | What it does |
| :-- | :-- |
| **Rename files** | Rename a folder’s files in one batch. |
| **Duplicate file finder** | Find identical file contents. |
| **Storage analyzer** | See what takes up space in a folder. |
| **Zip files** | Pack selected files into an archive. |
| **Unzip files** | Extract an archive into a new folder. |
| **Sort files by type** | Organize files into category folders. |

## Text Tools · 9 tools

| Tool | What it does |
| :-- | :-- |
| **Text to PDF** | Turn notes into a clean PDF. |
| **Text to DOCX** | Create an editable Word document. |
| **Word counter** | Live word and line totals. |
| **Character counter** | Count characters with or without spaces. |
| **Case converter** | Uppercase, lowercase and more. |
| **Remove duplicate lines** | Keep the first occurrence of each line. |
| **Sort lines** | Arrange lines in ascending or descending order. |
| **JSON formatter** | Pretty-print or minify JSON. |
| **JSON validator** | Find syntax errors with line and column. |

## Privacy & Security · 7 tools

| Tool | What it does |
| :-- | :-- |
| **Password generator** | Create a strong random password. |
| **QR code generator** | Create an offline QR code from text. |
| **QR code scanner** | Read QR codes from camera or images. |
| **Base64 encoder** | Encode text or file bytes as Base64. |
| **Base64 decoder** | Decode Base64 to text or exact bytes. |
| **SHA-256 generator** | Hash text or a file locally. |
| **MD5 generator** | Create an MD5 compatibility checksum. |

## Converters · 6 tools

| Tool | What it does |
| :-- | :-- |
| **Unit converter** | Everyday measurements in one place. |
| **Temperature converter** | Celsius, Fahrenheit, Kelvin and Rankine. |
| **Length converter** | Metric, Imperial and nautical distances. |
| **Weight converter** | Grams, kilograms, pounds and more. |
| **Speed converter** | Compare road, running and nautical speeds. |
| **Currency converter** | Convert with dated, saved exchange rates. |

## Useful details before you start

### PDFs and documents

Images to PDF combines selected images in order, with fit-image, A4, or Letter sizing. PDF to images and Split PDF package their multiple outputs in a ZIP. Page selections use numbers and ranges such as `1,3-5`; Rotate PDF can target selected pages. Compression is not guaranteed to shrink an already compact file, and a larger output is rejected.

PDF editing can affect signatures, forms, and document-level information. Use a copy of an important original and check the result. Password-protected PDFs must be unlocked elsewhere first. Text to DOCX creates an editable document; text to PDF depends on the platform’s available fonts for character coverage.

### Images

Supported conversion formats include PNG, JPEG, and WebP. JPEG replaces transparency with white; converting a JPEG to PNG does not restore detail already lost. Large sources are sampled before editing, and animated images use their first frame. Crop and watermark tools provide previews.

Remove metadata re-encodes the visible image without copying personal EXIF/GPS/XMP data. It does not redact visible information. Technical fields, such as dimensions, may remain. Lossy JPEG/WebP settings can change image quality.

### Files

Choose a folder for rename, duplicate finding, storage analysis, or sorting. Duplicate finding compares file contents using SHA-256 and does not delete duplicates. Storage analysis describes the selected folder; it is not a whole-drive cleanup service.

Batch rename, sorting, and ZIP extraction show a preview before applying changes. Sorting supports copying or moving. Existing destinations and unsafe archive paths are blocked. Completed changes can remain after cancellation or a failure; there is no automatic batch undo.

### Text, passwords, and QR codes

Word and character counting have different rules: the character counter counts Unicode code points, so a combined accent or emoji sequence can contain multiple characters. JSON tools reject duplicate keys and invalid values while preserving number spelling. Line tools can ignore case, trim lines, and remove empty lines.

Passwords are generated using secure randomness. QR codes can be created from text and read from an image or camera; the decoded content is displayed without automatically opening links. Physical webcam testing of the Windows scanner is pending.

Base64 is an encoding, not encryption. The decoder supports text and binary output. SHA-256 and MD5 calculate checksums; MD5 is a legacy option and is not suitable for password storage or security verification.

### Units and currencies

The general Unit Converter covers **length, weight/mass, speed, temperature, area, volume, time, data size, pressure, and energy**. Dedicated converters provide shortcuts for common categories. Temperature conversion rejects values below absolute zero.

Currency conversion uses a bundled **ECB-format snapshot dated October 30, 2026**, with 30 currencies including EUR. The source and date are shown. Import a newer daily XML snapshot or supply a manual rate and date; rates are not fetched automatically. Estimates exclude fees and provider spreads.

## Current Windows limits

| Input or operation | Limit |
| :-- | :-- |
| Image source | 256 MB compressed / up to 100 megapixels; edited output sampled to about 12 megapixels |
| Image dimensions | Up to 12,000 pixels per output edge, within the pixel limit |
| PDF input | 512 MB / up to 2,000 pages |
| PDF merge | Up to 100 PDFs / 512 MB combined / 2,000 output pages |
| PDF split | Up to 500 pages |
| Images to PDF | Up to 100 images |
| Text | 500,000 UTF-16 units; UTF-8 file import up to 2 MB |
| Folder scans | 20,000 files / 25,000 entries; links and junctions skipped |
| Batch rename/sort | Up to 500 top-level files |
| ZIP creation | Up to 100 files / 1 GB combined |
| ZIP extraction | 10,000 entries / 512 MB per file / 1 GB expanded; unsafe paths, links, and conflicting names rejected |
| Base64 file encoding | Up to 8 MB |
| Exchange-rate XML | 256 KB; daily UTF-8 ECB format |

Android limits and available options are described inside its tool screens. Keep the app open while processing; cancellation takes effect at a safe checkpoint.

[Back to LocalConvert](../README.md) · [Installation](INSTALLATION.md) · [Support](../SUPPORT.md)
