# Changelog

All notable changes to AssilOS will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

### Added
- Initial boot sector code
- BIOS interrupt support (int 0x10, int 0x16)
- Keyboard input handling

### Fixed
- N/A (initial release)

### Changed
- N/A (initial release)

### Removed
- N/A (initial release)

---

## [v1.0.0] - 2026-06-23

### Added
- First public release
- 512-byte boot sector OS
- Based on nanochess BootOS with modifications
- Basic screen output functionality
- Keyboard input support
- Build instructions in README

### Known Issues
- Cannot boot from CD or USB (floppy disk only)
- Requires CSM/Legacy Boot mode on modern systems
- Limited to 16-bit real mode

---

## [v0.1.0] - 2026-06-01

### Added
- Initial project creation
- Forked from nanochess BootOS
- Basic boot sector framework
- NASM build script

---

## How to Update This File

When you make changes to AssilOS, add entries following these rules:

### Added
- New features that didn't exist before

### Changed
- Modifications to existing features

### Fixed
- Bug fixes and patches

### Removed
- Features that were taken out

### Security
- Security-related updates

---

