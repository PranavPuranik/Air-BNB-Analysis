# Air-BNB-Analysis
<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Boston_Airbnb_Data_Analysis</h3>

</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* Installations
* Dataset
* Project Motivation
* Data Preparation
* Data Visualization
* Results

<!-- Installations -->
## Installations

For this project, I used the python 3.8 in Jupiter notebook for analysing data available in Anaconda Navigator.

<!-- Dataset -->
## Dataset

For this data analysis, I used Boston Airbnb data available on [Kaggle](https://www.kaggle.com/). This data was available in form of three CSV files: calendar.csv,
listings.csv and reviews.csv. This data contained information about listings in Boston, prices, host information, reviews and information
about location.

<!-- Project Motivation -->
## Project Motivation

In this project, I tried to analyze Airbnb data to adress following questions:
* Which is the most rated and visited places to stay in Boston?
* What is the airbnb price variation in the city and find some of the cheapest places to stay in Boston?
* How Airbnb prices have varied over time in last two year in Boston?

<!-- Data Preparation -->
## Data Preparation

The Boston Airbnb dataset contained 3585 observations and 95 features. I only needed calendar.csv and listings.csv dataset for my study.
For finding most popular places, I compared number or views, so created new dataset with only few columns showing number of views for all places.

For comparing prices, I created a new datafram to compare rents in different places in Boston. I also needed to convert prices from string to float, I had to remove '$' and ',' signs while cleaning and wrangling data.

While studying price variation over time, I created a new dataframe containing information like number of reviews, location, etc and use datetime
to study price variation over 2 years, months and weekly variations.


<!-- Data Visualization -->
## Data Visualization

In this study, I used python and Jupiter notebook for ploting most popular places, airbnb price variations in different regons and price variation over time..

<!-- Results -->
## Results

The observations from the study are published in [Medium](https://medium.com/@pranavpuranik10/cheapest-and-popular-places-to-stay-in-boston-during-your-next-visit-a46f140165a).
