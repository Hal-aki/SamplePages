# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

SamplePages is a minimal sample repository for a GitHub Pages site. It currently contains only Markdown content:

- `README.md` — repository title only
- `index.md` — the site's top page (currently empty), rendered by GitHub Pages

The git history shows the site originally used `index.html`, which was intentionally replaced with `index.md` ("mdファイルに変更"). Prefer Markdown files for page content rather than reintroducing raw HTML, unless asked.

## Development

There is no build system, package manager, linter, or test suite. Pages are plain Markdown; GitHub Pages (Jekyll) renders them on push. Changes can be verified simply by reviewing the Markdown — there are no commands to run.

## Conventions

- The default working branch is `develop` (there is no `main`/`master`).
- Commit messages have historically been written in Japanese (e.g. "index md追加"); short messages in either Japanese or English are fine.
