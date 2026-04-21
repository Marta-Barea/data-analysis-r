# Data Analysis in R

## Description

This repository contains the development of PEC2 for the Software for Data Analysis course, part of the UOC-UB Master's Degree in Bioinformatics and Biostatistics.

The project is implemented in R Markdown and includes practical exercises on R programming, SQL queries from R, and statistical simulation. The main output of the repository is a reproducible PDF report generated from the source Rmd document.

## Project Contents

The report is organized into two main blocks:

1. Programming fundamentals and databases.
2. Probability and simulations.

These sections include exercises on:

- iterating through and validating DNA sequences and converting them into RNA;
- defining functions with error handling for normalization calculations;
- running SQL queries in R on the Theoph dataset using an in-memory SQLite database;
- comparing log-normal distributions applied to drug elimination times;
- calculating probabilities and performing binomial simulation in an analgesic treatment response scenario.

## Repository Structure

- `assets/images/`: images and graphical resources used in the report.
- `report/PEC2_data_analysis_r.Rmd`: source document for the analysis.
- `report/PEC2_data_analysis_r.pdf`: generated PDF report.
- `report/preamble.tex`: LaTeX configuration used to compile the report.
- `README.md`: general project description.

## Requirements

To reproduce the report, you need at least:

- R
- RStudio or another environment compatible with R Markdown
- the `rmarkdown` package
- the `knitr` package
- the `DBI` and `RSQLite` packages
- a LaTeX distribution to generate the PDF output

## Reproducibility

1. Open `report/PEC2_data_analysis_r.Rmd` in RStudio.
2. Install the required packages if they are not already available.
3. Knit or render the document to generate the report.

Optionally, it can be compiled from the console with:

```r
rmarkdown::render("report/PEC2_data_analysis_r.Rmd")
```

## Author

Marta Barea Sepúlveda, PhD<br>
Interuniversity Master’s Degree in Bioinformatics and Biostatistics<br>
Universitat Oberta de Catalunya — Universitat de Barcelona
