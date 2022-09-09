# Mapping_Earthquakes
Visually show the differences between the magnitudes of earthquakes all over the world for the last seven days (add data to a geographical map) 

## Overview of Project
To complete this project, we used a URL for GeoJSON earthquake data from the USGS website and retrieved geographical coordinates and the magnitudes of earthquakes for the last seven days. Then, we added the data to a map. Our approach was to use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. Then we used the Leaflet library to plot the data on a Mapbox map through an API request and created interactivity for the earthquake data. (set up Mapbox account to get API token needed to create geographical maps)

We created our earthquake map with two different maps (*street*, *satellite*) and the *earthquake overlay*. In addition, we want to see the earthquake data in relation to the tectonic plates' location on the earth, and the earthquakes with a magnitude greater than 4.5 on the map. The purpose of this project was to create a map with the following three baseMap styles: *street*, *satellite*, and *dark*, and three overlays: *Earthquakes*, *Tectonic Plates*, and *Major Earthquakes*.



![Three map styles (3 displays)](https://user-images.githubusercontent.com/107021231/189285491-5f532afe-3062-447e-b7a6-edc4310069d4.png)
