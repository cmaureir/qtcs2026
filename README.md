# Qt Contributors' Summit 2026

Slides for the talk:

> Programming languages in the Qt Ecosystem: beyond Qt Bridges

Built with [reveal.js](https://revealjs.com) (git submodule). Deployed by
`.github/workflows/deploy.yml` (GitHub Pages) or `.gitlab-ci.yml` (GitLab Pages),
whichever host the repository ends up on; delete the other one.

## Running it locally

```sh
git submodule update --init --recursive
python -m http.server 8000   # then open http://localhost:8000
```

## Talk structure

| Section                                                    | Budget |
| ---------------------------------------------------------- | ------ |
| Framing: where Qt Bridges stands                           | 3 min  |
| Signals, incl. Python's playbook applied to Qt's own tools | 9 min  |
| Five doors into Qt                                         | 6 min  |
| What if moc goes away? (C++26 reflection)                  | 6 min  |
| Language watch: Swift (qt-swift), Zig, Gleam, Carbon, Mojo and MLIR, V, Odin, Goose | 14 min |
| Scorecard and opportunities                                | 6 min  |
| Discussion                                                 | open   |

That is about 45 minutes of material: cut the long tail, the Go/Nim snippets or
the MLIR section for a shorter slot.

Facts to re-check before presenting (all moving targets): Zig 0.16 (April
2026), Gleam version, Mojo 1.0 (August 2026) and its licence, Carbon status,
GCC 16 reflection support and whether Clang/MSVC have caught up, the
qt-swift README (Swift 6.4+, no QObject/signals yet), reflect-moc limits, V 1.0
status, and the Goose README.
