# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Boilerplate repository infrastructure (GitHub actions, Issue Templates, PR Templates).
- Spanish and French translations.
- Locked orientation to portrait mode.
- Localized calendar relative formatting supporting summer time timezone shifts.

### Fixed
- Fixed memory leaks caused by wallpaper color listener.
- Migrated background lists from raw threads to lifecycle-aware coroutines.
- Replaced deprecated ActivityResult patterns with ActivityResultLauncher.
