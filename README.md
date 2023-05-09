# README

## Fidelity tutorial

Tutorial and additional information to the paper “The unrecognized role
of fidelity in effectiveness-implementation hybrid trials: simulation
study and guidance for implementation researchers”, by Trutschel et
al. (2023): https://doi.org/10.21203/rs.3.rs-2219404/v1 .

<details>

## How to work on this repo?

1)  Clone the repo

2)  Open the file `fidelity-tutorial.Rproj`

3)  Install the following packages - they are needed for the following
    steps to work:

    `install.packages(c("renv", "quarto"))`

    3b) you also need to install quarto (i.e. a next-generation
    Rmarkdown-application). The newest version of RStudio comes bundled
    with quarto 1.0.36 (you can run `quarto check` in a Terminal (not
    the console)) or you can download the newest quarto version here:  
    https://quarto.org/docs/download/

4)  Call `renv::restore()` to initiate a local isolated project-library
    (to ensure everyone works with the same packages and versions).

5)  The tutorial is patched-together according to info in the
    `_quarto.yml` -file. Addition or deletion of chapters are signaled
    there.

6)  Call `quarto render` in a Terminal to render and `quarto preview`to
    get a preview of the book.

7)  Save, commit, and push to remote!

8)  If you have installed additional packages, call `renv::snapshot()`
    to add these to the lockfile, so that others can do 4) on their
    machines and have the same packages and versions as you do. Thanks!

\</details)
