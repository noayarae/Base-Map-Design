# Base-Map-Design
This repository stores base-map designs from Mapbox

Spring term | Geovisual Analytics 572

By **Efrain Noa-Yarasca**

## 1. Map 1. Interactive US-Population Map
The first map involves a base map and an interactive presentation of US-Population by states.
### 1.1 Base-map
The base map was set up in Mapbox considering the "outdoors" map. Here, several editions were elaborated. The background-color was was setup green and pink.  Crop lands were filled by crop icons and forest areas by tree icons. Zooming the cities, one can see editions on principal and secondary roads such as color, opacity.
Buildings were setup to appear when zooming and disappear when zoom-out.
### 1.2 Interactive presentation
Regarding map-interactive presentation, this map shows an friendly presentation of population of any US-state. When moving the mouse over any state, its area will be highlighted and the state's name and 2016-population will be shown.
To prepare this interactive map, a US-map having population by states was added in GeoJson format.
A JavaScript code was developed to achieve this nice presentation.  


## 2. Map 2. US-Routes Map

This map clearly shows main routes in the US. The main highways were colored by red, next level of routes by pink and so on. This map also highlights green areas, park areas and crop lands. Markers in Corvallis show some pictures once they are clicked.

### 2.1 Base-map
The base map was set up in Mapbox considering the "streets" map. Here, several editions were elaborated.

Highways were colored with dark red when zoom-in and light red when zoom-in. Next level of roads was colored by dark pink when zoom-in and yellow when zoom-out. Third level of roads were colored by dark orange when zoo-in and white when zoom-out. Pedestrian paths were colored by red and dotted lines. They are displayed only when zoomed-in. Buildings and residential houses were colored by black and brown.
Airports were clearly identified by highlining its name and runway.
Hospitals were filled by cross icon
National parks were colored by dark green, and crop lands by light green.
Water bodies were colored by dark blue.
Names of main cities were put on uppercase and colored by red to see easily. Name of towns were colored also colored by red and setup as italic.

### 2.2 Interactive presentation
Pictures were loaded on the map to show some places of Corvallis. The user can click the marker and a picture will popup. This was achieved by using markers and a GeoJson file having coordinates and features.
