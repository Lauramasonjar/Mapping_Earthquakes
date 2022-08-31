# Mapping_Earthquakes

## Project Overview

For this project we are creating an interactive map that shows the latest earthquake activity around the world. 

## Purpose
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

Our approach will be to use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. We will also use the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.


## Requirements

-	Overlay object for **Tectonic plates**.
-	Overlay object for **Earthquakes of the past 7 days**.
-	Overlay object for **Major earthquakes of magnitude above 4.5**.
-	Three different **map styles**:
    - Street view.
    - Satellite view. 
    - Dark view.
-	**A popup marker** with information about the location and magnitude of the earthquake.
-	**The radius** and **the color** of a marker reflect the earthquake intensity.
-	**A legend** with the context for the map.

#
**Tectonic Plate Data**



Tectonic plates are pieces of Earth's crust and uppermost mantle, together referred to as the lithosphere. The plates are around 100 km (62 mi) thick and consist of two principal types of material: oceanic crust (also called sima from silicon and magnesium) and continental crust (sial from silicon and aluminium). [Ref-Wikipedia](https://en.wikipedia.org/wiki/List_of_tectonic_plates#:~:text=Tectonic%20plates%20are%20pieces%20of,sial%20from%20silicon%20and%20aluminium)

#

**Major Earthquake Data**

- The earthquake intensity, darker color with larger diameter represents earthquakes with a higher magnitude.

![Mapping_Earthquakes](https://github.com/Lauramasonjar/Mapping_Earthquakes/blob/main/Mapping%20Earthquakes.png)

#

**Additional Map styles**
- Satellite view. 
- Dark view.




## Resources

**Data Source:**

- GeoJson file for Tectonic Plates retrieved from GitHub repository: https://github.com/fraxen/tectonicplates/tree/master/GeoJSON
- GeoJson file for earthquakes for the past 7 days retrieved via API call from USGS website: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
- GeoJson file for Major Earthquakes (M4.5+) for the past 7 days via API call from USGS website: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

- **GeoJson** files that are specifically designed to host geographical information. GeoJson files are the industry standard for representing simple geographical features, such as points, linestrings and polygons and non-spatial attributes, such as magnitude of the earthquake, hurricane strength, hail size, elevation, etc.

**Software:**
- Mapbox API [challenge_logic.js](Earthquake_Challenge/static/js/challenge_logic.js)
    -  An open-source mapping platform for custom designed maps. 

- VS Code and Chrome Developer Tools


**Languages:**
- JavaScript, 
- [HTML](Earthquake_Challenge/index.html) and [CSS](Earthquake_Challenge/static/css/style.css) 

**Libraries:**
- D3
- Leaflet
    - A JavaScript library, designed to build the web mapping applications.
