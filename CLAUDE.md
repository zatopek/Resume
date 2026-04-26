# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal resume written in LaTeX. Single-file project (`resume.tex`) using standard LaTeX packages — no custom document classes.

## Build

Compile the PDF with:

```bash
xelatex resume.tex
```

Or via Docker (no local TeX installation needed):

```bash
docker run --rm --user $(id -u):$(id -g) -i -w "/doc" -v "$PWD":/doc thomasweise/texlive xelatex resume.tex
```

The CI workflow (`.github/workflows/main.yml`) uses `texlive/texlive:latest` and runs `make`.

## Structure

- `resume.tex` — the entire resume; all content and formatting in one file
- `GautamVelpula.pdf` — compiled output checked into the repo

## LaTeX Details

Uses `article` class (11pt) with these packages: `geometry` (0.75in margins), `enumitem`, `hyperref`, `titlesec`. No BibTeX, no custom class files, no FontAwesome/XeLaTeX-specific fonts — compiles with `xelatex` or `pdflatex`.
