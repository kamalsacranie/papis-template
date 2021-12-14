# Research Essay Template

This is the general template I use to write my research essays using single
document bookdown format for R.

## General

- Essay is written in the `.rmd` file and then rendered using RStudio or an R
  Rscript
- The `.rmd` has my sane defaults for a research essay and there are more sane
  $LaTeX$ defaults in `preable.tex`

## Referencing

- We use `papis` to manage references and output them to `sources.bib`
- `library/` is the library that is setup for `papis` to use to store your
  database
- `apa.csl` is our sane default citation style
