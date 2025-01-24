# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/).
Versioning is done using [Calendar Versioning](https://calver.org/).

## [2025-01-24]

### Changed

- Refined `README.md`
- Refined `.gitignore`

## [2025-01-20]

### Added

- Added `.aspell.en.pws` and `.aspell.conf` to ignore some LaTeX commands at aspell.
- Added `latexindent` to GitHub actions (`check.yml`).
- When using lualatex: Added support for [spelling](https://www.ctan.org/pkg/spelling) package (which highlights bad spellings in red - if `.spell.bad` containing misspelled words exists)

### Fixed

- Fixed tag for iot Docker image.

### Changed

- Refined `Makefile`

## 2025-01-14

First public release.
<!-- markdownlint-disable-file MD024 MD033 -->

[2025-01-24]: https://github.com/latextemplates/LNCS/compare/2025-01-20...2025-01-24
[2025-01-20]: https://github.com/latextemplates/ACM/compare/2025-01-14...2025-01-20
