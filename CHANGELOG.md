# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
And the commit messages from [Conventional Commits](https://conventionalcommits.org) are being used.

## [1.0.1] - 2025-03-08

### Changed

- Updated dependencies

## [1.0.0] - 2021-11-10

### Added

- npmignore: further files to ignore on npm publishing
- npm: `postinstall` for mentioning some aspects after installation

### Changed

- optimized testing scripts

## [1.0.0-beta.0] - 2021-11-10

### Added

- Changelog

### Fixed

- Node lower version 15 compatibility: Using an older method regarding the introduced `safePluginName` constant from the last release

## [1.0.0-beta] - 2021-11-09

### Added

- QA: CodeQL and super-linter
- `np` for releases

### Changed

- improvement: patternlab 5 compatibility [#16](https://github.com/bmuenzenmeyer/plugin-node-uiextension/issues/16)
- updated some occurances of `styleguidekit` to `UIKit`
- updating `lodash` and `eslint` dependencies
- chore: fixed some `eslint` feedback
- stylesheets path should get defined agnostic to the plugins folder [#7](https://github.com/mfranzke/plugin-node-uiextension/pull/7)

### Fixed

- "Uncaught ReferenceError: $ is not defined" [#14](https://github.com/bmuenzenmeyer/plugin-node-uiextension/issues/14)
- docs: patternlab.io link
