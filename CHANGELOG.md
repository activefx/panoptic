# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed

- Fixes N+1 on failed jobs index - [virolea](https://github.com/virolea)
- Add back `/jobs` route prefix to scheduled and failed jobs routes

## [0.4.1]

### Fixed

- Remove mail-related code - [virolea](https://github.com/virolea) ([#12](https://github.com/virolea/panoptic/pull/12))

## [0.4.0]

### Added

- Add Job retries to failed jobs - [kylekeesling](https://github.com/kylekeesling) ([#8](https://github.com/virolea/panoptic/pull/8))

## [0.3.0]

### Added

- Add a detailed view for failed jobs ([#6](https://github.com/virolea/panoptic/pull/6))

## [0.2.0]

### Added

- Jobs filtered views ([#5](https://github.com/virolea/panoptic/pull/5))

### Changed

- Improved job time values display and removed job arguments from job index view

## [0.1.3]

### Changed

- Replace kaminari with pagy for pagination purposes

## [0.1.2]

### Fixed

- Remove link to deleted css file from layout

## [0.1.1]

### Fixed

- Remove assets folder to prevent compilation errors in production
