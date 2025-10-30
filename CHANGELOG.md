# Changelog

All notable changes to SnapDraw will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.2] - 2024-10-31

### ✨ Added

- **YouTube Demo Video** - Added demo video section to landing page for better product showcase
- **Enhanced About Tab** - Expanded feature list in Settings to showcase all 13 comprehensive features

### 🔄 Changed

- Updated landing page with improved feature descriptions
- Improved user onboarding experience with video demonstration

---

## [1.0.1] - 2024-10-30

### ✨ Added

- **Fixed Area Capture (Pro)** - Create reusable capture frames that stay in position
  - Save frequently used capture areas
  - Multiple fixed areas support
  - Multi-monitor support with improved drag behavior
  - Independent toolbar for each fixed area window
- **Timer Sequence Capture (Pro)** - Automated time-based screenshot capture
  - Set custom intervals (seconds)
  - Specify number of captures or continuous mode
  - Real-time countdown display
  - Ideal for capturing dynamic content, tutorials, or monitoring
- **Snap Box (Pro)** - Thumbnail widget for quick screenshot access
  - Floating thumbnail preview of recent captures
  - Drag and drop to organize
  - Quick access to full-size view
  - Adjustable size and position
- **Google Analytics Integration** - Usage analytics for both web and desktop app
  - Privacy-first implementation with user consent
  - Separate data streams for web (landing3) and desktop app
  - Event tracking for feature usage and performance monitoring
  - Comprehensive setup guide included

### 🐛 Fixed

- **License Validation Security** - Fixed critical bug where licenses from different LemonSqueezy products could activate SnapDraw
  - Added product ID validation to prevent cross-product license usage
  - Enhanced security with strict product matching
- **Capture Window Flash** - Fixed visual bug where "Capture Screenshot" text flashed before image loaded
  - Implemented image-ready event system
  - Window now only shows after image is fully rendered
  - Smoother capture experience

### 🎨 Improved

- **Settings Panel Design** - Simplified License tab to match other tabs' clean design
  - Removed heavy gradient styling
  - Added small status badge for license state
  - Better visual consistency across all tabs
- **Context Menu** - Enhanced floating window right-click menu
  - Dynamic "🔑 Enter License" menu (shows only when not activated)
  - Added "⚙️ Settings" menu for easy access
  - Menu items adapt based on license status
- **Multi-Monitor Support** - Improved Fixed Area window dragging across multiple displays
  - Better toolbar positioning on multi-monitor setups
  - Smoother drag behavior between monitors
- **Landing Page** - Enhanced landing3 website
  - Updated download URLs to v1.0.1
  - Added new feature descriptions for Fixed Area, Timer Sequence, and Snap Box
  - Improved hero slider with new screenshot
  - LemonSqueezy purchase integration

### 📚 Documentation

- **Google Analytics Setup Guide** - Comprehensive guide for GA4 setup (20251030_GOOGLE_ANALYTICS_SETUP.md)
  - Account creation steps
  - Data stream configuration
  - API secret generation
  - Testing and troubleshooting
- **Code Signing Guide** - Added detailed code signing and notarization guide
- **Independent Distribution Guide** - Documentation for manual release process

### 🛠️ Technical

- Added analytics module for desktop app (Measurement Protocol API)
- Improved IPC communication for license and settings management
- Enhanced window lifecycle management with event-driven visibility
- Better environment variable configuration for GA4

---

## [1.0.0] - 2024-10-25

### 🎉 Initial Release

SnapDraw is a powerful screenshot annotation tool for macOS that keeps your captures floating on top of all windows.

### ✨ Free Features

- **Smart Area Capture** - Visual guide lines for pixel-perfect screen capture
- **Always On Top** - Keep screenshots floating above all windows
- **Adjustable Opacity** - Scroll to adjust transparency (see through your captures)
- **Drag & Resize** - Freely move and resize floating screenshots
- **Quick Save** - Save screenshots instantly with ⌘S
- **Copy to Clipboard** - One-click copy with ⌘C
- **Keyboard Shortcuts** - Efficient workflow with customizable shortcuts
- **Multi-Display Support** - Works seamlessly across multiple monitors
- **Screen Recording Permission** - User-friendly permission setup guide

### 💎 Pro Features ($1.99 - Lifetime)

- **Drawing Tools** - Pen and highlighter with multiple widths
- **Eraser** - Remove annotations with custom size control
- **Text Annotations** - Add text anywhere on your captures
- **Arrows & Shapes** - Draw arrows, rectangles, and circles
- **Color Picker** - Choose any color for your annotations
- **Drawing Mode Toggle** - Quick enable/disable drawing tools
- **Undo/Redo** - Full drawing history support
- **Lifetime Updates** - All future updates included

### 🔐 License System

- **LemonSqueezy Integration** - Secure license validation
- **Single Device Activation** - One license per device
- **Offline Grace Period** - 7-day offline validation
- **Device Fingerprinting** - Secure device identification

### 🔄 Auto-Update System

- **GitHub Releases Integration** - Automatic update detection
- **Background Downloads** - Updates download in the background
- **User Control** - Choose when to install updates
- **Manual Check** - Check for updates from menu bar

### 🎨 User Interface

- **Modern macOS Design** - Native macOS look and feel
- **Menu Bar App** - Quick access from menu bar
- **Preferences Window** - Easy settings management
- **Welcome Dialog** - First-time user onboarding
- **Permission Guides** - Step-by-step setup instructions

### 🛠️ Technical Features

- Built with Electron 28
- Native macOS integration
- Secure local storage (electron-store)
- Environment-based configuration
- Development and production modes

### 📋 System Requirements

- macOS 12 (Monterey) or later
- Screen Recording permission
- Internet connection (for license activation and updates)

---

## How to Update

- **Automatic**: The app checks for updates on startup and notifies you
- **Manual**: Click "Check for Updates" in the menu bar

---

## Support

- **Issues**: https://github.com/ashsofter/snap-draw/issues
- **Email**: info@ashsoft.us
- **Website**: https://snapdraw.app (coming soon)

---

**Full Changelog**: https://github.com/ashsofter/snap-draw/commits/v1.0.0
