# Changelog

All notable changes to PowerClick, newest first. Versions and dates follow the Mac App Store version history. The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [2.2.0] - 2026-07-26

### Added

- Appearance settings in Settings > Appearance: Light, Dark or Auto. Auto follows your macOS setting, including the automatic switch at sunset. Your choice applies to the dashboard and the menu bar popover, and never changes your system appearance.
- Nine theme colors, applied across the whole app: Multicolor (follows your system accent color), Blue, Purple, Pink, Red, Orange, Yellow, Green and Graphite.
- A Clear or Tinted Liquid Glass look. On macOS 26 this uses the native Liquid Glass material.

### Changed

- Better contrast and readability in Light mode. Card materials, separators, captions and text on colored fills were reworked so they read well in both appearances.

### Fixed

- Missing translations filled in across all 13 languages. Four Finder menu labels no longer fall back to raw keys, and missing strings were restored in Spanish, French, Dutch and Portuguese.

## [2.0.2] - 2026-07-22

### Fixed

- Minor bug fixes.

## [2.0.1] - 2026-06-28

### Fixed

- A performance issue. The dashboard layout was simplified and redundant view work removed, for smoother scrolling.
- Snippet and clipboard rows in the menu bar popover now size consistently.
- Missing Italian translations.

## [2.0.0] - 2026-06-26

### Added

- Cloud folder support for iCloud Drive, Dropbox, Google Drive, OneDrive, Box and other folders you grant access to. Grant access once and PowerClick remembers it.
- Open in Editor, to open selected files and folders in VS Code and other supported editors.
- Batch Rename with prefix, suffix, lowercase, uppercase, title case, kebab-case, snake_case, date prefix, sequence numbers, whitespace cleanup and more. Save presets and reuse recent ones.
- Copy To, with favorite folders and recent destinations.
- Access to multiple folders instead of a single granted folder.
- Undo Last Action for supported move and rename operations.
- Quick File Info, to copy file names, paths, extensions, sizes, dates and image dimensions.
- 6 new languages: Italian, Japanese, Korean, Russian, Simplified Chinese and Traditional Chinese, for 13 in total.

### Changed

- Move To now offers favorite folders and recent destinations. If an item with the same name already exists, choose Replace or Keep Both.
- Redesigned app interface with clearer sections and smoother interactions.
- Better organized Finder menu with clearer action labels.
- Improved performance, sandbox access handling and overall reliability.

## [1.1.0] - 2026-04-30

### Added

- "Cut with PowerClick" and "Move Here", to move files and folders within Finder.
- Create PNG files from images or screenshots on your clipboard.
- The Menu Editor can now edit existing custom items, and has a new icon picker.
- Localization in 7 languages: English, Spanish, German, French, Portuguese, Turkish and Dutch.

### Changed

- Redesigned the Settings window into clearer categories: Finder, Clipboard, Appearance and About.
- New File from Clipboard now handles both text and images.
- Performance improvements, better sandbox access handling and clearer Finder menu labels.

## [1.0.1] - 2026-04-24

### Changed

- General performance improvements.

### Fixed

- More reliable file creation from the Finder extension.
- More stable sandbox access, using secure folder bookmarks so granted folders stay available.
- The clipboard history toggle could show the wrong state.

## [1.0] - 2026-04-24

### Added

- First release on the Mac App Store, with New File templates, clipboard history, a snippet library and Finder right-click tools.

[2.2.0]: https://github.com/atakilicov/powerclick/releases/tag/v2.2.0
[2.0.2]: https://github.com/atakilicov/powerclick/releases/tag/v2.0.2
[2.0.1]: https://github.com/atakilicov/powerclick/releases/tag/v2.0.1
[2.0.0]: https://github.com/atakilicov/powerclick/releases/tag/v2.0.0
[1.1.0]: https://github.com/atakilicov/powerclick/releases/tag/v1.1.0
[1.0.1]: https://github.com/atakilicov/powerclick/releases/tag/v1.0.1
[1.0]: https://github.com/atakilicov/powerclick/releases/tag/v1.0
