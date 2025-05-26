# Git Cheat Sheet

A comprehensive LaTeX-based Git Cheat Sheet containing essential Git commands for developers. This repository includes the LaTeX source code and the compiled PDF version of the cheat sheet, updated as of May 27, 2025.

## Overview

This Git Cheat Sheet provides a quick reference for common Git commands, organized into categories such as:
- Creating Snapshots
- Browsing History
- Branching & Merging (including Git Worktree commands)
- Collaboration
- Rewriting History

It is designed to be a handy resource for both beginner and advanced Git users, with examples and concise explanations.

## Files

- `git_cheatsheet.tex`: The LaTeX source code for the cheat sheet.
- `git_cheatsheet.pdf`: The compiled PDF version of the cheat sheet.

## Installation

You can compile the LaTeX source code either locally or using Overleaf, an online LaTeX editor.

### Option 1: Compile Locally
Ensure you have the following dependencies installed:

- A LaTeX distribution (e.g., TeX Live or MiKTeX)
- Packages: `inputenc`, `fontenc`, `lmodern`, `geometry`, `hyperref`, `titling`, `tocloft`, `enumitem`, `parskip`, `xcolor`, `verbatim`, `fancyhdr` (all included in a full TeX Live installation)

#### Steps to Compile Locally
1. Clone the repository:
   ```
   git clone https://github.com/KarimmYasser/git_cheatsheet.git
   cd git_cheatsheet
   ```
2. Compile the LaTeX file using `latexmk` (recommended) or `pdflatex`:
   ```
   latexmk git_cheatsheet.tex
   ```
   or
   ```
   pdflatex git_cheatsheet.tex
   ```
3. The resulting PDF (`git_cheatsheet.pdf`) will be generated in the same directory.

### Option 2: Compile Using Overleaf
1. Clone or download the repository:
   ```
   git clone https://github.com/KarimmYasser/git_cheatsheet.git
   ```
2. Go to [Overleaf](https://www.overleaf.com/) and create a new project.
3. Upload the `git_cheatsheet.tex` file to your Overleaf project.
4. Overleaf will automatically compile the LaTeX code, and you can view or download the resulting `git_cheatsheet.pdf`.

## Usage

- Open `git_cheatsheet.pdf` to view the cheat sheet.
- Edit `git_cheatsheet.tex` to add or modify commands, then recompile (locally or on Overleaf) to generate an updated PDF.
- Use the cheat sheet as a reference for Git workflows, including managing branches, resolving conflicts, and syncing with remote repositories.

## Contributing

Feel free to contribute by submitting pull requests or issues:
- Add new Git commands or sections.
- Improve formatting or examples.
- Report bugs or suggest enhancements.

## Acknowledgements

- Created by Karim Yasser.
- Inspired by the need for a concise, printable Git reference.
