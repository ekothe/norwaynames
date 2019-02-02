
<!-- README.md is generated from README.Rmd. Please edit that file -->
norwaynames
===========

The norwaynames package provides the following datasets

-   `all` this dataset includes the sex, count, and proportion of births for each first name from 1880 - 2017. The data set includes all names with more than 4 instances in any given year. Names have an NA count or percentage if they were not in use in that year. Before 1945, the count of births with each first name was not recorded. Proportion of births with each first name is recorded every year. Source: Statistics Norway <https://www.ssb.no/en/statbank/table/10467/>

-   `girls` this dataset includes the count, and proportion of births for each female first name from 1880 - 2017. The data set includes all names with more than 4 instances in any given year. Names have an NA count or percentage if they were not in use in that year. Before 1945, the count of births with each first name was not recorded. Proportion of births with each first name is recorded every year. Source: Statistics Norway <https://www.ssb.no/en/statbank/table/10467/>

-   `boys` this dataset includes the count, and proportion of births for each male first name from 1880 - 2017. The data set includes all names with more than 4 instances in any given year. Names have an NA count or percentage if they were not in use in that year. Before 1945, the count of births with each first name was not recorded. Proportion of births with each first name is recorded every year. Source: Statistics Norway <https://www.ssb.no/en/statbank/table/10467/>

``` r
library(norwaynames)
head(all)
#>   first_name year Percent Count    sex
#> 1      Aagot 1880   0.315    NA Female
#> 2       Aase 1880   0.031    NA Female
#> 3    Aashild 1880   0.016    NA Female
#> 4      Aasta 1880   0.031    NA Female
#> 5        Ada 1880   0.047    NA Female
#> 6      Adele 1880   0.016    NA Female
```

Installation
============

You can install the most recent version of norwaynames from github:

`install_github("ekothe/norwaynames")`
