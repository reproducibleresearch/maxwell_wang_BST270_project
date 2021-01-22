BST 270
Individual Project
Maxwell Wang

This repository contains the files needed to run my individual project.

Data:
us-counties.csv 
  Contains day-by-day cumulative cases and deaths for each United States county. Download from https://github.com/nytimes/covid-19-data
  Accessed January 19, 2021
all-states-history.csv
 Contains day-by-day data for each state. We make use of the currentlyHospitalized field, which tracks total current hospitalizations.
 Download from https://covidtracking.com/data
 Accessed January 19, 2021
 
 Figures:
 nyt1, nyt2, and nyt3 are included. These are the original New York Times figures that we are attempting to reproduce.

Code:
  The max_wang_individual_project.Rmd is the RMarkdown code that processes the data and produces my code.

This repository also contains the resulting pdf in max_wang_individual_project.pdf.


Instructions to reproduce pdf and figures:
  To run the code, require the following libraries: ggplot2, tidyverse, stringr, zoo, lubridate, kableExtra, choroplethr, choroplethrMaps.
  Libraries were built under R version 4.0.3
  Must CLONE this repository to properly obtain the data. Do not simply download the zip file.
