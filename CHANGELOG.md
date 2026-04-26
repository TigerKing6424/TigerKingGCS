# Changelog

All notable changes to TigerKingGCS will be documented in this file.
This project is currently in PILOT (experimental) stage.

## v0.1.1-pilot-beta — 2026-01-26

### Added
- Live MAVLink connection with SITL (UDP)
- Keyboard velocity control (WASD / Arrow keys)
- Map view with GPS marker and heading display
- App icon and toolbar icon (TigerKing theme)
- Help menu with About and Changelog entries

### Improved
- MAVLink auto-reconnect and heartbeat handling
- Telemetry polling stability
- UI layout and menu structure
- Command ACK logging for debugging

### Fixed
- UI freeze during reconnect attempts
- Map widget initialization errors
- Heartbeat detection false disconnects

### Known Issues
- NAV_TAKEOFF command fails in SITL
- Drone model icon not yet rendered on map
- GPS position update may appear static in some cases
- Battery warnings may trigger in simulation

### Core system

- MAVLink connection (UDP SITL)
- Auto reconnect / heartbeat handling
- Arm / mode change (GUIDED)
- Velocity control (WASD, arrows)
- Command ACK handling

### UI / UX

- Tk / Qt main window
- Menu bar (Help, About, Changelog)
- Toolbar icon
- App icon (TigerKing theme)
- Warning / log output

### Map / Telemetry

- Live GPS read (GLOBAL_POSITION_INT)
- Map widget (tkintermapview)
- Marker update
- Heading display
- Telemetry panel (ALT, GPS, speed print)

## v0.1.0-pilot-beta — 2026-01-20

### Added
- Initial TigerKingGCS pilot release
- Basic MAVLink connection
- Telemetry logging (ALT, GPS)
- Early UI prototype

## v1.0.0 - 2026-04-02 — Initial Release

First stable release of **TigerKing GCS** 🎉

### ✨ Highlights

* 🔐 User authentication (register, login, email verification, 2FA)
* 👥 Referral system with unique codes & auto tracking
* 💳 Crypto payments via NOWPayments (invoice-based)
* 📊 Referral dashboard (points, invited users, progress)
* 🎯 Milestone reward system (invite targets)

### ⚙️ Core

* Cloudflare D1 database integration
* Orders & commission tracking
* Secure API structure

### 🛠 Fixes & Improvements

* Improved referral + commission logic
* Better error handling
* Responsive UI (mobile + desktop)

### 📌 Notes

* First production-ready version
* More features coming soon (more control system, analytics, etc.)

---

Thanks for using TigerKing GCS ❤️
