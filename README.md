# Inventory of Climate Emotions (ICE) and mental wellbeing

This repository contains supplementary materials (data and code) associated with the manuscript inspecting emotional responses to climate change as predictors of mental wellbeing. The remaining supplementary materials can be found on the accompanying [OSF website](https://osf.io/scqyf/).

Please cite the corresponding publication when using these materials:

> Marczak, M., Budziszewska, M., Wierzba, M., Fußwinkel, S., Zaremba, D., Michałowski, J., Marchewka A., & Klöckner, C.A. (2023) *Inspecting diverse emotional responses to climate change as predictors of mental wellbeing. The key role of positive emotions and anxiety.* PsyArXiv.

## Contents

This repository contains [raw](https://github.com/nencki-lobi/ICE-wellbeing/tree/main/01/input) and [cleaned](https://github.com/nencki-lobi/ICE-wellbeing/tree/main/02/output) data collected in the course of the study. Morover, we share data analysis code, as well final [HTML report](https://github.com/nencki-lobi/ICE-wellbeing/tree/main/ICE_wellbeing.html).

## How to use

To reproduce the analyses described in the manuscript, run:

```
rmarkdown::render("ICE_wellbeing.Rmd", output_file = "ICE_wellbeing.html")
```

## Requirements

The following R packages are required: `BetterReg`, `boot`, `car`, `lm.beta`, `openxlsx`, `psych`, `rgl`, `simpleboot`, `tidyverse`.

Optional, but useful for working with PostgreSQL databases: `RPostgreSQL`.

## Contact information:

If you would like to use Inventory of Climate Emotions (ICE) in your research please contact Michalina Marczak (michalina.marczak@ntnu.no).

Any problems or concerns regarding this repository should be reported to Małgorzata Wierzba (m.wierzba@nencki.edu.pl).
