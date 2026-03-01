[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/RdDGCVLN)
# Mini-Project 1: Air Quality Analysis

Hello!
This is the README file for my first DS105-Data for Data Science, summative project.
This specific repository is a copy of the project (currently in a private repo managed by LSE). If there are any technical issues I didn't catch while copying and pushing it in VSCode, please email me at walkerwusimpson@gmail.com 

## Project Overview

I'm investigating the question “Does London’s air clean up on weekends?”
To answer this question, I had to decide whether I would include multiple locations, focus on certain polutants, and use all the historical data avaliable or select a certain period. 
Ultimately...
Locations: I chose to have one location in the center of London and another at the edge of Greater London
Pollutants: I chose to focus on pollutants that had an impact on health
Time: I chose to start gathering data when COVID restrictions were lifted
I go into further detail in markdown blocks scattered throughout the notebooks.



## How to Run

To reproduce my analysis, one should install the additional python dotenv package and install it via the terminal. Personal API Keys to fetch the historical data can be made on the OpenWeather website: https://openweathermap.org/

## Data Sources

I used OpenWeather's historical worldwide air pollution API. 
Regarding thresholds...
- for my start time, I found the end of (majority) covid-restrictions in the UK here: https://www.ons.gov.uk/peoplepopulationandcommunity/healthandsocialcare/conditionsanddiseases/bulletins/howpeoplespenttheirtimeaftercoronavirusrestrictionswerelifteduk/march2022
- to determine pollutants that had negative health impacts, I consulted the UN's Air Quality page here:https://www.who.int/teams/environment-climate-change-and-health/air-quality-energy-and-health/health-impacts, and the NIH's Air Pollution page here: https://www.niehs.nih.gov/health/topics/agents/air-pollution


## Results

My visualizations did not produce insights that imply London's weekend air is more beneficial for one's health in any area of Greater London.

However, my current vectorization and visualizations methods are beginner. I did not use any statistical methods in vectorizing my data or any of the visualizations in seaborn that include statistical significance. Perhaps in future classes and lectures, I will be able to confirm my current inferences. 
