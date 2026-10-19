# Linking SHELDUS and longitudinal studies
This repository provides code to link SHELDUS data with longitudinal studies such as cohort or panel studies. The code was originally developed for use with the [Health and Retirement Study (HRS)](https://hrs.isr.umich.edu/). However, HRS respondent location below the county level is restricted-level information (it is not publicly disclosable whether a state even has residents included in the HRS sample). Therefore, for this example, I simulate data for a hypothetical longitudinal study of residents of South Carolina which has publicly available data in SHELDUS and that I used in another [code example](https://github.com/jennatipaldo/sheldus_sc). The format and variables of the simulated data are intended to emulate the HRS and other longitudinal datasets. 

## Data Source
The data that this code analyzes is for publicly available data from SHELDUS (the Spatial Hazard Events and Losses Database for the United States), a county-level dataset for the United States with information on natural hazards, including events, type of hazard, losses, injuries, and fatalities. 

### Citation
ASU Center for Emergency Management and Homeland Security (2025). The Spatial Hazard Events and Losses Database for the United States, Version 23.0 [Online Database]. Phoenix, AZ: Arizona State University. Available from [SHELDUS](https://sheldus.org).

## Accessing data
SHELDUS data can be accessed at [SHELDUS](https://sheldus.asu.edu/) - you will need to create an account. Some data, such as the data for the state of South Carolina, are available for free. 

### Query Settings
I used the following settings in my query:

Search By:	Location and Dates

Adjustment Year:	2022

States: SOUTH CAROLINA

Counties: All

Date Range:	2012-01-01 to 2021-12-31

Hazards & Perils:	All

Loss Types:	Fatalities, Injuries, Property Losses

Aggregate By:	Month, Hazard, County, Year
