---
mapCalc1: 0.17761989342806395
map_height_y: 6185
map_width_x: 4231
scale_pixels: 563
scale_pixels_range: 100
---

```leaflet
id: whiteteeth_1 ### Must be unique with no spaces
image: [[The Whiteteeth Peninsula.webp]] ### Link to the map image file
bounds: [[0,0], [4231, 6185]] ### Size of the map in px Width_x, Height_y
height: 1000px ### Size of the leaflet embed in px on your screen
width: 95% ### Size of the leaflet embed in your note
lat: 3093 ### To center the map, make this half of the map width. 
long: 2116 ### To center the map, make this half of the map height. 
minZoom: -1.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level. 
maxZoom: 1 ### Controls how far towards the map you can zoom in.  Hover over the target icon to see the current level. 
defaultZoom: -1 ### Sets the default zoom level when the map loads.  Hover over the target icon to see the current level. 
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out. 
unit: km ### The value displayed when measuring so you know what type of unit is being measure.
scale: 0.17761989342806395 ### Real units/px (resolution) of your map
recenter: true
darkmode: false ### marker
```

> [!NOTE]- Quick Calculator
> Map Height in Pixels: `INPUT[number:map_height_y]`
Map Width in Pixels: `INPUT[number:map_width_x]`
lat: `VIEW[{map_height_y} / 2][math]` 
long: `VIEW[{map_width_x} / 2][math]` 
How Many Pixels In Scale: `INPUT[number:scale_pixels]`
How Many Units in Scale: `INPUT[number:scale_pixels_range]`
Scale: `VIEW[1/({scale_pixels}/{scale_pixels_range})][math:mapCalc1]`
