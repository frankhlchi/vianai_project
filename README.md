# Vianai project 
# required Python package: 
- pandas
- numpy
- matplotlib
- seaborn
- geopandas
- folium
- shapely
- xgboost

# data required to run the code:
- Green Taxi analysis part-1.ipynb 

(1) green_tripdata_2015-09.csv (Green Taxis for September 2015, from https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

(2) nyu_2451_36743.shp, (this file is included in this github responsitory, which is ./nyu_2451_36743_WGS84/nyu_2451_36743.shp); or it can be downloaded from https://archive.nyu.edu/handle/2451/36743)

- Green Taxi analysis part-2.ipynb

Required data files can be generated by running the part 1 notebook, or downloaded from the following links:

(1) proceessed_data.csv, https://drive.google.com/file/d/1Dwd5rloa3ontg9Zwnx6HtTBRNxh3EIp6/view?usp=sharing 

(2) region_info.csv, https://drive.google.com/file/d/172cysR4PsNOqOnJ0Ml2U78-DGMQq2tmx/view?usp=sharing 



# analysis breakdown:
Green Taxi analysis part-1.ipynb addresses the following problems:
- Characterize the data and comment about its quality
- Explore and visualize the data e.g. a histogram of trip distance
- Find interesting trip statistics grouped by hour
- Find an anomaly in the data and explain your findings

Green Taxi analysis part-2.ipynb answers the following questions :
- The taxi drivers want to know what kind of trip yields better tips. Can you build a model for them and explain the model?
