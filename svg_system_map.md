# Image of System Map

## Author
[Frank LaNasa](https://github.com/fjlanasa)

## Description

Scalable Vector Graphics (SVG) is a markup language for describing two-dimensional vector graphics (essentially computer graphics defined by connected points on a plane). SVG underlies many popular data visualization libraries like D3js, but can be used on it’s own to make simple charts and graphs. Using vanilla SVGs and HTML, build a simple two-dimensional visualization of one or more of our routes, similar to the MBTA’s rapid transit map.

Image of System Map

## Data Sources

The MBTA’s V3 API provides endpoints to fetch information about routes and route shapes. Note that the shapes endpoint returns encoded polylines, so you’ll need to use some tool to decode them (one example here).
The MBTA’s GTFS Feed also provides equivalent information in the form of text files:
routes.txt
shapes.txt

## Level
Beginner
