# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- pimod.sh -t: trace executed commands for debugging.
- Started a CHANGELOG.md with prior changes.

### Changed
- FROM: document PARTITION_NO argument.

### Fixed
- PUMP: fix behavior for bigger partition tables.
- Print Warning on QEMU binary fmt loading err.

## [0.3.0] - 2021-09-23
### Added
- Adjust GitHub Actions for Pull Requests.
- Add INCLUDE command; @aniongithub.

## [0.2.2] - 2021-05-02
### Changed
- Printing file system usage information, if PUMP was used.
- Warn for Windows/DOS newlines.

### Fixed
- qemu_setup: determine path by command -v
- from_remote_fetch: delete image if download failed.

## [0.2.1] - 2021-01-17
### Fixed
- Changed GitHub Action name for marketplace submission.
- Successful e2fsck lead to failing build.

## [0.2] - 2020-12-01
### Added
- Introducing shellcheck CI integration.
- Added paper to readme, <https://jonashoechst.de/assets/papers/hoechst2020pimod.pdf>.
- Implemented reusable GitHub Action.

### Changed
- Basing Docker container on debian:bullseye-slim.

### Fixed
- Disable bash error abort in file name parsing.
- Fixed a bug, where killing of remaining processes failed.
- Adjusted Dockerfile to reflect project structure.

## [0.1] - 2020-04-26
### Added
- Initial release of a working version of pimod.

[Unreleased]: https://github.com/Nature40/pimod/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/Nature40/pimod/compare/v0.2.2...v0.3.0
[0.2.2]: https://github.com/Nature40/pimod/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/Nature40/pimod/compare/v0.2...v0.2.1
[0.2]: https://github.com/Nature40/pimod/compare/v0.1...v0.2
[0.1]: https://github.com/Nature40/pimod/releases/tag/v0.1