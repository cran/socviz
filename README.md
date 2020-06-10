<!-- README.md is generated from README.Rmd. Please edit that file -->



# socviz <img src="man/figures/logo.png" align="right" width="120" />

<!-- badges: start -->
[![R build status](https://github.com/kjhealy/socviz/workflows/R-CMD-check/badge.svg)](https://github.com/kjhealy/socviz/actions)
<!-- badges: end -->

This is an R package of datasets, functions, and course materials to go along with the book _[Data Visualization: A Practical Introduction](https://amzn.to/2vfAixM)_ (Princeton University Press, 2019).


<img src="http://socviz.co/assets/dv-cover-pupress.jpg" width = "75%"/>

## What's in this Package

The `socviz` package contains about twenty five datasets and a number of utility and convenience functions. Most of them are used in _[Data Visualization: A Practical Introduction](https://amzn.to/2vfAixM)_ (`http://socviz.co`), and there are also a few others as well for self-learners and students to practice their skills on. 

A course packet is also included. This is a zipped file containing an [R Studio](http://rstudio.com) project consisting of a nine [R Markdown](http://rmarkdown.rstudio.com) documents that parallel the chapters in the book. They contain the code for almost all the figures in the book (and a few more besides). Some support files are also included, to help demonstrate things like reading in your own data locally in R.


## Installation

To install the package, you can follow the instructions in the Preface to the book. Alternatively, first download and install R for [MacOS](https://cran.r-project.org/bin/macosx/), [Windows](https://cran.r-project.org/bin/windows/) or [Linux](https://cran.r-project.org/bin/linux/), as appropriate. Then download and install [RStudio](http://rstudio.com/download/). Launch RStudio and then type the following code at the Console prompt (`> `), hitting return at the end of each line:


```r


my_packages <- c("tidyverse", "fs", "devtools")
install.packages(my_packages)

install.packages("socviz")

```

To install the development version of `socviz`, instead of `install.packages("socviz")` do the following:


```r

devtools::install_github("kjhealy/socviz")

```

Once everything has downloaded and been installed (which may take a little while), load the `socviz` package: 


```r
library(socviz)
```

## The Course Packet

The supporting materials are contained in a compressed `.zip` file. To extract them to your Desktop, make sure the `socviz` package is loaded as described above. Then do something like this:


```r

setup_course_notes(folder = "~/Desktop")

```

You can choose the destination folder, but you must supply one. Here, the `dataviz_course_notes.zip` file will be copied to your Desktop, and uncompressed there into a folder called `dataviz_course_notes`. Open the folder, and double-click the file named `dataviz.Rproj` to launch the project as a new RStudio session. If you want to uncompress the file somewhere other than your Desktop, e.g. your Documents folder, you can do this:


```r

setup_course_notes(folder = "~/Documents")

```



## More about the Datasets and Functions

The included datasets and functions are documented at <http://kjhealy.github.io/socviz/reference/>. 

