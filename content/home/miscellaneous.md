+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = "2016-04-20T00:00:00"

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Miscellaneous"
subtitle = ""

# Order that this section will appear in.
weight = 80

+++

## Installation Guide for Software and Packages

While teaching programming skills I have assembled a set of instructions for setting up a computing environment that I find useful for economics / marketing research. Instructions are provided for Linux (Ubuntu flavored), Mac and Windows environments. 

* [Installation Guide](https://github.com/lachlandeer/installation-guide)
    * Borrowed and updated from the programming course I co-taught at UZH in 2017. 

## Reproducible Research Workflows

The Snakemake workflow management system helps to create reproducible and scalable data analyses. 
It was originally designed for Bioinformatics workflows, but I have found it suits research in empirical economics and marketing just as well.
Official documentation for Snakemake is [here](https://snakemake.readthedocs.io/en/stable/). 
Below are some templates that I use for my research and an extended tutorial.

* [Snakemake template for `R`](https://github.com/lachlandeer/snakemake-econ-r)
    * *Status: Under development*
    * Coauthored with [Julian Langer](https://julianlanger.github.io) (U Zurich)
    
<!---
* [Snakemake template for `Python`](https://github.com/lachlandeer/snakemake-python)
* [An extended Snakemake tutorial](https://github.com/lachlandeer/snakemake-economics)
--->

Some of my older projects use `Waf` to implement a reproducible workflow. `Waf` was introduced to me by [Hans-Martin von Gaudecker](http://wiwi.uni-bonn.de/gaudecker/index.html). 
He provides great templates [here](https://github.com/hmgaudecker/econ-project-templates) in multiple programming languages along with an [extended tutorial](http://hmgaudecker.github.io/econ-project-templates/). 
It's a good alternative, but I think the Waf learning curve is a tad steeper.


## Markdown templates

Most of my written work is in markdown. Here are some templates I regularly use:

* [Article templates](https://github.com/lachlandeer/bookdown_rticles) with `bookdown` and `rticles`
* [Beamer slide template](https://github.com/lachlandeer/beamer-LagonBleu) with `markdown`
* [CV template](https://github.com/lachlandeer/lachlandeer-cv) with `Rmarkdown`
* [HTML slide template](https://github.com/lachlandeer/xaringan-template) with `Rmarkdown` and `xaringan`

<!---
* [UZH Thesis templates](https://github.com/lachlandeer/thesisdown-uzh) with `Rmarkdown`
* [UZH Letter template](https://github.com/lachlandeer/uzh-letter) with `Rmarkdown`
--->

<!---
## Other tutorials
Some other tutorials I have put together over the years:

* [Data Wrangling with Pandas: A Guide for Economists](https://github.com/lachlandeer/pandas-economics)
* [Estimating Econometric Models with GMM in R](https://github.com/lachlandeer/gmm-r)
--->