# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [unreleased]

## [1.4.0] 2019-03-12
### Added
  - `git changed` to show all changed files
  - `git staged` to show all staged files
## Changed
  - `git version` now creates an annotated tag

## [1.3.0] 2019-03-11
### Added
  - `git untracked` to list untracked files
### Changed
  - `git ignore` now allows to .gitignore to be in a subdirectory
  - `git ignore` now does an exact match to determine if a file/directory is already ignored

## [1.2.1] 2019-03-10
### Changed
  - `git ignore` only adds a line if it doesn't already exist

## [1.2.0] 2019-03-08
### Added
  - `git ignore` command to update .gitignore file

## [1.1.1] 2019-02-10
### Changed
  - In no tags exists default to a 0.0.0 starting point

## [1.1.0] 2019-02-09
### Changed
  - If no args are passed it just echos the current version
### Removed
  - Old debugging echo

## [1.0.0]
### Added
- Working

[unreleased]: https://github.com/eidsonator/fish-git/compare/1.3.0...master
[1.3.0]: https://github.com/eidsonator/fish-git/compare/1.2.1...1.3.0
[1.2.1]: https://github.com/eidsonator/fish-git/compare/1.2.0...1.2.1
[1.2.0]: https://github.com/eidsonator/fish-git/compare/1.1.1...1.2.0
[1.1.1]: https://github.com/eidsonator/fish-git/compare/1.1.0...1.1.1
[1.1.0]: https://github.com/eidsonator/fish-git/compare/1.0.0...1.1.0


