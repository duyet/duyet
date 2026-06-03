# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

GitHub profile README for `duyet/duyet`. Not a software project — contains only Markdown and GitHub Actions YAML. No build system, package manager, or application code.

## Auto-managed content

The `<!-- BLOG-POST-LIST:START -->` … `<!-- BLOG-POST-LIST:END -->` block in `README.md` is updated hourly by the `blog-post-workflow` GitHub Action. Do not manually edit content inside these markers — it will be overwritten on the next workflow run.

## Duplicate workflow file

The active workflow is `.github/workflows/blog-post-workflow.yml`. There is a stale copy at `.github/blog-post-workflow.yml` (not inside `workflows/`) that GitHub Actions ignores — do not edit it thinking it's the active one.

## Commit conventions

- `chore: update from latest post` — auto-commits from the blog-post-workflow (committer: `duyetbot`)
- `chore(deps): ...` — Renovate bot dependency updates
- Manual edits use `Update README.md` or semantic prefixes
