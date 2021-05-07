---
head: Improve change saving exec and result
---

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- A project scaffold made up of:
  - A [README](./README.md).
  - A CHANGELOG (this).
  - A "TODO" backlog.
  - Some initial workspace structure and utilities.

### Changed

- Rename `ws-changes` and `ws-change`: frame things in an active & imperative[^vNIL-a] voice.
- Remove Markdown heading characters from generated commit messages. The characters (`#`) are considered as comment markers in git commits, so the lines are excluded from the commit message. And, there's really no need for headings in most commit messages.

### Footnotes

- [^vNIL-a]: https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html

