# Changelog

All notable changes to SnapDraw will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.3] - 2025-01-02

### Added
- **Capture Delay Feature** - New delay option before capturing to maintain hover states
  - Configurable delay times: 1, 2, 3, 5, or 10 seconds
  - Mouse-following countdown display during delay
  - Visual area indicator with red outline during countdown
  - Mouse events pass through indicator (pointer-events transparent)
  - Perfect for capturing tooltips, dropdowns, and hover effects
- **Google Analytics Integration** - Usage analytics for feature improvement
  - Track area capture, fixed area capture, and timer sequence events
  - Track drawing tool usage (pen, eraser, shapes, etc.)
  - Track license activation and feature usage
  - Analytics consent setting in Preferences

### Changed
- Copyright year updated to 2025
- Area indicator styling improved with thinner border (1px solid)
- Area indicator background made more transparent (0.01 opacity)
- Countdown window no longer has rounded corners for cleaner look

### Fixed
- Area indicator properly closes before capture to avoid being captured
- Focus restoration improved for better hover state preservation
- Mouse tracker intervals properly cleaned up on countdown completion

## [1.0.2] - 2024-12-30

### Added
- Multi-monitor toolbar drag improvements
- Fixed area multi-window drag enhancements
- Snap Box size adjustments

### Changed
- Enhanced toolbar behavior across multiple displays
- Improved window dragging experience for fixed area captures

### Fixed
- Fixed area toolbar positioning on multiple monitors
- Snap Box sizing issues

## [1.0.1] - 2024-12-28

### Added
- Initial public release
- Screen capture with area selection
- Floating screenshot windows
- Drawing and annotation tools (pen, eraser, line, circle, rectangle, arrow)
- Color picker and line width adjustment
- Fixed area capture for repeated screenshots
- Timer sequence capture
- Opacity control with mouse wheel
- Customizable keyboard shortcuts
- License management system
- Auto-updater
- Launch at login option
- Screen recording permission handling

### Security
- Screen recording permission checks
- User-friendly permission guides
- Real-time permission status monitoring

---

## Release Notes Format

Each version includes:
- **Added**: New features
- **Changed**: Changes in existing functionality
- **Deprecated**: Soon-to-be removed features
- **Removed**: Removed features
- **Fixed**: Bug fixes
- **Security**: Security improvements
