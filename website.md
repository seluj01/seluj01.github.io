+++
title = "Website"
tags = ["programming", "Markdown"]
+++


# Website using Franklin and github pages

## Github
Create a repo for a github pages, in my case it should be named `seluj01.github.io`.
Clone it locally.

## Franklin.jl
Create a new website using Franklin.jl.
To build and display it,
```bash
julia -e 'using Franklin; serve()'
```
To full rebuild,
```bash
julia -e 'using Franklin; optimize()'
```