# Tic Tac Toe — Development

This is the active development branch. All new features and fixes are built here before being merged into `master` via a pull request.

## Project Overview

A zero-dependency, single-file browser game built with vanilla HTML, CSS, and JavaScript. No framework, no build step, no package manager — the entire deliverable is one `.html` file.

## Repository Structure

```
tictactoe-game/
├── tictactoe.html   # Complete game (markup, styles, and logic in one file)
├── CHANGELOG.md     # Version history
└── README.md        # This file
```

## Branch Strategy

| Branch | Purpose |
|---|---|
| `master` | Stable, production-ready releases only |
| `development` | Active development; all work lands here first |

Feature branches should be cut from `development` and merged back via pull request:

```
git checkout development
git checkout -b feature/my-feature
# ... make changes ...
git push origin feature/my-feature
# open PR → development
```

## Development Setup

No build tooling is required.

```bash
git clone https://github.com/RF0606/tictactoe-game.git
cd tictactoe-game
git checkout development
# Open tictactoe.html in a browser to test changes live
```

For rapid iteration, use a local dev server with auto-reload (e.g. VS Code Live Server extension or `npx serve .`).

## Versioning

This project follows [Semantic Versioning](https://semver.org/):

- **MAJOR** — breaking changes to game behaviour or file structure
- **MINOR** — new features added in a backwards-compatible way
- **PATCH** — bug fixes and minor visual tweaks

Releases are tagged on `master` (e.g. `v1`, `v1.1`, `v2.0`).

Current release: **v1**

## Release Process

1. All feature work is merged into `development` and tested.
2. A pull request is opened from `development` → `master`.
3. The PR is reviewed and merged.
4. A version tag is applied to the merge commit on `master`.
5. `CHANGELOG.md` is updated on `development` for the next cycle.

## Contributing

1. Branch off `development` using a descriptive name (`feature/`, `fix/`, `chore/`).
2. Keep commits small and focused; write clear commit messages.
3. Test the game manually in at least one browser before opening a PR.
4. Open a pull request into `development` with a description of what changed and why.

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for the full version history.
