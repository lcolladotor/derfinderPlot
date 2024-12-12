
<!-- README.md is generated from README.Rmd. Please edit that file -->

# derfinderPlot

<!-- badges: start -->

[![Lifecycle:
stable](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://lifecycle.r-lib.org/articles/stages.html#stable)
[![Bioc release
status](http://www.bioconductor.org/shields/build/release/bioc/derfinderPlot.svg)](https://bioconductor.org/checkResults/release/bioc-LATEST/derfinderPlot)
[![Bioc devel
status](http://www.bioconductor.org/shields/build/devel/bioc/derfinderPlot.svg)](https://bioconductor.org/checkResults/devel/bioc-LATEST/derfinderPlot)
[![Bioc downloads
rank](https://bioconductor.org/shields/downloads/release/derfinderPlot.svg)](http://bioconductor.org/packages/stats/bioc/derfinderPlot/)
[![Bioc
support](https://bioconductor.org/shields/posts/derfinderPlot.svg)](https://support.bioconductor.org/tag/derfinderPlot)
[![Bioc
history](https://bioconductor.org/shields/years-in-bioc/derfinderPlot.svg)](https://bioconductor.org/packages/release/bioc/html/derfinderPlot.html#since)
[![Bioc last
commit](https://bioconductor.org/shields/lastcommit/devel/bioc/derfinderPlot.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/derfinderPlot/)
[![Bioc
dependencies](https://bioconductor.org/shields/dependencies/release/derfinderPlot.svg)](https://bioconductor.org/packages/release/bioc/html/derfinderPlot.html#since)
[![Codecov test
coverage](https://codecov.io/gh/leekgroup/derfinderPlot/branch/devel/graph/badge.svg)](https://codecov.io/gh/leekgroup/derfinderPlot?branch=devel)
[![R build
status](https://github.com/leekgroup/derfinderPlot/actions/workflows/check-bioc.yml/badge.svg)](https://github.com/leekgroup/derfinderPlot/actions/workflows/check-bioc.yml)
[![GitHub
issues](https://img.shields.io/github/issues/leekgroup/derfinderPlot)](https://github.com/leekgroup/derfinderPlot/issues)
[![GitHub
pulls](https://img.shields.io/github/issues-pr/leekgroup/derfinderPlot)](https://github.com/leekgroup/derfinderPlot/pulls)
<!-- badges: end -->

Addon package with plotting functions for
[derfinder](http://www.bioconductor.org/packages/derfinder) results.

## Documentation

For more information about `derfinderPlot` check the vignettes [through
Bioconductor](http://bioconductor.org/packages/derfinderPlot) or at the
[documentation website](http://leekgroup.github.io/derfinderPlot).

## Installation instructions

Get the latest stable `R` release from
[CRAN](http://cran.r-project.org/). Then install `derfinderPlot` from
[Bioconductor](http://bioconductor.org/) using the following code:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE)) {
    install.packages("BiocManager")
}

BiocManager::install("derfinderPlot")
```

## Citation

Below is the citation output from using `citation('derfinderPlot')` in
R. Please run this yourself to check for any updates on how to cite
**derfinderPlot**.

``` r
print(citation("derfinderPlot"), bibtex = TRUE)
#> To cite package 'derfinderPlot' in publications use:
#> 
#>   Collado-Torres L, Jaffe AE, Leek JT (2017). _derfinderPlot: Plotting
#>   functions for derfinder_. doi:10.18129/B9.bioc.derfinderPlot
#>   <https://doi.org/10.18129/B9.bioc.derfinderPlot>,
#>   https://github.com/leekgroup/derfinderPlot - R package version
#>   1.35.0, <http://www.bioconductor.org/packages/derfinderPlot>.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {derfinderPlot: Plotting functions for derfinder},
#>     author = {Leonardo Collado-Torres and Andrew E. Jaffe and Jeffrey T. Leek},
#>     year = {2017},
#>     url = {http://www.bioconductor.org/packages/derfinderPlot},
#>     note = {https://github.com/leekgroup/derfinderPlot - R package version 1.35.0},
#>     doi = {10.18129/B9.bioc.derfinderPlot},
#>   }
#> 
#>   Collado-Torres L, Nellore A, Frazee AC, Wilks C, Love MI, Langmead B,
#>   Irizarry RA, Leek JT, Jaffe AE (2017). "Flexible expressed region
#>   analysis for RNA-seq with derfinder." _Nucl. Acids Res._.
#>   doi:10.1093/nar/gkw852 <https://doi.org/10.1093/nar/gkw852>,
#>   <http://nar.oxfordjournals.org/content/early/2016/09/29/nar.gkw852>.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Article{,
#>     title = {Flexible expressed region analysis for RNA-seq with derfinder},
#>     author = {Leonardo Collado-Torres and Abhinav Nellore and Alyssa C. Frazee and Christopher Wilks and Michael I. Love and Ben Langmead and Rafael A. Irizarry and Jeffrey T. Leek and Andrew E. Jaffe},
#>     year = {2017},
#>     journal = {Nucl. Acids Res.},
#>     doi = {10.1093/nar/gkw852},
#>     url = {http://nar.oxfordjournals.org/content/early/2016/09/29/nar.gkw852},
#>   }
```

Please note that the `derfinderPlot` was only made possible thanks to
many other R and bioinformatics software authors, which are cited either
in the vignettes and/or the paper(s) describing this package.

## Code of Conduct

Please note that the derfinderPlot project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.

## Development tools

- Continuous code testing is possible thanks to [GitHub
  actions](https://www.tidyverse.org/blog/2020/04/usethis-1-6-0/)
  through *[usethis](https://CRAN.R-project.org/package=usethis)*,
  *[remotes](https://CRAN.R-project.org/package=remotes)*,
  *[sysreqs](https://github.com/r-hub/sysreqs)* and
  *[rcmdcheck](https://CRAN.R-project.org/package=rcmdcheck)* customized
  to use [Bioconductor’s docker
  containers](https://www.bioconductor.org/help/docker/) and
  *[BiocCheck](https://bioconductor.org/packages/3.17/BiocCheck)*.
- Code coverage assessment is possible thanks to
  [codecov](https://codecov.io/gh) and
  *[covr](https://CRAN.R-project.org/package=covr)*.
- The [documentation website](http://leekgroup.github.io/derfinderPlot)
  is automatically updated thanks to
  *[pkgdown](https://CRAN.R-project.org/package=pkgdown)*.
- The code is styled automatically thanks to
  *[styler](https://CRAN.R-project.org/package=styler)*.
- The documentation is formatted thanks to
  *[devtools](https://CRAN.R-project.org/package=devtools)* and
  *[roxygen2](https://CRAN.R-project.org/package=roxygen2)*.

For more details, check the `dev` directory.

This package was developed using
*[biocthis](https://bioconductor.org/packages/3.17/biocthis)*.
