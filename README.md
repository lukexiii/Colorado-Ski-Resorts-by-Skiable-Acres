# Colorado Ski Resorts by Skiable Acres

## About the Map
This map displays the 28 ski resorts of Colorado by skiable acres. The map was created as part of a web mapping class lab project and is designed to provide an interactive overview of the resorts by size, along with other important stats for each resort - displayed in each tooltip when hovering over the circle. The map also displays the runs and lifts of each resort when zoomed into them, providing additional functionality.

## Map Features
The web map includes:

The 28 ski resorts of Colorado, with graduated circles showing the resort size in skiable acres from smallest to largest
An interactive Leaflet basemap
A layer on the basemap showing the runs and lifts for each resort
A tooltip that pops up upon hovering over a circle, showing important resort stats

## Methods
The web map was created using HTML, CSS, and JavaScript, with the Leaflet JavaScript library used to create the interactive map. The ski resort data was gathered from a Wikipedia Article that compares the resort stats. The coordinates for each resort center point were gathered from Google Maps. The coordinates and data were then opened, edited, and exported as a GeoJSON file. That GeoJSON file was then used in the web map as the circle points and resort stats.

Leaflet was used to display the circles and provide the interactive mapping functionality, while HTML and CSS were used to structure and style the web page.

## Data Sources
The Ski Resort Data was gathered via Wikipedia: [Comparison of Colorado Ski Resorts](https://en.wikipedia.org/wiki/Comparison_of_Colorado_ski_resorts)

The basemap was found through [Leaflet Provider Demo](https://leaflet-extras.github.io/leaflet-providers/preview/) and is from [Stadia Maps](https://stadiamaps.com/).
The resort runs layer was also found through [Leaflet Provider Demo](https://leaflet-extras.github.io/leaflet-providers/preview/) and is from [OpenSnowMap.pistes](https://www.opensnowmap.org/).

Files
index.html – main webpage
data.geojson – coordinate/point data and info for the resorts
