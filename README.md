# Cause of death attribution for COVID-19 pandemic
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
Visaulizations which include the word "seasons" are comparisons of the averages and the 2019-2020 flu season for that death attribution.  Visualizations without the word "seasons" are scatter plots for the death data for that cause of death starting with the 2014-2015 flu season.

## Setup
All needed files and programs are included in the technologies in order to run the code in this repository.


## Sources
https://www.cdc.gov/nchs/nvss/mortality_public_use_data.htm
