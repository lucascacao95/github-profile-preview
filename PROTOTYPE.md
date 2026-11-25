# Profile prototype

This repository is a standalone preview of a proposed GitHub profile README. It does not activate a profile README or update the account bio.

## Proposed bio

> Software engineer working on complex business systems. Building personal tools for photography, reading, and everyday life.

## Visual direction

Two project covers share the same proportions and typography scale. Chapter uses a muted green palette and a serif title; Roll uses a warm palette and a simple wordmark. Both show actual product interfaces. Descriptions, links, technologies, and project status remain accessible text beneath the images.

The layout uses a plain HTML table supported by GitHub Markdown. It follows GitHub's own light/dark styling; the covers intentionally retain their product colors. Narrow screens may scroll the two-column table horizontally.

## Image provenance

- **Chapter:** captured from the public application at commit `a1fa98de08153c38d532b97ff676ceb2b0e8cb35`, running locally in an isolated copy with a fresh SQLite database. The reader and all six book records are fictional. The application UI remains in its original Brazilian Portuguese. The capture does not use a personal library, real book covers, or private account data.
- **Roll:** the existing [public demonstration capture](https://github.com/lucascacao95/roll/blob/main/docs/screenshots/import-light.png), from the project at commit `942bc5f8717a8ac4dfe488451669f2e5cbffa943`. Its demo photographs are generated illustrations. Roll's code and artwork are MIT licensed; see [the source license](https://github.com/lucascacao95/roll/blob/main/LICENSE). The cover shows a cropped detail, without altering the application UI.
- **Cover composition:** original HTML/CSS in [design/covers.html](design/covers.html), rendered to 1200 × 900 PNGs using Chromium. Source screenshots are retained under `assets/source/`.

No private context document is included in this repository.

## Applying the design later

After review, copy `README.md` and `assets/` to the public repository named exactly `lucascacao95/lucascacao95`. Updating the account bio is a separate action. This preview does not change project descriptions, topics, pinned repositories, or repository visibility.
