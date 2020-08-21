# GTFS Timetable

## Description
Use the MBTA’s [GTFS Feed](https://www.mbta.com/developers/gtfs) to make a website that displays timetables for a route with trips on a given day. You can use as inspiration the commuter rail timetables displayed on [mbta.com](https://www.mbta.com/schedules/CR-Fairmount/timetable).

Image of Timetable

## Data Sources
The [MBTA’s GTFS](https://github.com/mbta/gtfs-documentation/blob/master/reference/gtfs.md) Feed consists of a series of [text files in a standard format](https://developers.google.com/transit/gtfs/reference) that represent the system’s static schedule (along with other geographic information). For this project, the files of interest are:
- [calendar.txt](https://developers.google.com/transit/gtfs/reference#calendartxt)
- [calendar_dates.txt](https://developers.google.com/transit/gtfs/reference#calendar_datestxt)
- [routes.txt](https://developers.google.com/transit/gtfs/reference#routestxt)
- [route_patterns.txt](https://github.com/mbta/gtfs-documentation/blob/master/reference/gtfs.md#route_patternstxt)
- [trips.txt](https://developers.google.com/transit/gtfs/reference#tripstxt)
- [stop_times.txt](https://developers.google.com/transit/gtfs/reference#stop_timestxt)
- [stops.txt](https://developers.google.com/transit/gtfs/reference#stopstxt)

## Level

Beginner 

Image of System Map

## Description

Scalable Vector Graphics (SVG) is a markup language for describing two-dimensional vector graphics (essentially computer graphics defined by connected points on a plane). SVG underlies many popular data visualization libraries like D3js, but can be used on it’s own to make simple charts and graphs. Using vanilla SVGs and HTML, build a simple two-dimensional visualization of one or more of our routes, similar to the MBTA’s rapid transit map.

## Data Sources

The MBTA’s V3 API provides endpoints to fetch information about routes and route shapes. Note that the shapes endpoint returns encoded polylines, so you’ll need to use some tool to decode them (one example here).
The MBTA’s GTFS Feed also provides equivalent information in the form of text files:
routes.txt
shapes.txt

## Level
Beginner
