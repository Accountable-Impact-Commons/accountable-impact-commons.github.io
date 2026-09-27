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
