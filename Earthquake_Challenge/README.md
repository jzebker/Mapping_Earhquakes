# Earthquake Challenge
[challenge_logic.js](https://github.com/jzebker/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/js/challenge_logic.js)

<sup>in index.html src="static/js/config.js" mapbox access token is not included - format: API_KEY = "xxxxxxx"</sup>
## Background
Basil and Sadhana like how you created your earthquake map with two different maps and the earthquake overlay. Now, Basil and Sadhana would like to see the earthquake data in relation to the tectonic plates’ location on the earth, and they would like to see all the earthquakes with a magnitude greater than 4.5 on the map, and they would like to see the data on a third map.
## Deliverable 1: Add Tectonic Plate Data
• The tectonic plate data is added as a second layer group
<p align="center"><img src='https://github.com/jzebker/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/img/2ndlayer.png?raw=true' /></p>

• The tectonic plate data is added to the overlay object
<p align="center"><img src='https://github.com/jzebker/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/img/2ndoverlay.png?raw=true' /></p>

• The d3.json() callback is working
<p align="center"><img src='https://github.com/jzebker/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/img/2ndd3json.png?raw=true' /></p>

• The map works

## Deliverable 2: Add Major Earthquake Data
• The major earthquake data is added as a third layer group
<p align="center"><img src='https://github.com/jzebker/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/img/3rdlayer.png?raw=true' /></p>

• The major earthquake data is added to the overlay object
<p align="center"><img src='https://github.com/jzebker/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/img/3rdoverlay.png?raw=true' /></p>

• The d3.json() callback is working
<p align="center"><img src='https://github.com/jzebker/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/img/3rdd3json.png?raw=true' /></p>

• The map works

## Deliverable 3: Add an Additional Map
• A third map tile layer is created
<p align="center"><img src='https://github.com/jzebker/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/img/3rdtilelayer.png?raw=true' /></p>

• The third map is added to the overlay object
<p align="center"><img src='https://github.com/jzebker/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/img/totallegend.png?raw=true' /></p>

• Example of working map - Dark Map, Plate Boundaries, and Major Earthquakes toggled ON
<p align="center"><img src='https://github.com/jzebker/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/img/workingmap.png?raw=true' /></p>
