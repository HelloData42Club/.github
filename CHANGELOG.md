# Changelog

All notable changes for a project are documented in this file.

For your understanding please look to [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), to understand the use of a changelog, 
[Semantic Versioning](https://semver.org/spec/v2.0.0.html) and [Versioning policy](#versioning-policy) below to get a better understanding of versioning.

## [Unreleased]

<!-- Each change must be put in here in a reverse chronological order. -->

<!-- Here is an exemple for a PR :

2026-01-01  Lohann Coant--Verdier  <mymail@mail.com>

Added the changelog template for the contributors
-->

### Added
- Subject for module 03 (SQL), exercises 00 to 02.

### Changed
- Exercise 01 of module 01 now uses a cleaner dataset.

### Fixed
- Typo in the module 01 subject.

## [1.0.0] - 2026-11-15

First public edition of the project.

<!-- Here lay all the previous version -->
[Unreleased]: https://github.com/HelloData42Club/<repo>/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/HelloData42Club/<repo>/releases/tag/v1.0.0

---

## Versioning policy

Version numbers follow `MAJOR.MINOR.PATCH`:

| Part | Incremented when | Example |
|---|---|---|
| **MAJOR** | New edition, or a restructuring that breaks the previous curriculum | `2.0.0` for the 2027 edition |
| **MINOR** | A new module or exercise is added, backwards compatible | `1.1.0` adds module 03 |
| **PATCH** | A fix: typo, broken link, clearer wording, corrected dataset | `1.0.1` |

## How to update this file

- Add an entry under `[Unreleased]` **in the same pull request** as the change.
- Write for participants and organizers, not for developers: describe the effect, not the implementation.
- Use one of these categories: `Added`, `Changed`, `Deprecated`, `Removed`, `Fixed`, `Security`.
- On release, rename `[Unreleased]` to the new version with its date (`YYYY-MM-DD`), create a fresh empty `[Unreleased]` section, and update the links at the bottom.
