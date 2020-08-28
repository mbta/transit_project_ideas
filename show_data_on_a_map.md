# Show data on a map

## Author
[Sky Rose](https://github.com/skyqrose)

## Description

Use a [Leaflet](https://leafletjs.com/) map to show data about MBTA service. There are a lot of things with latitudes and longitudes that could be shown. Bus stops, where vehicles are now, elevators, the shapes of routes, etc.

Features you could add on top of this:
- Allow the user to decide which kinds of data are shown or only show buses on specific routes.
- Click on something to learn more about it. E.g. click on a bus to see how crowded it is or click on a bus stop to see its name. Whatever extra information you think would be interesting.


## Data sources
- MBTA’s [V3 API](https://www.mbta.com/developers/v3-api) is the easiest place to get realtime and static data. 
- If you want to load all the data at once, MBTA’s [GTFS](https://www.mbta.com/developers/gtfs) data might be easier. However, it’s only static data. To get all the realtime vehicle data, you’d also have to use the [GTFS-realtime feed](https://www.mbta.com/developers/gtfs-realtime) too.
- You might find other interesting mappable data in the [Open Data Portal](https://mbta-massdot.opendata.arcgis.com/)
The [Leaflet](https://leafletjs.com/) website has information on how to make a map in javascript, and if your app is a React app, the [React-Leaflet](https://react-leaflet.js.org/) package will make using it easier.


## Level
Beginner
