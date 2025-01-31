# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/).
Versioning is done using [Calendar Versioning](https://calver.org/).

## [2025-01-31]

### Changed

- Renamed to `acm-enhanced` to show that this is an enhanced version of [acmart](https://ctan.org/pkg/acmart).

### Added

- Added `commands.tex` to collects all LaTeX macros / commands for a better overview on available (custom) LaTeX commands.

## [2025-01-25]

### Added

- Added [TeXcount](https://app.uio.no/ifi/texcount/index.html) to GitHub workflow summary.
- GitHub workflow job summary for `latexmk` generated using [texlogsieve](https://ctan.org/pkg/texlogsieve).

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

[2025-01-31]: https://github.com/latextemplates/ACM/compare/2025-01-25...2025-01-31
[2025-01-25]: https://github.com/latextemplates/ACM/compare/2025-01-20...2025-01-25
[2025-01-20]: https://github.com/latextemplates/ACM/compare/2025-01-14...2025-01-20
