# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [unreleased]

## [1.1.3] - 2023-09-18

### Added

- `chlPageData` option (undocumented - enterprise only)
- `(after|before)-interactive-callback` and `unsupported-callback`
- `turnstile.isExpired`
- Ukranian language (`uk`)

## [1.1.2] - 2023-03-09

### Added

- Option: `appearance`
- Option: `execution`
- Function: `ready`
- Function: `implicitRender`
- Function: `execute`

## [1.1.1] - 2023-02-06

### Changed

- Export `SupportedLanguages`
- Export `WidgetId`, `ElementId` and `Container`

## [1.1.0] - 2023-02-06

### Added

- `refresh-expired`
- `language`
- `TurnstileObject` which is equal to `window.turnstile`
- Defaults of each option in comments

### Changed

- More appropiate type-hints for container and widget id

### Fixed

- Missing token argument for `expired-callback`

## [1.0.1] - 2022-11-25

### Fixed

- Fix name of `retry-interval`

## [1.0.0] - 2022-11-25

Initial release.

[unreleased]:
	https://github.com/Le0Developer/turnstile-types/compare/v1.1.3...HEAD
[1.1.3]: https://github.com/Le0Developer/turnstile-types/releases/tag/v1.1.3
[1.1.2]: https://github.com/Le0Developer/turnstile-types/releases/tag/v1.1.2
[1.1.1]: https://github.com/Le0Developer/turnstile-types/releases/tag/v1.1.1
[1.1.0]: https://github.com/Le0Developer/turnstile-types/releases/tag/v1.1.0
[1.0.1]: https://github.com/Le0Developer/turnstile-types/releases/tag/v1.0.1
[1.0.0]: https://github.com/Le0Developer/turnstile-types/releases/tag/v1.0.0
