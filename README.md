# Earthquake-Geomapping
Uses Leaflet.js to plot recent earthquakes on a map

![sample map](https://github.com/ejhagee/Earthquake-Geomapping/blob/master/images/map.png)

### Description
Science tells us that most earthquakes occur mostly along tectonic plate boundaries.  This project aims to map this trend.

Here, Leaflet.js is used for the geomapping of earthquakes in the last week.  The earthquakes data for the last seven days is retrieved from the [United States Geological Survey](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php).  As well, the outlines of tectonic plates are mapped, found [here](https://github.com/fraxen/tectonicplates).

Maps were retrieved from [Mapbox](https://www.mapbox.com/).  The retrieval requires an API-KEY.

### File Structure
 - index.html will display the map
 - static/css has one file, style.css which is used to set map margins
 - static/js contains the app.js file which contains the JavaScript code that creates the map
 - README.md is this file which contains a brief description
