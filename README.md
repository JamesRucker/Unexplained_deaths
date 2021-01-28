# Unexplained Pandemic Mortality
An analysis of death attribution data during the COVID-19 pandemic through September 2020.

## Table of Contents
* [General Info](#general-info)
* [Technologies](#technologies)
* [Visualizations](#visualizations)
* [Setup](#setup)
* [Sources](#sources)

## General Info
Cause-of-death attribution discrepancies are common in respiratory illness-related mortality. Calculations of excess deaths account for these discrepancies but provide no actionable information when increased mortality is unexplained by reported underlying causes of death. We compared national mortality reports for the coronavirus-2019 (COVID-19) pandemic with historical benchmarks to calculate and critically evaluate excess deaths. 

Using 312 weeks of population-adjusted mortality data from the U.S. National Center for Health Statistics (n=16.3 million deaths), we compared deaths in 2019-2020 with the previous 2, 3, and 5 influenza seasons from 2014-15 to 2018-19. We parsed pandemic-period excess deaths into explained versus unexplained causes using reported diagnostic categories.

## Technologies
* Python version: 3.6.10.final.0
* Pandas version: 1.0.4
* Jupyter Notebooks: 6.0.3
* MatPlotLib: 3.2.1

## Visualizations
Visualizations which include the word "seasons" are comparisons of the averages from prior seasons and the 2019-2020 flu season for that cause-of-death attribution and time period.  Visualizations without the word "seasons" are scatter plots for the death data for that cause of death starting with the 2014-2015 flu season.

## Setup
All needed files and programs are included in the technologies in order to run the code in this repository.


## Sources
U.S. Centers for Disease Control and Prevention, National Center for Health Statistics.
Public use data file documentation, mortality multiple cause-of-death. Accessed January
4, 2021. https://www.cdc.gov/nchs/nvss/mortality_public_use_data.htm. These are full
cause-of-death files including all underlying and contributing diagnoses for all
deaths. They are available only through 2019.

U.S. Centers for Disease Control and Prevention, National Center for Health Statistics.
Weekly counts of deaths by state and select causes, 2020-2021.
https://data.cdc.gov/NCHS/Weekly-Counts-of-Deaths-by-State-and-Select-
Causes/muzy-jte6. This is a partial cause-of-death file for 2020-2021. Fields
indicate preliminary underlying cause of death for top natural causes and
respiratory illness, including COVID-19.

U.S. Centers for Disease Control and Prevention, National Center for Health Statistics.
Weekly counts of deaths by state and select causes, 2014-2019.
https://data.cdc.gov/NCHS/Weekly-Counts-of-Deaths-by-State-and-Select-Causes/3yf8-
kanr. This is a partial cause-of-death file for 2014-2019. Fields indicate preliminary
underlying cause of death for top natural causes and respiratory illness,
including COVID-19.

U.S. Census Bureau. State population totals and components of change: 2010-2019.
U.S. Census Bureau. Accessed January 4, 2021.
https://www.census.gov/data/tables/time-series/demo/popest/2010s-state-total.html.
This is the source of the state population data used to population-adjust mortality
counts. Table to access is Table 1. Annual Estimates of the Resident Population
for the United States, Regions, States, and Puerto Rico: April 1, 2010 to July 1,
2019.
