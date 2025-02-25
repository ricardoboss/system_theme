## [2.3.0] - [04/07/2023]

- Removed `SystemTheme.darkMode` ([#24](https://github.com/bdlukaa/system_theme/pull/24))
- Prevent app breaks on loading accent color failed ([#19](https://github.com/bdlukaa/system_theme/pull/19))

## [2.2.0] - [03/06/2023]

- Fix app build on Android ([#14](https://github.com/bdlukaa/system_theme/issues/14))

## [2.1.0] - [09/01/2023]

- Bundle source code with the package for Windows ([#8](https://github.com/bdlukaa/system_theme/issues/8))
- Added `SystemTheme.fallbackColor` ([#9](https://github.com/bdlukaa/system_theme/issues/9))
- Support for Linux and macOS ([#11](https://github.com/bdlukaa/system_theme/pull/11))

## [2.0.0] - Breaking Changes - 03/04/2022

- **BREAKING** `darkMode` was renamed to `isDarkMode`, and it's now sync
- **BREAKING** `accentInstance` was renamed to `accentColor`
- `SystemAccentColor` is now an extension of `Color`

## [1.0.1] - 12/05/2021

- Remove external C++ source present in the repository ([#1](https://github.com/bdlukaa/system_theme/pull/1))
- Improved the example app

## [1.0.0] - Initial - 01/04/2021

- Get system accent color
- Check if system is in dark mode
