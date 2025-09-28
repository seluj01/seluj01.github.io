+++
title = "Website"
tags = ["programming", "Markdown"]
+++


# Website using Franklin and github pages

## GitHub
Create a repo for a GitHub Pages, in my case it should be named `seluj01.github.io`.
Clone it locally.

## Franklin.jl
Create a new website using Franklin.jl.
To locally build and display it,
```bash
julia -e 'using Franklin; serve()'
```
To full rebuild,
```bash
julia -e 'using Franklin; optimize()'
```
move everything to the cloned repo, folders `_site`, etc. and file `index.md` should be at the root of the repo.

## GitHub Action
Ensure the site is built using a GitHub Action from file in `.github/workflows` and not by the default Jekyll build from GitHub.\\
On the repo in `settings > Pages > Build and deployment` select `Source: Deploy from a branch` and `Branch: gh-pages` with `/(root)`.
The branch `gh-pages` should be created by the GitHub Action.