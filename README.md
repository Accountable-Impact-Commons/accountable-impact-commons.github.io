# accountableimpactcommons.org

Source for the Accountable Impact Commons website, built with [Hugo](https://gohugo.io/) and the PaperMod theme, deployed to GitHub Pages by the workflow in `.github/workflows/hugo.yaml`.

## Local preview

    git submodule update --init --recursive
    hugo server -D

## Writing a post

Add a Markdown file under `content/posts/` with front matter:

    ---
    title: "Post title"
    date: 2026-09-14
    summary: "One-line summary shown in lists."
    tags: []
    ---

Set `draft: true` to keep it out of the published site.

## Licence

This repository follows the licensing set out in section 6 of the
[LF Decentralized Trust Labs charter](https://github.com/LF-Decentralized-Trust-labs/governance).

| What | Licence | File |
|---|---|---|
| Source code: Hugo templates and partials, `hugo.toml`, the deploy workflow, scripts | Apache License 2.0 | [`LICENSE`](LICENSE) |
| Site content: everything under `content/`, meaning the posts and pages | CC BY 4.0 | [`LICENSE-docs`](LICENSE-docs) |

Copyright attribution is recorded in [`NOTICE`](NOTICE). The PaperMod theme is a
git submodule under `themes/PaperMod` and carries its own MIT licence.
