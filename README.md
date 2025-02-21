# Temperature-Analysis
This is a assignment that was assigned by Tranzmeo in which I have analysed the temperature using NOAA's GHCN(global historical Climatology Network)
data.
This analysis contains 
1)The record of high and low temperature in between 2005-2014.
2)Highlighting the highest temperature.
3)Visualizing Locations.
4)summarising 2015 temperature.

There are 2 datasets provided
1)Temperature.csv which contains the daily temperature.It includes
->ID : Identifier
->Date : Date of observation.
->Element : Temperature (TMIN or TMAX).
->Data_Value : Recorded temperature.
2)BinSize.csv which provides data which includes
->ID : Identifier
->LATITUDE AND LONGITUDE : Geographical locations.
->NAME : Station names.

The assignment is done by using python 
->I have used pandas package (also known as DataFrame) for data manipulation.
->matpotlib library for ploting and visualisation.
->folium is a library used to create interactive maps using leaflet.js.
->seaborn is a library used to visualise data statistically.

Steps:
1)Convert dates, filter required years and remove leap year.
2)Identify the high and low temperature from 2005-2014.
3)Compare and find highest temperature in 2015 with previous data.
4)Plot the graph for high and low temperature in 2015, Map of stations near Ann arbor and provide insights on temperature.

This repository consist of
1)BinSize.csv
2)README.md
3)Temperature 1.png
4)Temperature 2.png
5)temperature.csv
6)temperature.ipynb
