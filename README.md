# leaflet-challenge

**Leaflet-Step-1**

This project creates an interactive map using Leaflet.js to visualize earthquake data from the USGS GeoJSON feed. It begins by defining a basemap layer using OpenStreetMap tiles, which serves as the map's background. The map is centered on San Francisco with a configurable zoom level. Earthquake data is dynamically fetched and displayed as circle markers, styled based on their magnitude and depth. Each marker's color represents the earthquake's depth, and its size reflects the magnitude. Popups provide detailed information about the magnitude and location of each earthquake. Additionally, a legend is added to explain the depth-based color coding, ensuring the map is informative and visually engaging. This project highlights how to combine real-time geospatial data with customizable, interactive map features.

**Leaflet-Step-2**

This project demonstrates the creation of an interactive map using the Leaflet.js library. The map visualizes earthquake data from the USGS Earthquake GeoJSON feed and tectonic plate boundaries from a public dataset. Additionally, it provides various customization and interactivity features, such as layer controls, popups, and a legend. Below is a breakdown of the key functionalities and steps:

**Features**

**1.	Basemap and Street Map Layers:**
o	A basemap layer is created using OpenStreetMap tiles, which provides a general geographical layout as the background of the map.
o	An optional street map layer, styled by the Humanitarian OpenStreetMap Team (HOT), serves as an alternate background option for a different perspective.

**2.	Interactive Map Initialization:**
o	The map is initialized with a center point (latitude and longitude) and a default zoom level.
o	The basemap is added as the default layer on map load.

**3.	Layer Groups and Controls:**
o	Two layer groups, earthquakes and tectonicPlates, are created to hold the earthquake markers and tectonic plate boundaries.
o	Layer controls allow users to toggle between the basemap and street map, as well as enable or disable the display of earthquake and tectonic plate data.

**4.	Earthquake Data Visualization:**
o	Earthquake data is fetched from the USGS GeoJSON feed.
o	Each earthquake is represented as a circle marker on the map, with:
	Color determined by the depth of the earthquake (shallow to deep).
	Radius determined by the earthquake's magnitude.
o	Popups provide additional information about each earthquake, such as magnitude and location.

**5.	Legend:**
o	A legend is added to explain the color coding for earthquake depths. Depth intervals are represented by color boxes to enhance understanding.

**6.	Tectonic Plate Boundaries:**
o	Tectonic plate boundary data is fetched from a GeoJSON file and displayed as orange lines on the map.
o	The tectonic plate layer can be toggled on or off independently of the earthquake layer.

