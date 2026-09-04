# Atomic Physics for Everyone

This repository contains a MyST Markdown edition of *Atomic Physics for
Everyone: An Introduction to Atomic Physics, Quantum Mechanics, and Precision
Spectroscopy with No College-Level Prerequisites* by Will Raven. The MyST
book is the primary edition maintained here: its configuration, chapters,
appendices, and figure assets all live at the repository root.

The original book was published by Springer in 2025 and is available as an
open-access work at
[doi:10.1007/978-3-031-69507-0](https://doi.org/10.1007/978-3-031-69507-0).
This rendition preserves the book's prose, equations, figures, worked
examples, problems, and chapter structure in an accessible web-native format.

## Read and edit the MyST edition

The main entry points are:

- [`myst.yml`](myst.yml) — project metadata and table of contents
- [`index.md`](index.md) — book landing page
- [`chapters/`](chapters/) — the converted chapters and appendices
- [`images/`](images/) — EPUB-derived chapter figures

## Build

```bash
npm install
npm run start          # preview
npm run build          # static site in _build/html/
```

CI runs on pull requests (`.github/workflows/ci.yml`); pushes to `main`
deploy via [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).

## Live site

https://quadriviumpress.github.io/AtomicPhysicsForEveryone/
