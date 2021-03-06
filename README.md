
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Reproducibility in Plant Pathology

![Publish
Docker](https://github.com/openplantpathology/Reproducibility_in_Plant_Pathology/workflows/Publish%20Docker/badge.svg)
[![DOI](https://zenodo.org/badge/62676177.svg)](https://zenodo.org/badge/latestdoi/62676177)
[![Project Status: Active – The project has reached a stable, usable
state and is being actively
developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)

This repository contains the data and code for our paper:

> Sparks, A.H., Del Ponte, E.M., dos Santos Alves, K., Foster, Z.,
> Grünwald, N. (YYYY). *Title of paper*. Name of journal/book
> <https://doi.org/xxx/xxx>

Our pre-print is online here:

> Authors, (YYYY). *Title of paper*. Name of journal/book, Accessed 17
> Jul 2020. Online at <https://doi.org/xxx/xxx>

### How to cite

Please cite this compendium as:

> Sparks, A.H., Del Ponte, E.M., dos Santos Alves, K., Foster, Z.,
> Grünwald, N. (2020). *Compendium of R code and data for ‘Status and
> Best Practices for Reproducible Research In Plant Pathology’*.
> Accessed 17 Jul 2020. Online at
> <https://doi.org/10.5281/zenodo.1250665>

### How to download or install

#### The R package

This repository is organized as an R package. There are custom R
functions, `table_of_journals()` and `workflow_dia()` that are used in
this repository, along with a bibliography file of the articles that
were examined and the notes that are located in `inst/extdata`
directory. We have used the R package structure to help manage
dependencies, to take advantage of continuous integration for automated
code testing and for file organisation.

You can download the compendium as a zip from from this URL:
<https://github.com/openplantpathology/Reproducibility_in_Plant_Pathology/archive/master.zip>

Or you can install this compendium as an R package,
Reproducibility.in.Plant.Pathology, from GitHub with:

``` r
if (!require("remotes"))
  install.packages("remotes")
remotes::install_github("openplantpathology/Reproducibility_in_Plant_Pathology"
)
```

Once the download is complete, open the
`Reproducibility_in_Plant_Pathology.Rproj` in RStudio to begin working
with the package and compendium files.

## Meta

Code: [MIT](http://opensource.org/licenses/MIT) year: 2020, copyright
holder: Adam H Sparks

Data: [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

Adam H Sparks, Associate Professor, Centre for Crop Health  
University of Southern Queensland  
Toowoomba, Queensland 4350

\+61 (7) 4631 1948 <adam.sparks@usq.edu.au>

<https://adamhsparks.com/>
