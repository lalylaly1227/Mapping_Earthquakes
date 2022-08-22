# Mapping_Earthquakes

## Project Overview
The purpose of this challenge was to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.  We were to use maps to demonstrate earthquake data. We needed to use different layers to showcase the earthquakes, major earthquakes as well as the teconic plates.  The maps can also toggle between the street view, the satellite view and the dark view.  We will use javascript (GeoJSON) to create interactive maps to visualize this data. To complete this project, we need to use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map using the logic_challenge.js file.

## Results
The map can be viewed and it is interactive. Each earthquake is visually represented by a circle and a color scale, where a higher magnitude will be shown by a larger diameter and will be darker in color. Additionally, each earthquake has a popup marker that, when clicked, shows the magnitude of the earthquake and the location of the earthquake. The map has three views: Street View, Satellite View, and Dark View as well as a legend.

The viewer is able to toggle between the three layers to filter the data. These layers include: All Earthquakes, Tectonic Plates, and Major Earthquakes (greater than 4.5 magnitude)

![Challenge Results](https://user-images.githubusercontent.com/105124485/185832622-ade28386-243e-497c-a180-69c4c7a3b76d.png)

## Summary
To create the maps we used the JavaScript and the D3.js libraries and GeoJSON data to retrieve the coordinates and magnitudes of the earthquakes. We then needed the Leaflet library to plot the data on a Mapbox map through an API request and create interactive maps for the earthquake data. 
