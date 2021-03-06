# IDW Interpolation Prediction Analysis in R
Using Inverse Distance Weighting (IDW) interpolation to create prediction surfaces in R.
IDW method was used to predict distribution of N02, PM_25 and O3 of Air Quality data collected from sensors across USA.


## Data Source
The EPA provides many prepared datasets. Air quality data for year 2000 was used in this analysis
In this exercise, the Annual Summary Data  for will be used – Concentrations by Monitor:
https://aqs.epa.gov/aqsweb/airdata/download_files.html#Annual

## Study Area
The Analysis will cover Five States of "South Carolina", "North Carolina", "Georgia", "Kentucky" and "Tennessee"
![image](https://user-images.githubusercontent.com/60210384/168989439-71b36df9-292d-4dc4-9385-5f516159b219.png)



## Datasets
* Nitrogen dioxide (NO2)
* Ozone (03)
* PM2.5 Local conditions



## Data Preparation
Our research is limited to three air quality parameters: ozone (O3), nitrogen (NO3), and PM2:5 local condition. The data has 55 fields, however only Latitude, Longitude, Datum, Parameter Name, Arithmetic Mean, and State Name are relevant for this analysis.

