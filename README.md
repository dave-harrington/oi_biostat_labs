# oi_biostat_labs

#### Summary

This repository contains `R` labs that accompany the *OpenIntro Biostatistics* textbook. These labs complement the conceptual material discussed in detail in the text by introducing statistical computing with `R` and `R Markdown`.

Each lab consists of a handout file with background information and problem statements, a solutions file with fully worked solutions and `R` code, and a template `.Rmd` file containing the basic structure to generate a file similar to the solutions file. The template is optimized for generating a PDF document. We recommend that a full installation of TeX be downloaded before using the labs. The '.Rmd' source for the handout and solutions files are also available, and may be of use to instructors.

Most of the datasets used in the labs can be accessed from the `oibiostat` `R` package; instructions are provided for downloading any additional datasets. To install the 'oibiostat' package from GitHub:

```r
install.packages("devtools")
devtools::install_github("OI-Biostat/oi_biostat_data")
```


#### Users' Note

These labs were initially developed for a classroom setting, but can also be used by those interested in an independent learning experience. 

Unit 0 contains two short tutorials for getting started with R and R Markdown. Subsequent units correspond to the chapters in *OpenIntro Biostatistics*. Each lab consists of three files: a handout file, a template file, and a solutions file. 

- The handout file (.pdf) contains background information and problem statements. An instructor might choose to provide printed handout files to students so they can easily reference the problem statements while working through the labs. 

- The template file (.Rmd) contains space for entering answers (both plain text writing and code) along with additional guidance related to R and Rmd syntax. When compiled, the template generates a PDF document.

- The solutions file (.pdf) contains fully worked solutions and code. 

Each unit contains a 'Lab Notes' file that gives a high-level overview of the labs and provides a detailed explanation of the `R` programming used in each lab.
