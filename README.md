# -leaflet-challenge
The instructions for this activity are broken into two parts:

Part 1: Create the Earthquake Visualization
The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON FeedLinks to an external site. page and choose a dataset to visualize
When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization.
Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.

Hint: The depth of the earth can be found as the third coordinate for each earthquake.

Include popups that provide additional information about the earthquake when its associated marker is clicked.

Create a legend that will provide context for your map data.

Your visualization should look something like the preceding map
Requirements
These requirements apply only to "Part 1: Create the Earthquake Visualization" 

**Map**
TileLayer loads without error 

Connects to geojson API using D3 without error

Markers with size corresponding to earthquake magnitude 

A legend showing the depth and their corresponding color 

**Data Points**
Data points scale with magnitude level

Data points colors change with depth level 

Each point has a tooltip with the Magnitude, the location and depth (10 points)

All data points load in the correct locations 
