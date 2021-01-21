BST 270
Individual Project
Maxwell Wang

This repository contains the files needed to run my individual project.
The data is contained in us-counties.csv and all-states-history.csv, 
from the NYT and the Covid Tracking Project, respectively.
us-counties.csv lists the cumulative cases and deaths for each US county, for each day, over one year.
all-states-history.csv lists more specific data types, but we make use of the currentlyHospitalized variable, which 
tracks the total current hospitalizations for each day, for each state.
The max_wang_individual_project.Rmd is the RMarkdown code that processes the data and produces my code.

This repository also contains the resulting pdf in max_wang_individual_project.pdf.

To run the code, require the following libraries: ggplot2, tidyverse, stringr, zoo, lubridate, kableExtra, choroplethr, choroplethrMaps
