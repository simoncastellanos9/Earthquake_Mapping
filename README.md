# Earthquake mapping

### Purpose

This project's main purpose it to visualize earthquake data. For this, we want to plot a data set on your map to illustrate the relationship between tectonic plates and seismic activity.

### Methodology & Results

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. We visited the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and picked a data set to visualize. After clicking on a data set, we were given a JSON representation of that data. We used the URL of this JSON to pull in the data for our visualization.

![3-Data](Images/3-Data.png)



![4-JSON](Images/4-JSON.png)

We created a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude. The data markers reflect the magnitude of the earthquake by their size and and depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.

![5-Advanced](Images/5-Advanced.png)
