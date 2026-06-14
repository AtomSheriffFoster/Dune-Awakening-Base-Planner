# Changelog

All notable changes to Dune Awakening Base Planner will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [2.4.1] - 2026-06-14

### Fixed
- Fixed a crash when loading large base layouts with many buildings
- Fixed power calculation rounding errors in the generator planner
- Fixed resource totals not updating correctly after removing buildings

### Improved
- Improved startup performance on low-end systems
- Improved UI scaling on 4K displays

---

## [2.4.0] - 2026-05-28

### Added
- **Deep Desert mode** — dedicated planning mode with Deep Desert building cost multipliers
- **Export to image** — export your base layout as a PNG file to share with your clan
- **Power zone visualization** — color-coded power coverage overlay on the base grid
- Added support for all buildings from the May 2026 game update

### Fixed
- Fixed defense planner not saving turret placement correctly
- Fixed production chain loop detection not working for complex chains

---

## [2.3.0] - 2026-04-15

### Added
- **Production Chain Optimizer** — new module for mapping resource flows from raw nodes to final products
- **Clan share feature** — export/import base layouts as JSON files to share with teammates
- Added Salvaged Metal, Cobalt Paste, and Calibrated Servok to the resource calculator

### Changed
- Redesigned the resource calculator UI for faster input
- Base layout grid increased to 64x64 tiles

### Fixed
- Fixed storage capacity not being included in resource planning totals

---

## [2.2.0] - 2026-03-10

### Added
- **Defense Planner module** — plan turret placement, wall perimeters, and security zones
- Added Hagga Basin and Deep Desert zone presets
- Keyboard shortcuts for common actions (rotate, delete, undo)

### Fixed
- Fixed undo/redo not working correctly after saving a layout
- Fixed generator count calculation for large bases

---

## [2.1.0] - 2026-02-01

### Added
- **Save & Load layouts** — store multiple base configurations locally
- **Power Calculator** — calculate generator requirements and coverage per zone
- Dark mode UI

---

## [2.0.0] - 2026-01-10

### Added
- Complete rewrite with new modular UI
- **Base Layout Designer** with drag-and-drop grid editor
- **Resource Cost Calculator** covering all base buildings
- Windows 11 support

---

## [1.0.0] - 2025-11-20

### Added
- Initial release
- Basic base grid planner
- Resource list for common buildings
