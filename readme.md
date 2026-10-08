# My Daily Walk Through App State

## Introduction
This map shows my daily walk on campus. I go from Kidd Brewer Stadium to Blue Deer on King Street and back again. I picked this walk because it is on campus and shows a very accessible place to walk. I think students could use it if they need a quick route from across campus to King Street.

## Major Functions
Major functions of the map include looking at campus. It gives you information on where things are, along with a quick and accessible route to get to King Street. You can also hover over the points to see landmarks along the route, and zoom and pan around the map.

## Libraries
- [Leaflet](https://leafletjs.com/) (version 1.9.4) - a JavaScript library used to build the interactive map, draw the route line and markers, and show the tooltips.

## Data Sources
- **Route:** Made with Google Maps walking directions, converted to a GPX file with [mapstogpx.com](https://mapstogpx.com/), and then to GeoJSON stored in `data/route.js`.
- **Basemap:** [OpenStreetMap](https://www.openstreetmap.org/) from Leaflet Providers. I used it because the suggested CartoDB.Positron basemap now requires an API key.

## Author
Joshua Turner
