SIAR - Stable Isotope Analysis in R
====

This package currently includes a mixing model, an ellipse based metric for population-level niche width and of community-level niche width all underpinned by Bayesian Inference.

See also the related package [MixSIAR](https://github.com/brianstock/MixSIAR) and the development of the standalone ellipse and convex hull estimates of niche with at [SIBER](https://github.com/andrewljackson/siber)

## Installation Instructions
N.B. the package siar is likely to be removed from CRAN in early 2015 owing to a change in how package dependencies need to be handled within siar. There are a few other minor, mostly stylistic issues that CRAN have identified that need to be dealt with. However, with only 2 weeks notice given to us on 21.12.2014, and with christmas holidays in fully swing, its unlikely we will be able to fixe them. In the meantime, the source files are still available here, and can be installed directly from github as instructed below.
* the latest released version: `install.packages("siar")`
* the latest development version: `install_github("AndrewLJackson/siar")`

##Publications

Jackson, A.L., Parnell, A.C., Inger R., & Bearhop, S. 2011. Comparing isotopic niche widths among and within communities: SIBER – Stable Isotope Bayesian Ellipses in R. Journal of Animal Ecology, 80, 595-602. [doi](http://dx.doi.org/10.1111/j.1365-2656.2011.01806.x)

Parnell, A.C., Inger R., Bearhop, S. & Jackson, A.L. 2010. Source partioning using stable isotopes: coping with too much variation. PLoS ONE, 5(3), e9672 . [doi](http://dx.doi.org/10.1371/journal.pone.0009672)
