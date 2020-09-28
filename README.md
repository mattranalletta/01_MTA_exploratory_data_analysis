# Metis Project 1: Exploratory Data Analysis for MTA Turnstile Data

The group is tasked with optimizing the placement of street teams around New York City subway stations, to gather contact information for the annual fall gala held by WomenTechWomenYes (WTWY). 

The goals of the client are: (1) to fill the seats for the event with individuals passionate about increasing participation of women in tech and who many donate to the cause, and (2) to build awareness and reach for WTWY.

[More background information here.](https://github.com/mattranalletta/onl20_ds4/blob/master/curriculum/project-01/project-01-introduction/project_01.md)

## Group members
- [Chris Doenlen](https://github.com/scrapfishies)
- [Vanessa Hu](https://github.com/vanessa920)
- [Jay Park](https://github.com/jcpark376)
- [Matt Ranalletta](https://github.com/mattranalletta)

## Contents
- [Group presentation](https://github.com/mattranalletta/ridge_project1_group4/blob/master/Ridge-Group4%20Presentation.pdf)
- [Notes and code on data cleaning process](https://github.com/mattranalletta/ridge_project1_group4/blob/master/data_cleaning/mta_data_cleaning.ipynb) (.ipynb)
- [Cleaned up MTA data](https://github.com/mattranalletta/ridge_project1_group4/blob/master/data_cleaning/mta_clean.zip) (.zip)
- [Top 10 Station Recommendation Analysis](https://github.com/mattranalletta/ridge_project1_group4/blob/master/mta_top_stations_analysis.ipynb) (.ipynb)
- [Recommended Stations Heat Maps](https://github.com/mattranalletta/ridge_project1_group4/tree/master/heatmaps)

## Summary

We downloaded six weeks of the MTA's public turnstile data from the summer of 2019 and cleaned it by removing outliers and messy data, as described in the code notes [here](https://github.com/mattranalletta/ridge_project1_group4/blob/master/Project_1_mta_data_analysis.ipynb). We parsed the data set to find the busiest stations, based on number of entries and exits at each station, and then combined that with research on the locations of tech companies in New York. 

From there, we picked ten key stations that both had high turnstile traffic and were near the top tech companies, and we removed more touristy stations like Times Square and Grand Central. We then analyzed each of the station data to find the times and days of the week when traffic was highest. We made day and time recommendations to WTWY off of this information [(seen here in the presentation)](https://github.com/mattranalletta/ridge_project1_group4/blob/master/Ridge-Group4%20Presentation.pdf), while also noting the possible lines the street teams could take.

## Sources & Reference
- [MTA Turnstile Data](http://web.mta.info/developers/turnstile.html)
- [MTA Turnstile Data - codebook](http://web.mta.info/developers/resources/nyct/turnstile/ts_Field_Description.txt)
- [MTA.info](http://www.mta.info/nyct), for maps and line logos
- [Kaggle: MTA Turnstile Data Analysis](https://www.kaggle.com/nieyuqi/mta-turnstile-data-analysis)
