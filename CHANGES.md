# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.4.0] - 2023-04-21

### Added

- This CHANGELOG file.

### Changed

- Rewrote the .dtx file to use the  document class ``l3doc`` instead of ``ltxdoc``.

### Removed
- Unnecessary ``\str_use`` calls.

## [0.3.0] - 2023-04-18

### Added

- ``\PackageError``'s to abort loading the package when the ``expl3`` or ``LaTeX`` format is too old.

## [0.2.0] - 2023-04-07

### Added

- Manually ``\Require``'d the packages ``expl3`` and ``xparse`` for users
of older ``LaTeX`` installations. 
- Added ``__UsedOn_``-guards (as per ``LaTeX3`` convention) to the macros ``\origlabel``, ``\origcref``, and ``\origCref`` to prevent them from leaking.

### Changed

- Used internal ``doc`` macro ``\pkg`` instead of my own ``\package``. 

## [0.1.0] - 2023-03-29

### Added

- Initial version of ``cleveref-used`` package.

[unreleased]: https://github.com/SvenPistre/cleveref-usedon/compare/v0.4.0...HEAD
[0.4.0]: https://github.com/SvenPistre/cleveref-usedon/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/SvenPistre/cleveref-usedon/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/SvenPistre/cleveref-usedon/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/SvenPistre/cleveref-usedon/releases/tag/v0.1.0