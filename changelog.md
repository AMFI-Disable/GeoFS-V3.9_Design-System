# Changelog

All notable changes, design tokens, and version releases for GeoFS-V3.9 Design System are documented in this file.

---

## [3.9.0] - Unified Metadata

### Changed

- Standardize the userscript metadata and version across the V3.9 ecosystem.
- Match only the GeoFS main site and activate only when it reports V3.9.

---

## [Unreleased]

### Changed

- **Design Token Harmonization**: Replaced high-contrast amber accent theme with neutral monochrome styling (`#dddddd`, `#888`) and green indicators (`#4caf50`) across cockpit controls.
- **Typography Standardization**: Standardized interface font stacks across all HUD overlays.
- **Favicon Metadata**: Switched userscript icon reference to the official GeoFS favicon.

---

## [2.0.6] - GeoFS V3.9 Compatibility

### Changed

- Start only after GeoFS reports V3.9; remain inactive on other or unrecognized versions.
- Update compatibility documentation and version metadata.

---

## [2.0.1] - Token Harmonization And Responsive Layouts

### Added

- **Centralized CSS Variables**: Global design tokens for glassmorphic backdrop-filter blur, border radii, and cockpit alert palettes.
- **High-DPI Screen Optimization**: Refined vector icons and typography for crisp rendering on Retina displays.

### Fixed

- **Z-Index Layer Hierarchy**: Standardized modal and floating widget z-index stacking to prevent UI overlapping.
- **Dark-Theme Contrast**: Enhanced amber/orange indicator contrast ratios against translucent dark backgrounds.

---

## [2.0.0] - Modern Glassmorphic Design System

### Added

- **Avionics Visual Language**: Dark-grey translucent panels with subtle borders mimicking modern integrated flight decks (Garmin G1000, Collins Pro Line).
- **Component Style Library**: Pre-built styles for dials, toggle switches, alert banners, and telemetry gauges.

---

## [1.0.0] - Initial Production Release

Initial release of the visual style framework and component styles for GeoFS-V3.9.
