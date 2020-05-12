# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.0.1] - 2020-05-12

## Changed
* Assume that file names are in format YYYYMMDDHHMM.* (e.g., 202005121111.md)
* Support wiki-style links in notes (e.g., "[[202005121111 A description]]")
* Get note title from YAML header (e.g., title: A note title) instead of from
file name

## [1.3.0] - 2019-08-10

### New
* Add options to not include external links, and self references (#16)
* Add screenshot and tags to README (#15)

### Changed
* Use the Black formatter on the whole codebase

## [1.2.0] - 2019-08-06

### New

* ENH: Add the `--use-graphviz` option to use Graphviz to draw the network (#13)

## [1.1.0] - 2019-07-01

### Changed
FIX: Use faster layout algorithm for large networks (#8)

### Fixed
ENH: Allow different, and multiple file patterns (#6)
DOC: Fix twine instructions to upload to PyPI

## [1.0.0] - 2019-06-17

First version of zkviz


[Unreleased]: https://github.com/Zettelkasten-Method/zkviz/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/Zettelkasten-Method/zkviz/compare/04d473f...v1.0.0
[1.1.0]: https://github.com/Zettelkasten-Method/zkviz/compare/v1.0.0...v1.1.0
[1.2.0]: https://github.com/Zettelkasten-Method/zkviz/compare/v1.1.0...v1.2.0
[1.3.0]: https://github.com/Zettelkasten-Method/zkviz/compare/v1.2.0...v1.3.0
