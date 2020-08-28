# Performance Analysis Project Ideas

## Author
[Eddie Maldonado](https://github.com/lemald)

## Description
We provide some very high-level performance statistics about the MBTA on the [mbtabackontrack.com](https://mbtabackontrack.com/) website. Many of these statistics are useful, but top-level “on-time performance” doesn’t capture the entire reality that our riders experience. With some simple querying from the [V3 API](https://api-v3.mbta.com/docs/swagger/index.html) and data storage and lookup, we can do even more in-depth analysis to identify problem spots and potential solutions.

## Data Sources
The [V3 API](https://api-v3.mbta.com/docs/swagger/index.html) contains a lot of information, but in particular, it has vehicle positions, predictions, and schedules. The vehicles’ locations along a specific route can be queried periodically (or streamed!) fairly easily without hitting our default API key cap. The results of these queries can then be stored, for instance, in a simple SQL database.

## Use Cases
Once you have this data, you can build a front-end to analyze it in many ways.
Identify instances of “bunching” - one vehicle running extremely close behind another - and its twin, “gapping.”
Find particularly slow spots along routes - intersections where buses spend a lot of time waiting for a light, for instance.
Compare actual data to the schedule to determine how frequently trips get dropped (validity of this may depend on how consistently we track vehicles on different modes, though).

## Level

Intermediate to advanced. It requires a persistent process to scrape the API periodically, which may be an unfamiliar exercise for new developers who have mostly worked within a web framework. It also requires more understanding of transit operations than some other ideas might.
