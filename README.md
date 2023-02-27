# Quantitative Analysis of HVFHV under COVID-19
- Student Name: Yutong Liu
- Student ID: 1074416
- Due Date: Friday 16th of August 11:59:00 am (AEST).
- Report Link: _Insert Report Link if applicable_

# Dependencies
- Language:  Python 3.8.3 
- Packages / Libraries: _i.e pandas, numpy, sklearn, folium, seaborn, matplotlib, geopandas, statsmodels 

# Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- NYC COVID-19 cases by day: https://raw.githubusercontent.com/nychealth/coronavirus-data/master/trends/cases-by-day.csv
- Taxi Zone Lookup Table: https://s3.amazonaws.com/nyc-tlc/misc/taxi+_zone_lookup.csv


# Directory
- `raw_data`: Contains the aggregated data set 'fhvhv_covid.csv'. There is another preprocessed data set 'fhvhv_2020.feather' contains all trip reccords of High Volume For-Hire Vehicles from September to December 2020. As this file is too large to upload, you can generate it from Notebook 2.
- `preprocessed_data`: Contains all the preprocessed data files. You may add this folder to `.gitignore` if your files are too large, but your script should automaticaally generate files here given the correct dataset in `raw_data`.
- `plots`: All figures are saved as pdf format, except for geospatial maps which is stored as html format. You can generate the maps from Notebook 3 in order to view them. I have also attached the screen shots of the maps in the folder.
- `code`: Keep all notebooks and scripts in this folder. Ensure that you have notebooks for each _stage_ of code. Here's an example:
    - Notebook 1 for "Extracting Data & Installing Packages".
    - Notebook 2 for "Preprocessing & Exploratory Data Analysis".
    - Notebook 3 for "Analysis and Visualisation".
    - Notebook 4 for "Statistical Modelling".
- `deprecated`: A folder to store "old code" that **you do not use anymore** or code that you experimented with, but decided to not go ahead. This is useful in case you ever need to come back to an older iteration of code or to express your other approaches to the problem.

# Other
- Please change the working directory to suit you need when you download, read and save the files.
