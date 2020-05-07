
-----

output: github\_document

-----

<!-- README.md is generated from README.Rmd. Please edit that file -->

rockr <img src='hex/rockr_hex' align="right" height="150" />

<!-- badges: start -->

<!-- badges: end -->

The goal of rockr is to:

Given a series of polls   –based on a longitudinally sequenced
phenomenon   –where response options reoccur across polls

1.  Wrangle data into an analysis-ready format

2.  Produce multiple scalings and subsets of data for different ways of
    conceptualizing and slicing poll responses

3.  Render animated bar charts to visualise the cumulative and
    aggregated sentiment according the series of polls

<p align="center">

<img src="plots/album_poll_final_percentage.gif" alt="reviewer">

</p>

## Installation

You can install rockr by first going to your Developer Settings and
creating a new [Personal Access Token
(PAT)](https://github.com/settings/tokens). Once you have the new token,
run this:

``` r

# install.packages("devtools")

devtools::install_github("bmgf-k12/edreportr", auth_token = "PAT")
```

## Setup
