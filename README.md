# MagTk's Data Mining Report Template

Suggested report template for Data Mining projects based on the CRISP-DM methodology.

## Contents

This repository currently contains R-based examples.
Additional implementations and examples may be added in future releases.

### R

- `R/report_template.Rmd` – empty report template
- `R/example_report.Rmd` – completed example report
- `R/example_report.html` – rendered example report

### Data

- `data/penguins_mess.csv` – sample dataset used in the examples

## Requirements

The report was developed in R using the following packages:

```r
library(tidyverse)
library(GGally)
library(corrplot)
library(tidymodels)
library(rpart.plot)
library(ranger)
library(vip)
library(viridis)
library(scales)
```

Install missing packages with:

```r
install.packages(c(
  "tidyverse",
  "GGally",
  "corrplot",
  "tidymodels",
  "rpart.plot",
  "ranger",
  "vip",
  "viridis",
  "scales"
))
```



## Purpose

This repository provides a reusable report structure for Data Mining projects and academic assignments.

The template follows the CRISP-DM methodology and may be adapted to specific project requirements.

## License


This work is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0).

You are free to:
- Share — copy and redistribute the material.
- Adapt — remix, transform, and build upon the material.

Under the following terms:
- Attribution — appropriate credit must be given.
- NonCommercial — the material may not be used for commercial purposes.

For details see the LICENSE file.


## Citation

If you use this material in teaching, coursework, research, or derivative works, please cite this repository.

Citation information is available through GitHub's Cite this repository feature and in the CITATION.cff file.

### BibTeX Entry

@software{tkacz2026magtk_dm_template,
  author       = {Tkacz, Magdalena},
  title        = {MagTk's Data Mining Report Template},
  version      = {0.1.0},
  year         = {2026},
  publisher    = {GitHub},
  url          = {https://github.com/magtk/data-mining-report-template}
}



