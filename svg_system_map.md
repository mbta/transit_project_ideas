# Image of System Map

## Author
[Frank LaNasa](https://github.com/fjlanasa)

## Description

Scalable Vector Graphics (SVG) is a markup language for describing two-dimensional vector graphics (essentially computer graphics defined by connected points on a plane). SVG underlies many popular data visualization libraries like [D3js](https://d3js.org/), but can be used on it’s own to [make simple charts and graphs](https://css-tricks.com/how-to-make-charts-with-svg/). Using vanilla SVGs and HTML, build a simple two-dimensional visualization of one or more of our routes, similar to the [MBTA’s rapid transit map](https://cdn.mbta.com/sites/default/files/2020-05/subway-map-june2020-v34a-GLX-shuttle.pdf).

![System Map](https://ctd-static-content.s3.amazonaws.com/github-images/system-map.png)

## Data Sources

- The MBTA’s [V3 API](https://api-v3.mbta.com/) provides endpoints to fetch information about [routes](https://api-v3.mbta.com/docs/swagger/index.html#/Route/ApiWeb_RouteController_index) and route [shapes](https://api-v3.mbta.com/docs/swagger/index.html#/Shape/ApiWeb_ShapeController_index). Note that the shapes endpoint returns encoded [polylines](https://developers.google.com/maps/documentation/utilities/polylinealgorithm), so you’ll need to use some tool to decode them (one example here).
- The MBTA’s [GTFS Feed](https://github.com/mbta/gtfs-documentation/blob/master/reference/gtfs.md) also provides equivalent information in the form of text files:
    - [routes.txt](https://developers.google.com/transit/gtfs/reference#routestxt)
    - [shapes.txt](https://developers.google.com/transit/gtfs/reference#shapestxt)

## Level
Beginner
