# Mapping Earthquakes with Javascript

<div align="center">
    <img src=images/image.jpg>
</div>

## <div align="center">Short blurb describing what the tool does</div>

<p align="center">
<a href="#goals">Goals</a> &nbsp;&bull;&nbsp;
<a href="#dataset">Dataset</a> &nbsp;&bull;&nbsp;
<a href="#tools-used">Tools Used</a> &nbsp;&bull;&nbsp;
<a href="#analysis-and-challenges">Analysis and Challenges</a> &nbsp;&bull;&nbsp;
<a href="#results">Results</a>
</p>

# <div align="center">Goals</div>

The clients want an earthquake map with two different maps and the earthquake overlay. I'll build that interactive map with Javascript and utilize D3.js to perform API calls. This API allows me to add arthquake data in relation to the tectonic plates’ location on the earth - prioritizing earthquakes with a magnitude greater than 4.5 on the map.

# <div align="center">Dataset</div>

High level explanation of data source

- [Data Set File Name:](data/data_source.format) Explain source of file, size of dataset and format

# <div align="center">Tools Used</div>
- **Tool 1:** Tool purpose
- **Tool 2:** Tool purpose

# <div align="center">Results</div>

Using our knowledge of JavaScript, Leaflet.js, and geoJSON data, we added tectonic plate data using d3.json(), add the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and added the tectonic plate data to the overlay object with the earthquake data.

We then used the same methods to add major earthquake data to the map using d3.json(). We also added color and set the radius of the circle markers based on the magnitude of earthquake, and added a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().

!["Light Map"](images/light_map.png)

!["Dark Map"](images/dark_map.png)

[Back to top](#mapping-earthquakes-with-javascript)
