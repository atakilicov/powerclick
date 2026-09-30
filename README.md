<p align="center">
  <img src="assets/icon.png" width="96" height="96" alt="PowerClick app icon">
</p>

<h1 align="center">PowerClick</h1>

<p align="center">
  The right-click menu Finder should have had. New File, Copy Path, Cut & Move, Batch Rename.
</p>

<p align="center">
  <a href="#requirements"><img src="https://img.shields.io/badge/macOS-13%2B-000000?logo=apple&logoColor=white" alt="macOS 13 or later"></a>
  <a href="#languages"><img src="https://img.shields.io/badge/languages-13-0a84ff" alt="13 languages"></a>
  <a href="#faq"><img src="https://img.shields.io/badge/price-one--time%20purchase-34c759" alt="One-time purchase"></a>
</p>

<p align="center">
  <!-- TODO: campaign link. Replace every https://apps.apple.com/app/id6762026455?mt=12 in this file with https://apps.apple.com/app/apple-store/id6762026455?pt=<PROVIDER_TOKEN>&ct=github&mt=12 -->
  <a href="https://apps.apple.com/app/id6762026455?mt=12"><img src="https://toolbox.marketingtools.apple.com/api/v2/badges/download-on-the-mac-app-store/black/en-us" height="40" alt="Download on the Mac App Store"></a>
</p>

<!-- TODO: assets/hero.gif (800px wide, under 5 MB). When it's in, replace this comment with:
<p align="center">
  <img src="assets/hero.gif" width="800" alt="Creating a new Markdown file and copying its path from the Finder right-click menu with PowerClick">
</p>
-->

Finder on macOS has no New File command and no Cut for files, and it hides Copy Path behind the Option key. PowerClick adds **New File**, **Copy Path**, **Cut & Move** and **Batch Rename** to the Finder right-click menu, with more tools in the menu bar. It is sandboxed, makes no network connections, and is a one-time purchase on the Mac App Store.

[Get PowerClick on the Mac App Store](https://apps.apple.com/app/id6762026455?mt=12) · [Website](https://powerclick.kilicov.dev/?utm_source=github&utm_medium=readme)

> This repository is PowerClick's home on GitHub: documentation, the changelog and the public issue tracker. PowerClick is not open source, and this repository contains no source code.

## Features

### New File

Create a new file right where you are in Finder. Built-in templates cover text, data, web and code files, and you can add your own file types with their own extension, content and icon. New File from Clipboard turns what you copied into a file, and smart naming prevents overwriting a file that already exists.

<!-- TODO: assets/new-file.gif -->

### Copy Path & file info

Copy a file's full path, parent folder path, name, name without extension or extension. You can also copy its size, its creation and modification dates, and the dimensions of an image.

<!-- TODO: assets/copy-info.png -->

### Cut & Move

Cut a file or folder in Finder and choose Move Here in the destination folder. Or send it straight to Desktop, Documents, Downloads, a recent destination or a favorite folder with Move To and Copy To. If an item with the same name is already there, choose Replace or Keep Both.

<!-- TODO: assets/cut-move.gif -->

### Batch Rename

Select several files and rename them in one step. Add a prefix or suffix, replace text, insert dates and sequence numbers, trim whitespace, remove special characters, and convert names to lowercase, UPPERCASE, Title Case, kebab-case or snake_case.

<!-- TODO: assets/batch-rename.gif -->

### Open in editor

Open selected files and folders in VS Code or another supported code editor straight from Finder, with no dragging and no terminal commands.

### Cloud folders

PowerClick works in iCloud Drive, Dropbox, Google Drive, OneDrive and Box folders. Grant access once and PowerClick remembers it. You can also add your Home folder, project folders and external locations, and manage folder access from the app at any time.

### Snippets & clipboard history

Save text you reuse, such as code blocks, email replies, terminal commands and templates, and pick recent clipboard text from the menu bar. Both are stored only on your Mac.

### Undo

Moved or renamed something by mistake? Undo Last Action reverses the last supported move or rename with one click.

### Appearance

Since version 2.2.0 you can choose Light, Dark or Auto (Auto follows macOS), one of nine theme colors, and a Clear or Tinted Liquid Glass look.

<!-- TODO: assets/settings-appearance.png -->

## Requirements

- macOS 13 Ventura or later
- Apple silicon or Intel Mac (PowerClick is a Universal app)
- The PowerClick Finder extension enabled in System Settings

## Getting started

1. Install PowerClick from the [Mac App Store](https://apps.apple.com/app/id6762026455?mt=12).
2. Open PowerClick. It lives in the menu bar.
3. Enable the Finder extension: open **System Settings > Privacy & Security > Extensions > Finder Extensions** and turn on PowerClick. The menu bar icon turns green when the extension is active.
   <!-- TODO: confirm the exact path on macOS 13, 14, 15 and 26. macOS 15 and later may list it under General > Login Items & Extensions instead. -->
4. Right-click a file, a folder or an empty area of a Finder window and open the PowerClick submenu.

## FAQ

**Is PowerClick a subscription?**
No. PowerClick is $5.99, paid once on the Mac App Store. There is no subscription and there are no in-app purchases.

**Does it work in iCloud Drive, Dropbox and other cloud folders?**
Yes. PowerClick works in iCloud Drive, Dropbox, Google Drive, OneDrive and Box folders. Grant access once and PowerClick remembers it.

**Does PowerClick collect any data?**
No. PowerClick is sandboxed, makes no network requests, and has no analytics or tracking. Your clipboard history, snippets and settings stay on your Mac. See [PRIVACY.md](PRIVACY.md).

**Why do I need to enable the Finder extension?**
macOS keeps every Finder extension off until you turn it on yourself. PowerClick's right-click menu comes from its Finder extension, so the menu appears only after you enable it in System Settings.

**Does PowerClick replace Finder?**
No. PowerClick adds its own submenu to Finder's right-click menu. Every built-in Finder command stays where it was.

**How do I get a refund?**
Apple handles all Mac App Store purchases and refunds. You can request a refund at [reportaproblem.apple.com](https://reportaproblem.apple.com).

## Support & feedback

- Found a bug? [Open a bug report](https://github.com/atakilicov/powerclick/issues/new?template=bug_report.yml).
- Have an idea? [Request a feature](https://github.com/atakilicov/powerclick/issues/new?template=feature_request.yml).
- Questions and setup help: [Discussions](https://github.com/atakilicov/powerclick/discussions).
- Anything you'd rather not post publicly: [ata@kilicov.dev](mailto:ata@kilicov.dev).

[SUPPORT.md](SUPPORT.md) lists what to include in a bug report.

## Languages

PowerClick is available in 13 languages: English, Spanish, German, French, Portuguese, Turkish, Dutch, Italian, Japanese, Korean, Russian, Simplified Chinese and Traditional Chinese.

<!-- TODO (phase 2): link localized/README.tr.md, README.es.md, README.pt-BR.md and README.de.md here once they exist. -->

## Changelog

**2.2.0** (July 26, 2026) adds Appearance settings: Light, Dark or Auto, nine theme colors, and a Clear or Tinted Liquid Glass look. It also improves contrast in Light mode and fills in missing translations across all 13 languages.

See [CHANGELOG.md](CHANGELOG.md) for the full version history, or [Releases](https://github.com/atakilicov/powerclick/releases).

---

PowerClick is made by [Kilicov](https://www.kilicov.dev/?utm_source=github&utm_medium=readme), an independent app studio in Istanbul.

PowerClick is not open source. This repository contains documentation and media only. See [LICENSE.md](LICENSE.md).
