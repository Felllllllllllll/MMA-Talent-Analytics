hello-ta
================

Hello,TA!

``` r
options(repos = list(CRAN = "https://cloud.r-project.org"))
```

``` r
install.packages('tidyverse')
```

    ## 
    ## The downloaded binary packages are in
    ##  /var/folders/gr/b1qq2xyj2cb89524s13yptc80000gn/T//Rtmpe7I4Uj/downloaded_packages

``` r
install.packages("igraph")
```

    ## 
    ## The downloaded binary packages are in
    ##  /var/folders/gr/b1qq2xyj2cb89524s13yptc80000gn/T//Rtmpe7I4Uj/downloaded_packages

``` r
install.packages("tinytex")
```

    ## 
    ## The downloaded binary packages are in
    ##  /var/folders/gr/b1qq2xyj2cb89524s13yptc80000gn/T//Rtmpe7I4Uj/downloaded_packages

``` r
library(tidyverse)
```

    ## ── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
    ## ✔ dplyr     1.1.3     ✔ readr     2.1.4
    ## ✔ forcats   1.0.0     ✔ stringr   1.5.0
    ## ✔ ggplot2   3.4.3     ✔ tibble    3.2.1
    ## ✔ lubridate 1.9.3     ✔ tidyr     1.3.0
    ## ✔ purrr     1.0.2     
    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()
    ## ℹ Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors

``` r
library(igraph)
```

    ## 
    ## Attaching package: 'igraph'
    ## 
    ## The following objects are masked from 'package:lubridate':
    ## 
    ##     %--%, union
    ## 
    ## The following objects are masked from 'package:dplyr':
    ## 
    ##     as_data_frame, groups, union
    ## 
    ## The following objects are masked from 'package:purrr':
    ## 
    ##     compose, simplify
    ## 
    ## The following object is masked from 'package:tidyr':
    ## 
    ##     crossing
    ## 
    ## The following object is masked from 'package:tibble':
    ## 
    ##     as_data_frame
    ## 
    ## The following objects are masked from 'package:stats':
    ## 
    ##     decompose, spectrum
    ## 
    ## The following object is masked from 'package:base':
    ## 
    ##     union
