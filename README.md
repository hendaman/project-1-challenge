# project-1-challenge

Exploring post COVID-19 mobility patterns in Melbourne

Exploring Mobility Patterns in Metropolitan Melbourne (June 2018-June 2022)

Team Members

Henry Leighton

Owen Johannes

Tao Ma

Jai Gupta

Tattwamasi Ray

Project Description

The COVID-19 pandemic has significantly impacted transportation and mobility patterns in many cities, including Melbourne. This study aims to investigate how mobility patterns in Metropolitan Melbourne have evolved from June 2018 to June 2022, with a focus on the impact of the pandemic. We will analyze the data to answer several research questions related to public transport usage, pedestrian traffic, and the effects of the pandemic on mobility.

Research Questions

Which stations saw the greatest change in public transport usage/pedestrian traffic? Which municipality saw the greatest change in public transport usage? And which station saw the greatest change in the City of Melbourne?

How has each of the different modes of public transport increased or decreased in usage over the pandemic?

How has the volume of pedestrian traffic in Melbourne’s CBD evolved over the time frame? (Explore peak and off-peak hours)

Did the pandemic affect people traveling during peak hours by public transport in Melbourne?

Datasets
We used the following datasets for our analysis:

Monthly public patronage by mode (XLS/CSV): https://discover.data.vic.gov.au/dataset/monthly-public-transport-patronage-by-mode

Annual regional train station patronage (station entries) (XLS/CSV): https://discover.data.vic.gov.au/dataset/annual-regional-train-patronage-station-entries

Pedestrian Counting System - Monthly (counts per hour) (CSV): https://melbournetestbed.opendatasoft.com/explore/dataset/pedestrian-counting-system-monthly-counts-per-hour/information/

Pedestrian Counting System - Sensor Locations (API): https://data.melbourne.vic.gov.au/explore/dataset/pedestrian-counting-system-sensor-locations/information/

Pedestrian Counting System - Past Hour (counts per minute) (API): https://data.melbourne.vic.gov.au/explore/dataset/pedestrian-counting-system-past-hour-counts-per-minute/information/

Victorian Coronavirus (COVID-19) Data: https://www.coronavirus.vic.gov.au/victorian-coronavirus-covid-19-data

Hypothetical Testing:

After we made our analysis, we did Hypothesis Testing and stastical analysis. it means our Analysis did not occur by chance, it is backed enough evidence. we performed different tests ANOVA test using the f_oneway function from the scipy.stats module and two sample two tests which returns the F-statistic and p-value. Finally, we check the p-value and compare it with the significance level (0.05 in this case) to determine whether to reject or fail to reject the null hypothesis.
If the p-value is less than the significance level, we reject the null hypothesis and conclude that there is a significant difference .Otherwise, we fail to reject the null hypothesis and conclude that there is no significant difference.

Conclusions:
By analyzing these insights,we found conclusions that people are slowly returning to their pre-pandemic mobility patterns and are starting to use public transport again.Policymakers can make informed decisions to improve public transport services, especially in the post-COVID era, to encourage more people to return to using public transport as their preferred mode of transportation.



Directory Structure

data: This directory contains all the raw and processed datasets used in the analysis.

notebooks: This directory contains all the Jupyter notebooks used in the analysis.

results: This directory contains all the results and visualizations generated from the analysis.

README.md: This file contains a brief description of the project and the directory structure.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Branch naming structure:

Initials - Question - Version

Example: HL-Q1-V1
