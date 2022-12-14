## Introduction to WEkEO Notebooks


#### CMEMS Reanalysis: Seasonal and Annual Trends of the Sea Surface Temperature in the Adriatic Sea.
The Sea Surface Temperature (SST) is an important physical characteristic of the oceans. The Adriatic Sea is an elongated basin, located in the central Mediterranean, between the Italian peninsula and the Balkans.The CMEMS Mediterranean Sea Physics Reanalysis time series is provided from 01/01/1987 to 31/12/2019. The SST is defined by selecting the first vertical level of the daily mean of Potential Temperature within the variable name “thetao” and downloaded from this [link](https://resources.marine.copernicus.eu/product-download/MEDSEA_MULTIYEAR_PHY_006_004).  

#### Accordingly, the input “CMEMS_SST” in the netCDF format is prepared to display Seasonal and Annual Maps together with Trends and Anomalies. The Spatial data for the Area of Interest is called “areaAdriatic” in the CSV format. 
The Input Data “CMEMS_SST.nc” and “areaAdriatic.csv” are present in the following [link](https://drive.google.com/drive/u/0/folders/1D1kQBpmnS4r2Dhq7f8bkhWXC_WF8gIkD).

## CONTENTS of the Jupyter Notebook:

1) Section 1: Data processing: CMEMS Data.

#### THE CODE SECTIONS:

2) Section 2: Functions for the Data Aggregation process: Annual, Winter and Summer Seasons Aggregations.
3) Section 3: The SST Data Analysis and Plots: Daily, Monthly, Annual Trends and Standard Deviation.
4) Section 4: The Seasonal and Annual Mean Map Visualizations.
5) Section 5: The Seasonal Anomalies Map Visualizations.
6) Section 6: References.



There are two sections of code at the top that occure before entering the main programme and includes:

1. importing modules
2. "functions_cmems.py" file which contains functions that are called in the main programme

The "functions_cmems.py" file contains calling functions to provide necessary methods for the data elaboration.
Therefore, in the initial part contains the specific functions for the aggregations and, continuing with data analysis and visualization functions and finally calculation and visualization of seasonal anomalies functions.
