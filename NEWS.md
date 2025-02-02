# tidyquery (development version)

* Continuous integration migrated to GitHub Actions ([#28](https://github.com/ianmcook/tidyquery/issues/28))

# tidyquery 0.2.3

* Accepts names in form `namespace::object` in `FROM` clause ([#22](https://github.com/ianmcook/tidyquery/issues/22))
* Exports its version number ([#23](https://github.com/ianmcook/tidyquery/issues/23))
* Minor bugfixes and improvements

# tidyquery 0.2.2

* Improves stability with dtplyr and data.table ([#17](https://github.com/ianmcook/tidyquery/issues/17))
* Requires queryparser 0.3.1 or higher
* Minor improvements

# tidyquery 0.2.1

* Works when `FROM` clause refers to data frame in non-global environment ([#12](https://github.com/ianmcook/tidyquery/issues/12))
* Minor changes to support dplyr 1.0.0
* Minor bugfixes and improvements

# tidyquery 0.2.0

* Works with the [dtplyr](https://dtplyr.tidyverse.org/) package (a [data.table](http://r-datatable.com/) backend for dplyr) ([#6](https://github.com/ianmcook/tidyquery/issues/6))
* Accepts two-table joins that use SQL-92-style (explicit) join syntax ([#7](https://github.com/ianmcook/tidyquery/issues/7))
* Includes new function `show_dplyr()` to print dplyr code instead of running it ([#8](https://github.com/ianmcook/tidyquery/issues/8))
* Generates simpler, shorter dplyr code in many cases ([#9](https://github.com/ianmcook/tidyquery/issues/9))
* Continuous integration and coverage tests
* Minor bugfixes and improvements

# tidyquery 0.1.0

* First CRAN release
