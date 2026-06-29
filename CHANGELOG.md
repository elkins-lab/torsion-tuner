# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.3] - 2026-06-29

### Added
- Added API documentation pages for `export.py`, `psvs_parser.py`, and `train.py`.

### Fixed
- Fixed strict type annotations across the test suite for `mypy` compatibility.
- Fixed an unused loop variable in `examples/multi_modal_refinement.ipynb`.
- Excluded `synth_nmr` from `mypy` missing imports checking.

## [0.1.2] - 2026-06-07

### Security
- Removed compromised `polyfill.io` CDN script from MkDocs configuration to resolve supply-chain vulnerability.
