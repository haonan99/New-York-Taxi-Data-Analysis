 # MAST30034 Exporatory Analysis of New York City Taxi

As one of the most populous cities in the United States, New York City witnesses millions of taxi trips every month. This project aims to conduct a quantitative analysis of the New York City Taxi and Limousine Commission (TLC) trip record data to gain a better understanding of it. Additionally, we aim to provide recommendations that might improve taxi drivers' income.

 * <img src="https://iconape.com/wp-content/files/ik/11613/png/medium.png" width="15" height="15"/><a href="https://medium.com/@haonanzhong/new-york-city-taxi-data-analysis-286e08b174a1"> Medium Story</a>
 * <img src="https://iconape.com/wp-content/files/ro/51720/png/dropbox-paper.png" width="15" height="15"/><a href="https://github.com/greysonchung/New-York-Taxi-Data-Analysis/blob/main/Project%201%20Report.pdf"> Project Report</a>

 ## Dependencies
 - <img src="https://iconape.com/wp-content/files/zt/11663/png/python.png" width="15" height="15"/> Language: Python 3.8.8
 - <img src="https://iconape.com/wp-content/files/zt/11663/png/python.png" width="15" height="15"/> Python Packages / Libraries: pandas, geopandas, numpy, matplotlib, seaborn, scipy, sklearn, statsmodels, contextily

 ## Datasets
 - [NYC TLC Dataset (Jan, Feb, Jul, Aug of 2018)](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
 - [NYC Taxi Zone Shapefile](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
 - [NYC Central Park Weather Record (2018)](https://www.ncdc.noaa.gov/cdo-web/datasets/GHCND/stations/GHCND:USW00094728/detail)
 - To download NYC TLC datasets please locate `download.ipynb` included in `code`, Taxi Zone Shapefile and weather dataset has been included in `raw_data`.

 ## Directory
 - `raw_data`: Contains all the raw data files. Added to `.gitignore`
 - `preprocessed_data`: Contains all the preprocessed data files. Added to `.gitignore`
 - `plots`: Contains all visualisation plot for the project.
 - `deprecated`: Contains all the old code that I don't use anymore.
 - `code`: Contains notebooks for Preprocessing, Visualisation, and Modelling.
    - `download.ipynb` for "Downloading" trip record datasets.
    - `preprocessing.ipynb` for "Preprocessing" and "Exploratory Data Analysis".
    - `visualisation.ipynb` for "Analysis and Visualisation".
    - `modelling.ipynb` for "Statistical Modelling".
 - To reproduce the results, simply download all the dataset and run each notebook.
