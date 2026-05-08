# Changelog

All notable changes to the Sim-plicity Team Manager desktop application.

**Version Status Note**: This changelog includes both publicly released versions and internal development builds. The last version distributed to end users via auto-update was v25.04.01. Versions from v25.10.01 onward represent UAT and development cycles and may not yet be available through official release channels.

---

## [26.04.02] - 2026-04

### Added
- **Sim Profile Auto-Load**: Assign a wheelbase profile to any supported sim and Team Manager loads it automatically when the game starts
- **Updated icons**: All icons replaced with a clean stroke-based set for a more consistent look throughout the app
- **Improved log collection**: Per-session logs are now extracted and packaged as a zip for easier troubleshooting

### Changed
- Profile rename, save, and preview now use native dialogs
- Profile preview displays values with proper formatting
- App is now locked to dark theme to prevent visual issues on systems with a light OS theme

### Fixed
- Profile rename, save, and preview not working correctly
- Preset status not updating when switching between connected wheelbases
- Text placeholders not displaying correctly

---

## [26.04.01] - 2026-04

### Added
- **Firmware Loader V3**: Migrated firmware installation from V2 to V3 for improved reliability and compatibility with newer devices
- **External hardware detection**: Automatic detection for external hardware bootloader devices — DIY and Gen 1 OSW controllers are now properly identified when connected
- **Improved update delivery**: Optimized delta-based update process for smaller downloads and faster installations

### Changed
- **Hardware communication**: Added command integrity checks, proper HID command queuing, and automatic FFB polling timeout for unresponsive devices
- **Stability**: Startup crashes are now logged, background task failures are caught, and over 1,700 lines of obsolete HID code removed
- **UI**: All tabs now stretch to fill available width consistently

### Fixed
- Settings tab appearing blank after switching between wheelbase tabs
- FFB upgrade button appearing incorrectly on devices with outdated firmware
- Bootloader version display for devices in firmware update mode

---

## [26.03.02] - 2026-03

### Added
- **Offline license tracking**: License status syncs when connected, tracks remaining offline access days when disconnected, and alerts when reconnection is required
- **Improved sim detection**: Replaced all-or-nothing cache with per-sim partial loading for faster startup and more reliable game detection
- **Refreshed UI design**: Updated card styling and sub-tab layout for a cleaner, more consistent appearance

### Fixed
- LiveFFB gain slider now correctly reflects the wheel's current active value

---

## [26.03.01] - 2026-03

### Fixed
- **Force feedback stability**: Fixed critical bug where FFB effects could accumulate incorrectly, timer synchronization issues, and crashes during concurrent device access
- **Device disconnect handling**: Fixed detection issues when devices disconnect and reconnect, and timers continuing to run after disconnect

---

## [26.02.02] - 2026-02

### Added
- **Unified status bar**: Five-color status bar showing connection state, authentication status, and device health at a glance
- **Live FFB Gain Mixer**: Real-time adjustment of force feedback gains for individual effects without disconnecting from your sim
- **V2 SPI protocol configuration**: Support for configuring V2 SPI protocol settings on compatible firmware versions

### Changed
- **Device detection**: Improved initialization, especially for devices in bootloader mode

### Fixed
- Device detection failure at application startup when wheelbase is plugged in
- Settings and Advanced tabs showing default values instead of actual device settings
- Firmware tab not loading when device is in bootloader mode

---

## [26.02.01] - 2026-02

### Added
- **Account tab**: API key management for generating, viewing, and managing authentication keys
- **Redesigned icons**: Improved visual clarity for tab and sub-tab navigation

### Changed
- **Firmware downloads**: Now authenticate with your account for access to appropriate firmware versions
- **Console Mode requirement**: Now requires firmware v26.01.02 or later for compatibility and stability

### Fixed
- Application freeze when switching between Console Mode and Direct Mode
- Direct Mode firmware options not appearing when expected
- Firmware tab not updating when signing in or out

---

## [26.01.02] - 2026-01

### Added
- **Account authentication**: Sign-in infrastructure for accessing premium features and firmware updates
- **Ticket tracking**: In-app workflow for tracking bug report status directly from the Help section
- **Log file links**: Clickable links to log file locations in Troubleshooting tab

### Changed
- **Dark theme**: Applied consistent dark theme across Firmware, Advanced settings, and notification banners

### Fixed
- Bug report Submit button not enabling when form is valid
- Load Button clipping issue in Profiles sub-tab
- Settings and Advanced tabs not responding when authentication state changes
- UI inconsistencies with button sizing and layout
- Application shutdown by properly disposing device resources

---

## [26.01.01] - 2026-01

### Added
- **Help section**: New tab with guides, troubleshooting tips, and in-app issue reporting

### Changed
- **Visual clarity**: Improved color contrast throughout the interface

### Fixed
- Profiles now save correctly and refresh properly
- Deleting a profile no longer causes a crash
- Creating new profile now inherits current settings and is automatically selected
- Bug Report UI no longer crashes on shutdown and displays correctly in both light and dark themes
- Issue with BootLoader mode devices

---

## [25.12.02] - 2025-12

### Changed
- **Application stability**: Fixed several issues that could cause crashes during shutdown
- **Hardware connectivity**: Improved connection and communication with wheelbases to prevent hangs

---

## [25.11.01] - 2025-11

### Added
- **Automatic updates**: New system for installing and updating the application automatically
- **Hardware support documentation**: Comprehensive support documentation for third-party and legacy hardware devices

### Fixed
- Integration with iRacing

---

## [25.10.02] - 2025-10

### Added
- **USB mode notifications**: Upgrade notifications for Console and Direct USB modes

### Fixed
- **Profiles**: Fixed issue where Profiles dropdown would sometimes appear empty and several bugs related to profile loading
- **USB modes**: Fixed recursive calls when selecting USB modes; mode selection now works correctly

---

## [25.10.01] - 2025-10

### Added
- **Weight Threshold**: Advanced wheelbase configuration feature (requires account)

### Changed
- **Hardware integration**: Improved wheelbase communication and reliability

---

*Last Updated: May 8, 2026*
