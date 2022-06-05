# Overview

Basil and Sadhana like how you created your earthquake map with two different maps and the earthquake overlay. Now, Basil and Sadhana would like to see the earthquake data in relation to the tectonic plates’ location on the earth, and they would like to see all the earthquakes with a magnitude greater than 4.5 on the map, and they would like to see the data on a third map.

# Results

Using our knowledge of JavaScript, Leaflet.js, and geoJSON data, we added tectonic plate data using d3.json(), add the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and added the tectonic plate data to the overlay object with the earthquake data.

We then used the same methods to add major earthquake data to the map using d3.json(). We also added color and set the radius of the circle markers based on the magnitude of earthquake, and added a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().

!["Light Map"](https://github.com/rivas-j/mapping_earthquakes/blob/a0e107a625131aa00895160a18382b3d5dcad4ea/Earthquake_Challenge/resources/light_map.png)

!["Dark Map"](https://github.com/rivas-j/mapping_earthquakes/blob/a0e107a625131aa00895160a18382b3d5dcad4ea/Earthquake_Challenge/resources/dark_map.png)
