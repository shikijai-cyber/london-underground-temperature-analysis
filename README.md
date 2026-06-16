# London Underground Temperature Analysis

## Overview
This R Markdown project analyses London Underground temperature readings over time. It cleans raw monthly temperature data, handles outliers and missing values, and visualises temperature patterns across Underground lines.

## Features
- Raw-data cleaning and type conversion
- Date feature construction from month/year fields
- Outlier exploration and filtering
- Time-series visualisation using `ggplot2`
- Reproducible R Markdown report with rendered HTML output

## Project structure
```text
analysis/      R Markdown source report
outputs/       Rendered HTML report
data/raw/      Original `Underground.csv` file placeholder
requirements.R R package installation helper
```

## Installation
```bash
Rscript requirements.R
```

## Usage
Place `Underground.csv` in `data/raw/`, then render:
```r
rmarkdown::render("analysis/underground_temperature_report.Rmd")
```

## Technologies used
R, R Markdown, tidyverse, lubridate, ggplot2, knitr.

## Portfolio note
The uploaded archive did not include `Underground.csv`; the project is structured so the dataset can be added locally without changing the repository layout.
