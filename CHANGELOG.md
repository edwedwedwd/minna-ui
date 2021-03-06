<!-- markdownlint-disable no-duplicate-header no-inline-html -->

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2018-06-14

### Added

- New file size badge in README of the [`@minna-ui/css`](https://github.com/WeAreGenki/minna-ui/tree/master/css) and each component package. Please keep in mind, for components, it shows the file size of the JavaScript bundle but not the CSS bundle due to a limitation in the service.
- New neutral font colour.
- Unit tests for CLI scripts.

### Removed

- Default margin between button. This should be up to the developer to decide based on their specific usage scenario.

### Changed

- Improved accessibility for form inputs and the toggle component. More noticeable visual focus indicator.
- Simplified side nav styles.
- Labels are now less prominent.
- Refine CSS animations for `.card-touch`.
- Update jest to v23.0.0 and rewrite preset to use the newly supported `jest-preset.js` (instead of `jest-preset.json`).
- Updated package dependencies.

## [0.1.0] - 2018-05-23

### Added

- Unit tests for all packages. Coverage now at 100% 🎉
- Wrote a simple readme for some packages but these are still a work in progress.

### Changed

- Component builds are now powered by rollup, replacing our custom build script. Builds are much more flexible and reliable now.
- New standalone option for `@minna-ui/postcss-config` to be used when `@minna-ui/css` is not installed.
- Simplify jest svelte transform.
- Updated package dependencies.

### Fixed

- Tweaked `@minna-ui/eslint-config` and `@minna-ui/jest-config` to work better with unit tests.
- Some edge cases in CSS mixins which were discovered via new unit tests.

## 0.0.0 - 2018-05-18

### Added

- Initial public release 🎊

[Unreleased]: https://github.com/WeAreGenki/ui/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/MaxMilton/new-tab/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/MaxMilton/new-tab/compare/v0.0.0...v0.1.0
