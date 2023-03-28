# Tableau_InfluxDBCloud_IOx
Parquet files, parquet to hyper file conversion script, hyper file for data ingestion into Tableau. 

## Requirements
- A Tableau account. Sign up for a free trial [here](https://www.tableau.com/trial/tableau-software)

## Contents
1. airsensors.parquet: The parquet file contains data from InfluxDB Cloud powered IOx. Querying for parquet files directly isn't currently publically available but is on the roadmap. 
2. create_hyper_file_from_parquet.py: A python script that produces a hyper file for data ingestion into Tableau. 
3. airSensors.hyper: The resulting hyper file from the conversion. 
4. airSensors.twb: A Tableau Work Book to visualize time series dadta from the [Air Sensor Sample Dataset](https://github.com/influxdata/influxdb2-sample-data/blob/master/air-sensor-data/air-sensor-data.lp).
 

