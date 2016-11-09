EUROPEAN CLIMATE ASSESSMENT & DATASET (ECA&D), file created on: 09-10-2016
THESE DATA CAN BE USED FREELY FOR NON-COMMERCIAL RESEARCH PROVIDED THAT THE FOLLOWING SOURCE IS ACKNOWLEDGED: 

Klein Tank, A.M.G. and Coauthors, 2002. Daily dataset of 20th-century surface
air temperature and precipitation series for the European Climate Assessment.
Int. J. of Climatol., 22, 1441-1453.
Data and metadata available at http://www.ecad.eu

the following documents have been modified by Alvaro Alonso for a talk about data analysis with pythons library pandas.
DOCUMENTS:

weather_station_information.csv

Daily entries of all the european weather stations.In the data set different reports were merged (from the above organization). Entries with incomplete or inaccurate data were disposed. 

Columns:

station: id of the weather station
date: date of the record YYYYMMDD. Earliest date recorded: 20100101
max_temp: highest daily temperature in Celsius
min_temp: lowest daily temperature in Celsius
avg_temp: average daily temperature in Celsius
precipitation: daily precipitation in mm

stations.csv

All information related to the weather stations which measured the data

 01- 05 STAID  : Station identifier
 07- 46 STANAME: Station name
 48- 49 CN     : Country code (ISO3116 countrycodes)
 51- 59 LAT    : Latitude in degrees:minutes:seconds (+: North, -: South)
 61- 70 LON    : Longitude in degrees:minutes:seconds (+: East, -: West)
 72- 76 HGTH   : Station elevation in meters
