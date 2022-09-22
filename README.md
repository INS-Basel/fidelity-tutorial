README
================

## Fidelity tutorial

Tutorial and additional information to \[name of paper\]

## How to work on this repo?

1)  Clone the repo

2)  Open the file `fidelity-tutorial.Rproj`

3)  Install the following packages - they are needed for the following
    steps to work:

    `install.packages(c("renv", "quarto"))`

3b) you also need to install quarto (i.e. a next-generation
Rmarkdown-application). RStudio come bundled with quarto 1.0.36 (you can
run `quarto check` in a Terminal (not the console)) or you can download
the newest version here:  
https://quarto.org/docs/download/

4)  Call `renv::restore()` to initiate a local isolated project-library
    (to ensure everyone works with the same packages and versions).

5)  The tutorial is patched-together according to info in the
    `_quarto.yml` -file. Addition or delecion of chapters are signaled
    there.

6)  Call quarto render to get a preview of the book.

7)  Save, commit, and push to remote!
