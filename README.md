
# `groupTesting`: Simulating and Modeling Group (Pooled) Testing Data

###### Version : [1.1.0](https://myaseen208.com/groupTesting/); License: [GPL-2\|GPL-3](https://www.r-project.org/Licenses/)

##### *Md S. Warasi*

[Department of Mathematics and Statistics, Radford University, Radford,
VA](https://www1.radford.edu/content/csat/home/math/faculty.html)

------------------------------------------------------------------------

[![minimal R
version](https://img.shields.io/badge/R%3E%3D-2.10.0-6666ff.svg)](https://cran.r-project.org/)
[![License: GPL
v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![CRAN_Status_Badge](https://www.r-pkg.org/badges/version-last-release/groupTesting)](https://cran.r-project.org/package=groupTesting)
[![rstudio mirror
downloads](https://cranlogs.r-pkg.org/badges/grand-total/groupTesting?color=green)](https://CRAN.R-project.org/package=groupTesting)
<!-- [![packageversion](https://img.shields.io/badge/Package%20version-0.2.3.3-orange.svg)](https://github.com/myaseen208/groupTesting) -->

[![develVersion](https://img.shields.io/badge/devel%20version-1.1.0-orange.svg)](https://github.com/myaseen208/groupTesting)

<!-- [![GitHub Download Count](https://github-basic-badges.herokuapp.com/downloads/myaseen208/groupTesting/total.svg)] -->

[![Project Status:
WIP](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
[![lifecycle](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://lifecycle.r-lib.org/articles/stages.html#stable)
[![Last-changedate](https://img.shields.io/badge/last%20change-2024--07--14-yellowgreen.svg)](https://github.com/myaseen208/groupTesting)

------------------------------------------------------------------------

## Description

Provides an expectation-maximization (EM) algorithm using the approach
introduced in Warasi (2021) [doi:10.1080/03610918.2021.2009867\>. The EM
algorithm can be used to estimate the prevalence (overall proportion) of
a disease and to estimate a binary regression model from among the class
of generalized linear models based on group testing data. The estimation
framework we consider offers a flexible and general approach; i.e., its
application is not limited to any specific group testing protocol.
Consequently, the EM algorithm can model data arising from simple
pooling as well as advanced pooling such as hierarchical testing, array
testing, and quality control pooling. Also, provided are functions that
can be used to conduct the Wald tests described in Buse (1982)
\<doi:10.1080/00031305.1982.10482817\> and to simulate the group testing
data described in Kim et al. (2007)
\<doi:10.1111/j.1541-0420.2007.00817.x](https://doi.org/10.1080/03610918.2021.2009867%3E.%20The%20EM%20algorithm%20can%20be%20used%20to%20estimate%20the%20prevalence%20(overall%20proportion)%20of%20a%20disease%20and%20to%20estimate%20a%20binary%20regression%20model%20from%20among%20the%20class%20of%20generalized%20linear%20models%20based%20on%20group%20testing%20data.%20The%20estimation%20framework%20we%20consider%20offers%20a%20flexible%20and%20general%20approach;%20i.e.,%20its%20application%20is%20not%20limited%20to%20any%20specific%20group%20testing%20protocol.%20Consequently,%20the%20EM%20algorithm%20can%20model%20data%20arising%20from%20simple%20pooling%20as%20well%20as%20advanced%20pooling%20such%20as%20hierarchical%20testing,%20array%20testing,%20and%20quality%20control%20pooling.%20Also,%20provided%20are%20functions%20that%20can%20be%20used%20to%20conduct%20the%20Wald%20tests%20described%20in%20Buse%20(1982)%20%3Cdoi:10.1080/00031305.1982.10482817%3E%20and%20to%20simulate%20the%20group%20testing%20data%20described%20in%20Kim%20et%20al.%20(2007)%20%3Cdoi:10.1111/j.1541-0420.2007.00817.x).

   

## Installation

The package can be installed from CRAN as follows:

``` r
install.packages("groupTesting", dependencies = TRUE)
```

 

The development version can be installed from github as follows:

``` r
if (!require("remotes")) install.packages("remotes")
remotes::install_github("myaseen208/groupTesting")
```

   

## What’s new

To know whats new in this version type:

``` r
news(package = "groupTesting")
```

## Links

[CRAN page](https://cran.r-project.org/package=groupTesting)

[Github page](https://github.com/myaseen208/groupTesting)

[Documentation website](https://myaseen208.com/groupTesting/)

[Companion website](https://myaseen208.com/groupTesting/)

## Citing `groupTesting`

To cite the R package `groupTesting` in publications use:

``` r
citation("groupTesting")
```
