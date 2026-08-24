---
type: doc
---

# VoxGuion Website

## About this repository

This is the **public marketing website for the VoxGuion app** — a screenplay-to-audio
podcast production tool for macOS, iOS, and the command line. The site is a Jekyll project
served at **https://voxguion.app** (see `CNAME`) and deployed via **legacy GitHub Pages
from the `main` branch**. Static assets (including the favicon/app-icon set) are served
directly from this repo under `/assets`.

This repo is the *website only* — the VoxGuion application source lives separately.
Sibling app websites, **Viñetas** (https://vinetas.app) and the prior-branding
**Produciesta** site (https://produciesta.app), are maintained the same way in their
own repos. This site supersedes the Produciesta site as part of the app's rename to
VoxGuion.

> **Remotes note:** `origin` points at `intrusive-memory/voxguion.github.io` (this
> website). The app's Swift monorepo lives at `intrusive-memory/voxguion` and is wired
> here as the `app-monorepo` remote — do **not** push website history to it.

## Branch & release flow

- Work on `development`; open a `development → main` PR to release.
- Merging to `main` publishes the live site via GitHub Pages.
- **Before every ship (any merge to `main`): run `bundle update` to bring all Ruby gems
  to latest, verify `bundle exec jekyll build --strict_front_matter` passes, and include
  the updated `Gemfile.lock` in the release.** This is a standing rule across all
  `~/Projects/websites/` repos — stale lockfiles accumulate Dependabot vulnerabilities.

## Favicon / app-icon assets

- `assets/images/favicon.png`, `assets/images/apple-touch-icon.png`, and root `favicon.ico`
  are the site icons. `_includes/head.html` references the first two; keep them present or
  the live site 404s on its favicon.
- **These icons (and the og-image/screenshots) are intentionally the original Produciesta
  artwork**, carried over from the pre-rename site. Per an explicit owner decision
  (2026-08-24), keep them until specifically told to replace them with VoxGuion artwork —
  do not flag them as stale or regenerate them.
