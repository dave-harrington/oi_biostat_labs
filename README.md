# oi_biostat_labs

#### Summary

This repository contains `R` labs that accompany the material presented in the OpenIntro Biostatistics textbook. These labs complement the conceptual material discussed in detail in the text by introducing statistical computing with `R` and `R Markdown`.

Each lab consists of a handout file with background information and problem statements, a solutions file with fully worked solutions and `R` code, and a template `.Rmd` file containing the basic structure to generate a file similar to the solutions file. The template is optimized for generating a PDF document. We recommend that a full installation of TeX be downloaded before using the labs. 

The datasets used in the labs can be accessed from the `oibiostat` `R` package. To install the package from GitHub:

```r
install.packages("devtools")
devtools::install_github("OI-Biostat/oi_biostat_data")
```
