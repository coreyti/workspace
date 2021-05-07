---
head: Improve footnoting, part 2 (lists are good again)
---

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Footnotes in (this) Changelog are no longer in a list. That format seems to break GitHub; hopefully this will not.
- And, while we're here, let's experiment[^vNIL-a] with per-release footnotes.
- GitHub really doesn't do Markdown footnotes well, but I find them to be very useful. So:
  - Footnotes should **not** be simple URLs (which GitHub likes just fine).
  - Footnotes **must** have some text content, even if that is simply markup to turn a link into text.
  - The result will be that GitHub does not generate links for the in-line footnote references, but will render those references as text. The actual footnote content will *also* be rendered, which is what we're really trying to achieve.
- Footnotes are back into lists. Now that we're not utilizing GitHub's naïve handling of footnotes, the list formatting seems to work.

### Footnotes

- [^vNIL-a]: Here's a footnote for the current, unrelease work-in-progress.

---

## [0.1.0] - 2021-05-06

### Added

- A project scaffold made up of:
  - A [README](./README.md).
  - A CHANGELOG (this).
  - A "TODO" backlog.
  - Some initial workspace structure and utilities.
- The `ergo-sojourn` utility provides a simple way to move between points in git history. This is neat for things like flipping through the changes in a repository as a sort of time-lapse presentation.

### Changed

- Rename `ws-changes` and `ws-change`: frame things in an active & imperative[^v0.1.0-a] voice.
- Remove Markdown heading characters from generated commit messages. The characters (`#`) are considered as comment markers in git commits, so the lines are excluded from the commit message. And, there's really no need for headings in most commit messages.
- Rename the entire project/concept as "ergonomic" (it was previously named "workspace").
  - This is a nice complement to the spirit of the idea. Ergonomics are about efficiency in the workplace[^v0.1.0-b], from Greek in which "ergo" translates as "work". Latin "ergo" translates as "therefore", which feels appropriate as well, somehow (as in, "I am in this workspace, therefore...").
  - It is also suggested that this template be cloned as "workspace" for a given organization/effort. To that end, I'd like to be able to do the same: clone [`ergonmic`](https://github.com/coreyti/ergonomic) as [`workspace`](https://github.com/coreyti/workspace) in my own account, and use the latter for project work. Here's the mind-blowing moment: it's likely that I'll have my `workspace` be a place within which I work on `ergonomic`, which is how I define my `workspace`.
  - This change also affects occurrences of "workspace" and "ws" in the project. For example, `ws-change` becomes `ergo-change` (a hint at what's to come in terms of tool naming and design).

### Footnotes

- [^v0.1.0-a]: [Article: "A Note About Git Commit Messages"](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
- [^v0.1.0-b]: [Etymology Online: "ergonomics"](https://www.etymonline.com/word/ergonomics#etymonline_v_11569)

