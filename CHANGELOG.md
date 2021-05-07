---
head: Rename as "ergonomic"
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
- Rename the entire project/concept as "ergonomic" (it was previously named "workspace").
  - This is a nice complement to the spirit of the idea. Ergonomics are about efficiency in the workplace[^vNIL-b], from Greek in which "ergo" translates as "work". Latin "ergo" translates as "therefore", which feels appropriate as well, somehow (as in, "I am in this workspace, therefore...").
  - It is also suggested that this template be cloned as "workspace" for a given organization/effort. To that end, I'd like to be able to do the same: clone [`ergonmic`](https://github.com/coreyti/ergonomic) as [`workspace`](https://github.com/coreyti/workspace) in my own account, and use the latter for project work. Here's the mind-blowing moment: it's likely that I'll have my `workspace` be a place within which I work on `ergonomic`, which is how I define my `workspace`.
  - This change also affects occurrences of "workspace" and "ws" in the project. For example, `ws-change` becomes `ergo-change` (a hint at what's to come in terms of tool naming and design).

### Footnotes

- [^vNIL-a]: https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html

- [^vNIL-b]: https://www.etymonline.com/word/ergonomics#etymonline_v_11569

