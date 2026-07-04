# Changelog

All notable changes to the Stranger Things Tribute Page will be documented in this file.

## [1.1.0] - 2026-07-04

### Added
- **Boutique Design System**: Migrated to a professional 4-column Bento Grid layout.
- **Glassmorphism 2.0**: Upgraded cards with frosted acrylic effects, `backdrop-filter` blur, and Linear-Gradient light sweeps.
- **Cinematic Atmosphere**: Added a fractal noise film-grain overlay and GPU-accelerated drifting ambient orbs.
- **Magnetic Interactions**: Implemented a Lerp-based `MagneticCard` class for tactile cursor-following animations.
- **Cast Portraits**: Replaced emojis with high-resolution professional portraits of the main cast.
- **Typographic Polish**: Adjusted letter-spacing and line-heights for agency-grade visual hierarchy.

### Changed
- **UI Cleanup**: Removed the audio control panel from the bottom right to reduce visual noise.
- **Performance**: Enforced `translate3d` and `will-change` for 60fps animation fluidity.

### Fixed
- Resolved a fatal JS error where missing audio control elements blocked the "Enter" screen functionality.

## [1.0.0] - 2025-01-01

### Added
- Initial fan-tribute page for Stranger Things (Netflix Original Series)
- Enter screen with animated "Enter with Music" button
- Audio engine: background music loop, hover/click SFX, volume slider
- Floating particle ambient effects (15s CSS keyframe animation)
- Featured Episodes section: The Vanishing of Will Byers, The Gate, The Battle of Starcourt
- Main Characters section: Eleven, Mike Wheeler, Dustin Henderson, Will Byers
- Quote section: "Friends don't lie" — Eleven
- Styling: dark-mode palette with Stranger Red (#e62429) + Upside Down Teal (#00d4aa), glass-morphism, neon glows
- Keyboard shortcuts: Space (enter/play-pause), Arrow Up/Down (volume)
- Responsive breakpoints for mobile (768px)
- Hover sound effects on episode/character cards via JavaScript event delegation
