<p align="center">
  <img src="assets/cover.png" alt="QuickView: press Space to preview anything on Windows" width="100%">
</p>

<p align="center">
  <a href="https://github.com/abdullah-al-faahim/QuickView-Windows/releases/latest/download/QuickView.exe">
    <img src="assets/download-button.svg" alt="Download QuickView for Windows" width="340">
  </a>
</p>

<p align="center">
  <a href="https://abdullah-al-faahim.github.io/QuickView-Windows/"><b>Website</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/abdullah-al-faahim/QuickView-Windows/releases"><b>All releases</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/abdullah-al-faahim/QuickView-Windows/issues"><b>Report an issue</b></a>
  <br><br>
  <img alt="Latest release" src="https://img.shields.io/github/v/release/abdullah-al-faahim/QuickView-Windows?style=flat-square&color=2563eb">
  <img alt="Downloads" src="https://img.shields.io/github/downloads/abdullah-al-faahim/QuickView-Windows/total?style=flat-square&color=7c3aed">
  <img alt="Windows 10 and 11" src="https://img.shields.io/badge/Windows-10%20%7C%2011-0ea5e9?style=flat-square">
  <img alt="Size 83 KB" src="https://img.shields.io/badge/size-62%20KB-16a34a?style=flat-square">
</p>

---

**QuickView** brings Space-to-preview to Windows. Select any file in File Explorer or on the desktop, tap **Space**, and the preview appears in about 75 ms. Tap Space again to close it.

- ⚡ **Fast and tiny.** One 83 KB file with no runtime and no frameworks. It uses under 2 MB of RAM and 0% CPU while waiting.
- 🎨 **Built for designers.** Previews PSD, PSB, AI, EPS, INDD, SVG, Sketch, Adobe XD, Figma, Krita and Procreate files, no Adobe apps required.
- 📄 **Every document.** Sharp, zoomable PDF pages built in. Word, Excel, PowerPoint, Visio, Outlook mail and HTML through Windows' preview handlers, or rendered as high-resolution pages via your installed Office or LibreOffice.
- 🎬 **Video & music.** New in 1.1: MP4, MOV, MKV, WEBM, AVI, WMV, MP3, FLAC, WAV and more play right in the preview, with a seek bar.
- 🖼️ **Photos done right.** JPG, PNG, WEBP, HEIC, AVIF, TIFF and camera RAW, rendered on the GPU with zoom, pan and EXIF rotation.
- ⌨️ **Keyboard first.** <kbd>←</kbd> <kbd>→</kbd> to browse the folder, <kbd>Enter</kbd> to open, <kbd>Space</kbd> or <kbd>Esc</kbd> to close.

## Install

**Option A: just run it**

1. Download **[QuickView.exe](https://github.com/abdullah-al-faahim/QuickView-Windows/releases/latest/download/QuickView.exe)** and run it. It lives in the system tray.
2. Right-click the tray icon and tick **Start with Windows**.

**Option B: installer ZIP** (installs per user and adds QuickView to *Open with*)

1. Download **[QuickView-1.1.3-win64.zip](https://github.com/abdullah-al-faahim/QuickView-Windows/releases/latest/download/QuickView-1.1.3-win64.zip)** and extract it.
2. Right-click `install.ps1` → **Run with PowerShell**. No admin rights needed.

> [!NOTE]
> QuickView isn't code-signed yet, so Windows SmartScreen may say *"Windows protected your PC"*. Click **More info → Run anyway**. The app makes no network connections and needs no admin rights.

## Supported formats

| Category | Formats |
|---|---|
| **Documents** | PDF (built-in page renderer), DOC/DOCX, XLS/XLSX, PPT/PPTX, RTF, VSDX, MSG, EML, HTML, ODT/ODS/ODP. Office files use Office's preview; if that fails they're converted with installed Office or LibreOffice into high-resolution pages. With neither installed, the text is shown. |
| **Video & audio** | MP4, MOV, M4V, MKV, WEBM, AVI, WMV, MPG, TS/M2TS, 3GP, MP3, WAV, FLAC, AAC/M4A, WMA, OGG, OPUS. Formats without a Windows codec (FLV, RM…) show a frame thumbnail. |
| **Design** | PSD, PSB, AI, AIT, EPS, INDD, SVG, SVGZ, Sketch, XD, Figma (.fig), Krita, OpenRaster, Procreate, 3MF |
| **Images** | JPG, PNG, GIF, BMP, TIFF, ICO, WEBP, HEIC/HEIF, AVIF, JXR, DDS, RAW (CR2, NEF, ARW, DNG…) |
| **Text & code** | TXT, MD, JSON, XML, CSV, LOG, YAML, INI and 100+ source-code extensions |
| **Everything else** | Archives show their contents, and any other file gets a high-resolution thumbnail or an info card |

## Keyboard & mouse

| Input | Action |
|---|---|
| <kbd>Space</kbd> | Open / close preview |
| <kbd>←</kbd> <kbd>→</kbd> | Previous / next file (Explorer's selection follows) |
| <kbd>Enter</kbd> | Open in the default app |
| <kbd>Esc</kbd> | Close |
| Mouse wheel · drag · double-click | Zoom · pan · reset (images and SVG) |

## Requirements

Windows 10 version 1703 or later, or Windows 11, 64-bit.

## Uninstall

Untick **Start with Windows** in the tray menu, choose **Exit**, and delete `QuickView.exe`. If you used the ZIP, run `uninstall.ps1` instead.

---

<p align="center"><sub>This repository hosts QuickView's releases and website. Found a bug or a format that doesn't preview? <a href="https://github.com/abdullah-al-faahim/QuickView-Windows/issues">Open an issue</a>.</sub></p>
