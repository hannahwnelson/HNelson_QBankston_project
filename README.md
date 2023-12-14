# HannahQuinn872

## Summary

This is a repository containing research pertaining to COPD mortality in the state of North Carolina. The goal is to determine factors that lead to higher rates of mortality in the state, and investigate the disparity between rural and urban mortality. The research is mostly based on CDC data sets, from the years of 2008-2021. Maps and OLS regressions were used to establish relevancy of particular determinants. 


## Investigators

Quinn Bankson and Hannah Nelson

## Database Information

-CDC data on hospitalizations for asthma
-CDC data on extreme heat
-CDC data on COPD mortality
https://www.cdc.gov/copd/data-and-statistics/county-estimates.html 

-EPA data on AQI
https://www.epa.gov/outdoor-air-quality-data/air-data-daily-air-quality-tracker

-NCHS data on urban rural classification schemes
https://www.cdc.gov/nchs/data_access/urban_rural.htm

Shapefile for NC from ENVIORN872

## Folder structure, file formats, and naming conventions 

A file called Raw contains all raw files. No raw files are used directly in the final .rmd.

A file called Cleaned contains all cleaned files. These are wrangled and organized files that are used in the final .rmd. 

A file called Presentation holds various presentation materials. 

A file called AIC holds initial AIC investigations. This file does not provide any additional information that is not in the final materials. 

A file called Importing_Cleaning_Merging.rmd documents the way that files form the Raw data folder were processed before being added to the Cleaned data folder. 

The package "here" is used in the final to make naming conventinos easier for changing file pathways. The directory for "here" is the repository, called HannaQuinn872. 

The file "Final Material" contains a file called Final.Rmd and Final.html. Final.Rmd was used to knit Final.html. Final.html is a bookdown html document2 style knitted version of our final product. It walks readers through 6 stages which are linked in an interactive table of contents. The sections of the final product include 
1. Rationale and Research Questions
2. Dataset Information
3. Exploratory Analysis
4. Analysis
5. Summary and Conclusions
6. References

