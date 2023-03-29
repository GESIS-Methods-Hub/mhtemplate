
# mhtemplate

<!-- badges: start -->
<!-- badges: end -->

mhtemplate provides a custom pkgdown template for GESIS Methods Hub packages. We use this to render sites at xxx. Please don’t use it for your own package if it’s not part of the GESIS Methods Hub package.

Inspired by [rotemplate](https://github.com/ropensci-org/rotemplate) and [tidytemplate](https://github.com/tidyverse/tidytemplate/).

For help, see [pkgdown docs](https://pkgdown.r-lib.org/articles/customise.html#template-packages)

# Usage (local)

Install the package

```r
remotes::install_github("GESIS-Methods-Hub/mhtemplate")
```

add `_pkgdown.yml` to an R package repository with content

```yml
template:
  package: mhtemplate
```
