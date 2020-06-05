# Air-BNB-Analysis
<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Boston_Airbnb_Data_Analysis</h3>

</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Installations](#install)
* [Dataset](#ds)
* [Project Motivation](#pm)
* [Data Preparation](#dp)
* [Data Visualization](#dv)
* [Results](#res)

<!-- Installations -->
## Installations <a name="install"></a>

For this project, I used the python 3.8 in Jupyter notebook for analysing data available in Anaconda Navigator.
Python libraries required include pandas and numpy.

<!-- Dataset -->
## Dataset<a name="ds"></a>

For this data analysis, I used Boston Airbnb data available on [Kaggle](https://www.kaggle.com/). This data was available in form of three CSV files: calendar.csv,
listings.csv and reviews.csv. This data contained information about listings in Boston, prices, host information, reviews and information
about location.

<!-- Project Motivation -->
## Project Motivation<a name="pm"></a>

In this project, I tried to analyze Airbnb data to adress following questions:
* Which is the most rated and visited places to stay in Boston?
* What is the airbnb price variation in the city and find some of the cheapest places to stay in Boston?
* How Airbnb prices have varied over time in last two year in Boston?

<!-- Data Preparation -->
## Data Preparation<a name="dp"></a>

The Boston Airbnb dataset contained 3585 observations and 95 features. I only needed calendar.csv and listings.csv dataset for my study.
For finding most popular places, I compared number or views, so created new dataset with only few columns showing number of views for all places.

For comparing prices, I created a new datafram to compare rents in different places in Boston. I also needed to convert prices from string to float, I had to remove '$' and ',' signs while cleaning and wrangling data.

While studying price variation over time, I created a new dataframe containing information like number of reviews, location, etc and use datetime
to study price variation over 2 years, months and weekly variations.


<!-- Data Visualization -->
## Data Visualization<a name="dv"></a>

In this study, I used python and Jupiter notebook for ploting most popular places, airbnb price variations in different regons and price variation over time..

<!-- File Description -->
## File Description<a name="ds"></a>

For this study, I downloaded these 3 .csv files from [Kaggle](https://www.kaggle.com/):
* calendar.csv - This file contains information about price variation over time, availabilty of property
* listings.csv - This file contains information about listings location, property type, host, price, listed date, documnets required for verification, listing ratings, market, transportation, etc.
* reviews.csv - This files contained name of visitors who stayed in different properties and their reviews about their stay at that property.

<!-- Acknowledgement -->
## Acknowledgement<a name="ds"></a>

I want to thank [Udacity](https://www.udacity.com/) for the excellent course materials and designed projects which are really helpful for me for becoming proficient in Data Science.

<!-- Results -->
## Results<a name="res"></a>

The observations from the study are published in [Medium](https://medium.com/@pranavpuranik10/cheapest-and-popular-places-to-stay-in-boston-during-your-next-visit-a46f140165a)
and analysis is performed in [Airbnb Boston.ipynb](https://github.com/PranavPuranik/Air-BNB-Analysis/blob/master/Airbnb%20Boston.ipynb)

1.Jamaica Plain, Dorchester, and South End are most popular places to rent Airbnb in Boston. <br>
2. Hyde Park and Roslindale have the lowest Airbnb prices in Boston to stay. <br>
3. The cheapest way to stay in Boston is to rent a shared room for less than $50 in Hyde Park or Mission Hill; or rent a private room for $63 in Hyde Park. <br>
4. February and March has lowest average Airbnb prices while September and October have the highest average Airbnb prices in Boston.
