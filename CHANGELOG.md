# Changelog

All notable changes to Simple Notch are listed here. Each release on GitHub uses
the matching section below as its release notes.

## [Unreleased]

## [0.3.3] - 2026-09-21

### Added

- Weather widgets with current conditions, UV index, saved locations, and
  WeatherKit setup guidance.
- Important-event notifications in the notch, plus a larger drawer owned by
  the selected left-side widget.
- Expanded Coding Agents drawer and refinements to compact playback controls,
  scrolling text, and customization.

## [0.3.2] - 2026-09-20

### Fixed

- Keep the compact music bars animated during playback in Low Power Mode; the
  meter still stops when paused, hidden, or Reduce Motion is enabled.

## [0.3.1] - 2026-09-20

### Fixed

- Restored continuous animation for the compact right-side music bars after
  layout changes.
- Made the compact play/pause control respond immediately, resist stale media
  updates, and use the full right-side hit area.

## [0.2.0] - 2026-09-18

### Added

- Seven-day trial and in-app Polar license activation, with device-only
  Keychain storage, support for up to three Macs, periodic validation, and a
  seven-day offline allowance.
- A Polar-powered storefront for one-time and yearly plans, including secure
  post-checkout license-key delivery, download links, and activation guidance.
- Legal notice, privacy policy, and software license terms for the storefront.

### Changed

- Now Playing marquee text uses Core Animation layers for smoother, more
  reliable continuous scrolling.

## [0.1.2] - 2026-09-17

### Added

- App launcher shortcuts can be reordered by dragging their icons in Settings,
  with keyboard and context-menu controls available as alternatives.

### Changed

- Replaced download-only update notifications with signed Sparkle updates that
  can download and install new versions automatically.

## [0.1.1] - 2026-09-17

### Added

- Automatic update check: Simple Notch looks for a new release on GitHub once a
  day and offers to download it. Turn it off or check manually in Settings ›
  General.

### Changed

- The app launcher holds up to 8 apps, up from 6.
- Removed the "Use Preview Track" menu item from release builds.

## [0.1.0] - 2026-09-17

### Added

- Compact Now Playing next to the notch: cover art on the left, audio bars on
  the right coloured from the album art.
- Hover drawer with playback controls, an app launcher, or automatic switching
  between them.
- Per-display surfaces: attached notch shape on built-in displays, floating pill
  on external monitors.
- Now Playing, Spotify, and Apple Music sources.
- Liquid Glass or solid black surfaces, full-screen and external-display hiding.
- Settings for notch and pill sizing, plus a Permissions pane for Automation
  access.
