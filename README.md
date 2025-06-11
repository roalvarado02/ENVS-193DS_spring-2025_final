# ENVS-193DS_Final
Final for ENVS 193DS class
Spring 2025

## General information

This is the repository for the Env S 193DS Final. In this final, we explore research writing, data visualization, data analysis with data that someone else collected, and affective visualizations that we created. 

### Packages

```
library(readxl) #allows reading excel files
library(tidyverse) #load package for data manipulation and vizualization 
library(janitor) #load package for cleaning column names
library(dplyr) #package for data manipulation
library(gt) #package for themes
library(effectsize) #package to compute effect sizes
library(ggplot2) #package to create data visualization 
library(lubridate) #package to manipulate dates
library(DHARMa) #packing to run residual diagnostics 
library(MuMIn) #package for model selection
library(ggeffects) #package for ggpredict
```

## Data and file information

File structure:

```
.
├── ENVS-193DS_spring-2025_final.Rproj
├── README.md
├── code                                     # code folder
│   ├── final.html            # rendered output is from .qmd key
│   ├── final.qmd
│   ├── final_files
└── data                                     # data folder
    └── occdist.csv
    └── seasurfacetemp.csv
```

## Rendered output

The rendered key is https://envs193ds.lsit.ucsb.edu/user/roalvarado/rstudio/files/ES-193DS/Final/ENVS-193DS_spring-2025_final/code/final.html 