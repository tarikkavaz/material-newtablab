# Change Log

All notable changes to the ".K Material" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

### Changed
- Added chat.requestBackground and chat.avatarBackground colors to match the new chat UI

- Matched editor background color to terminal background for visual consistency

### Fixed
- Added transparency to background colors that were obscuring content:
  - `editor.inactiveSelectionBackground`
  - `editor.selectionHighlightBackground`
  - All merge conflict background colors (currentHeaderBackground, currentContentBackground, incomingHeaderBackground, incomingContentBackground, commonHeaderBackground, commonContentBackground)
  - Minimap highlight colors (findMatchHighlight, selectionHighlight)
- Updated deprecated properties:
  - `editorIndentGuide.background` → `editorIndentGuide.background1`
  - `editorIndentGuide.activeBackground` → `editorIndentGuide.activeBackground1`
- Fixed fontStyle values: Changed `"normal"` to `""` (empty string) for attribute name styles

- Initial release
