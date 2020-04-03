# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.0] - 2020-04-03

### Added
- Support fixed cases of multipart/form-data

### Fixed
- Empty postData param value causes converter crash

## [0.2.0] - 2020-03-13

### Changed
- Less strict validation for postData
- Prioritize postData.params over postData.text

### Added
- Run babel on standalone bundle

## [0.1.5] - 2020-02-17

### Fixed
- Remove pseudo headers
- Remove cookies
- Remove Content-Length header

## [0.1.4] - 2020-02-05

### Fixed
- Allow charset in postData mimeType
- Use both id and title for group name

## [0.1.3] - 2019-08-05

### Changed
Start using scheme for jslib module imports.

## [0.1.2] - 2019-07-10

### Fixed
Missing sleep import.

## [0.1.1] - 2019-07-09

### Added
- add CHANGELOG

### Fixed
Broken positional arg in caporal resulting in broken `har-to-k6` command.

## [0.1.0] - 2019-07-09
### Added
- Initial release

[Unreleased]: https://github.com/loadimpact/har-to-k6/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/loadimpact/har-to-k6/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/loadimpact/har-to-k6/compare/v0.1.5...v0.2.0
[0.1.5]: https://github.com/loadimpact/har-to-k6/compare/v0.1.4...v0.1.5
[0.1.4]: https://github.com/loadimpact/har-to-k6/compare/v0.1.3...v0.1.4
[0.1.3]: https://github.com/loadimpact/har-to-k6/compare/v0.1.2...v0.1.3
[0.1.2]: https://github.com/loadimpact/har-to-k6/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/loadimpact/har-to-k6/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/olivierlacan/keep-a-changelog/releases/tag/v0.1.0