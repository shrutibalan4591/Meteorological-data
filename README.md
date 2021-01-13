# Meteorological-data

One type of data that’s easier to find on the net is Weather data. Many sites provide historical
data on many meteorological parameters such as pressure, temperature, humidity,
wind_speed, visibility, etc. One such weather dataset we obtained is from
kaggle. (Source URL: https://www.kaggle.com/muthuj7/weather-dataset) 

The dataset has hourly temperature recorded 10 years starting from 2006-04-01
00:00:00.000 +0200 to 2016-09-09 23:00:00.000 +0200. It corresponds to Finland, a country in
the Northern Europe.

In this assignment, we are responsible for performing data cleaning, perform
analysis for testing the (given) Hypothesis.

The Null Hypothesis **H0** is **"Has the Apparent temperature and humidity compared monthly
across 10 years of the data indicate an increase due to Global warming"**

The **H0** means we need to find whether the average Apparent temperature for the
month of a month say April starting from 2006 to 2016 and the average humidity for
the same period have increased or not. This monthly analysis has to be done for all 12
months over the 10 year period. So you are basically resampling your data from hourly
to monthly, then comparing the same month over the 10 year period. Support your
analysis by appropriate visualizations using matplotlib and / or seaborn library.
