---
last-synced: 2026-03-30T13:24:59.181Z
---
# Changelog

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]

### Added
- Dark mode support
- Plugin API v2
Some Change
---

## [2.1.0] - 2026-02-14

### Added
- New `--watch` flag for live reloading
- Support for YAML config files

### Fixed
- Memory leak in the event loop (#142)
- Incorrect path resolution on Windows (#138)

### Changed
- Upgraded dependencies to latest stable versions

---

## [2.0.0] - 2025-11-01

### Breaking Changes
- Removed deprecated `init()` callback API — use `async/await` instead
- Config key `outputDir` renamed to `outDir`

### Added
- Full TypeScript support
- CLI interactive mode

---

## [1.0.0] - 2025-06-15

### Added
- Initial release
