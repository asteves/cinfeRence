
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Applied Causal Inference Tutorials

<!-- badges: start -->
<!-- badges: end -->

The goal of these tutorials is to give students hands on deliberate
practice with the basics of causal inference.

![](https://media.giphy.com/media/JgfJrINqmg6dNw3qJ3/giphy.gif)

## Installation

You can install the released version of cinfeRence from
[GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("rstudio/learnr")
remotes::install_github("rstudio/gradethis")
remotes::install_github("asteves/cinfeRence")
```

There are two ways to start tutorials. In RStudio 1.3 or later, you will
find tutorials listed in the “Tutorial” tab in the top-right pane (by
default). Find a tutorial and click “Start Tutorial” to begin.
Alternatively, you can run any tutorial from the R console by typing:

``` r
learnr::run_tutorial("TUTORIAL_OF_INTEREST", package = "cinfeRence")
```

For example:

``` r
learnr::run_tutorial("00-intro", package="cinfeRence")
```

will bring up the Introduction tutorial in your default web browser. You
can see the full list of tutorials in the package from the R console by
typing:

``` r
learnr::available_tutorials("cinfeRence")
```

## Submission Reports

At the end of each tutorial, students can download submission reports
that describe what questions and exercises they attempted. These pdfs
can be uploaded to a learning management system like Gradescope.

## Notes

Thanks to [Matt Blackwell](https://github.com/mattblackwell) for
permission to use the submission functions avaiable in
[qsslearnr](https://github.com/mattblackwell/qsslearnr)
