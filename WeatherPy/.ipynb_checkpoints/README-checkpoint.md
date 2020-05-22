# Python-API

## Overview

Created a Python script to visualize the weather of +500 cities across the world of varying distances from the equator.  API keys used to gather data and the Matplotlib library utilized to build scattered plots.

## Scattered Plots
A series of scatter plots built to showcase the following relationships:

### Temperature (F) vs. Latitude

![](Lat_vs_Temp.png)

### Humidity (%) vs. Latitude

![](Lat_vs_Humidity.png)

### Cloudiness (%) vs. Latitude

![](Lat_vs_Cloud.png)

### Wind Speed (mph) vs. Latitude

![](Lat_vs_Wind.png)

## Gmaps

Jupyter-gmaps and the Google Places API used to develop a global heat map visualizing world-wide temperatures.  Pandas DataFrames narrowed down to include:

Max temperatures between 70-80 degrees, wind speeds less than 10 mph and zero cloudiness.

![](Heatmap_Layer.png)

Used Google Places API to find the first hotel for each city located within 5000 meters of specified coordinates.  Hotel locations marked and layered above the heatmap providing the Hotel Name, City, and Country.

![](Marker_Heatmap_Layer.png)
