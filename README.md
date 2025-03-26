# transit-destination-access

Data processing and analysis for "Measuring the Destination Access Impacts of 
Public Transit Service Adjustments", a research project I completed in spring
2025 in partial fulfillment of my MS in Urban Informatics at Northeastern University.

[add link to full report when available]

### Key Data Sources

- public transit schedules in General Transit Feed Specification (GTFS) format
- total population per census block from decennial US census
- total jobs per census block from US Census LODES program
- OpenStreetMap travel network data

### Key Methods

- daily "quantity-of-service" calculations (e.g., total trips, revenue vehicle hours & kilometers) using SQL queries on GTFS feeds
- origin-destination network analysis (transit + walking) using `r5r` package
- destination access measures using `accessibility` package

