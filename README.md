# Quarto TWRI revealjs theme

[![quarto-ext-chk](https://github.com/TxWRI/quarto-revealjs-txwri/actions/workflows/check-template.yaml/badge.svg)](https://github.com/TxWRI/quarto-revealjs-txwri/actions/workflows/check-template.yaml)

A minimal presentation theme for the institute.

![](template.gif){width=40%}

## Use

```bash
quarto install extension txwri/quarto-revealjs-txwri
```

or use the following to copy the template files to a new working directory (reccomended for your first time using the template)

```bash
quarto use template txwri/quarto-revealjs-txwri
```

This template is based largely on the Quarto ['clean' template](https://github.com/grantmcdermott/quarto-revealjs-clean).

The R scripts included in the template require the following R packages:
dplyr, ggplot2, gt, knitr, ragg, rmarkdown, scico, stringr, tidyr

You do not necessarily need these packages if you are not rendering the examples in the template.
You *will* need [quarto v1.3.0](https://quarto.org/docs/get-started/) or greater installed on your system.


## Changelog

- v1.0.0

Initial release.
