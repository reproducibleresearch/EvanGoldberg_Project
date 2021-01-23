# EvanGoldberg_Project
Repository for Evan Goldberg's Individual Project

This repository contains the data and code needed in order to reproduce the figures and tables presented in the New York Times article, [Coronavirus in the U.S.:
Latest Map and Case Count](https://www.nytimes.com/interactive/2020/us/coronavirus-us-cases.html#anomaly-notes). 

The first data set is the us-counties.csv which can be accessed in the [NYT GitHub repository](https://github.com/nytimes/covid-19-data) as well as in our repository. This is the primary source of data for this project. It contains information about COVID cases and deaths at the state and county level. It is important to note that this dataset is updated daily in the NYT GitHub. Our version was accessed on January 19th, 2021, and this project was designed to reproduce results as of January 17th, 2021. 

The second set of data is the cases.csv obtained from [The COVID Tracking Project](https://covidtracking.com/data) for hospitalization data. This data also contains information on COVID cases and deaths, but more importantly, contains information on hospitalization data. Our version was accessed on January 19th, 2021.

Our code can be accessed from 270_individual_project_evan_goldberg.Rmd and the results can be accessed from the accompanying 270_individual_project_evan_goldberg.html. 

In order to reproduce this project, you need to download the RMD file and the two csv files. R version 4.0.2 and R Studio were used to write the code and to reproduce the figures and tables. All steps for reproducing the plots and tables are located in the RMD file. The following packages were used and are also included in the RMD file: ggplot2, tidyverse, stringr, zoo, lubridate, and kableExtra. 
