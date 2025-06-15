# The Art of War — LaTeX Edition

This repository contains a complete LaTeX-rendered version of **The Art of War** by **Sun Tzu**, based on the 1910 English translation by Lionel Giles. It includes proper formatting, critical footnotes, commentary, and the full Project Gutenberg license.

## Purpose

This project was created to demonstrate:
- Proficiency in advanced LaTeX (enumerate customization, quote formatting, custom TOC).
- Usage of Git for version control and collaborative academic document management.

## Structure

- `main.tex` — Full LaTeX source file for the typeset book.
- `README.md` — Project description and usage guide.
- `.gitignore` — LaTeX auxiliary files excluded from versioning.
- `output.pdf` — Compiled PDF output of the document (ignored by default).

## Features

- Custom typeset title page, dedication, and table of contents.
- Fully annotated chapters with inline historical commentary.
- Faithful reproduction of Project Gutenberg's license and formatting rules.
- Clean semantic structure using `enumerate`, `quote`, and `\chapter*`.

## How to Compile

You need a LaTeX distribution like **TeX Live** or **MiKTeX**. Then:

```bash
pdflatex main.tex
```
