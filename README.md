# MySheets — Batch export for Autodesk Revit

**Every sheet. Every format. One run.**

MySheets is a Revit add-in that batch-exports the sheets and views you select to **PDF, DWG, DXF, DWF, DGN, IFC, NWC and gbXML** — in a single run, with one naming rule and a review of exactly what will be written before anything leaves Revit.

![MySheets — batch export for Autodesk Revit](https://mysheets.pages.dev/assets/og.png)

## The problem it solves

Issuing a set usually means opening sheet after sheet, exporting each one, renaming by hand, and keeping track of what you already did. It's repetitive, easy to get wrong, and it's the part of the week nobody bills for. MySheets turns that into one deliberate run.

## Highlights

| Feature | What it does |
| --- | --- |
| **8 formats from one selection** | The same chosen sheets and views are written in every format you tick, in the same run. |
| **One naming rule** | Compose file names from sheet number, sheet name, revision, discipline, scale, date or any Revit parameter — invalid filename characters are sanitized; every file follows the same rule. |
| **Review before writing** | Item count, included formats and output folder are shown before a single file is created — missing requirements are reported up front. |
| **Safe by default** | Existing files are skipped and reported, never silently overwritten. |
| **External images in DWG** | Optional image binding embeds referenced images into exported DWGs (uses your installed AutoCAD; ordinary DWG export needs nothing extra). |
| **Light and dark themes** | A quiet interface designed to sit beside Revit all day. |

## Requirements

- 64-bit Windows 10 or 11
- Autodesk Revit **2020–2027** — one unified installer detects installed versions and places a matching build into each
- Administrator rights for installation (machine-wide)
- AutoCAD 2020–2027 only for the external image binding step

## Install

1. Close Revit.
2. Run `MySheets-Setup-1.0.0.exe` as administrator. The build is not code-signed: Windows SmartScreen may ask you to confirm via **More info → Run anyway**, and Revit will show its unsigned add-in notice once.
3. Open Revit — **MySheets** appears on its own ribbon tab.
4. The first launch starts a **7-day trial**. Activation is offline and machine-bound — no account, no always-on connection.

## Get the installer

- **GitHub Releases:** download `MySheets-Setup-1.0.0.zip` from <https://github.com/mostafayossrii/MySheets/releases>
- **Website:** <https://mysheets.pages.dev/> — or a LinkedIn message to [Mostafa Yossri](https://www.linkedin.com/in/mostafayossri/)

## License

MySheets is proprietary software. Copyright © 2026 Mostafa Yossri. All rights reserved. This repository hosts product information and distribution pointers only; no source code is published here and no license to the software is granted by its publication.

Autodesk and Revit are trademarks of Autodesk, Inc. MySheets is not affiliated with or endorsed by Autodesk.
