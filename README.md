# BDSE08-G4-01-NYCTaxi
Using New York City Taxi data sets in iii BDSE08 Group 4 final project

## File content:

### arrange.sh & make_fields.py
  code from instructor Yang.  For unifying column names.

### nyu-2451-36743-geojson.json
  New York Taxi Zones GeoJSON downloaded from https://geo.nyu.edu/catalog/nyu-2451-36743

### nyu_2451_36743.zip
  New York Taxi Zones Shapefile downloaded from https://geo.nyu.edu/catalog/nyu-2451-36743

### title.ipynb
  Python code for data cleaning (unify column names, remove missing values, outlier detection)

### Spark_Title.ipynb
  Spark version of title.ipynb

### Readline.ipynb
  Uploaded 2018/10/16, updated 2018/10/16, merged 2018/10/17 \n  
  code to remove unwanted columns in our datasets and unify column names - including instructor Yang's 2 codes - by Shao-Chi.

### MappingLonLat-Shapely-2018-1022-1913.ipynb
  Uploaded: 2018/10/23
  
  Given a point (set of Longitude / Latitude), this python code can find out which NYC Taxi Zones the point belongs.
  
  This is to transform all longitude / latitude data in the NYC Taxi dataset to NYC Taxi zones.

### central_park_weather
  uploaded: 2018/10/24
  
  Weather record of Central Park (NY, USA) up to June, 2018
  
  Source: https://github.com/toddwschneider/nyc-taxi-data/blob/master/data/central_park_weather.csv
