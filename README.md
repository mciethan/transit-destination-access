# transit-destination-access

Data processing and analysis for [Measuring the Destination Access and Equity Impacts of 
Public Transit Service Changes](https://docs.google.com/document/d/1rZ53ZGgcFSwCZZcrQuP_10jydLrTczdVK5aa1SwKZlw/edit?usp=sharing), a case study of Title VI policy at the MBTA that I completed in spring 2025 
in partial fulfillment of my MS in Urban Informatics at Northeastern University.

### Key Data Sources

- public transit schedules in General Transit Feed Specification (GTFS) format
- total population per census block from decennial US census
- total jobs per census block from US Census LODES program
- OpenStreetMap travel network data

### Key Methods

- daily "quantity-of-service" calculations (e.g., total trips, revenue vehicle hours & kilometers) using SQL queries on GTFS feeds
- origin-destination network analysis (transit + walking) using `r5r` package
- destination access measures using `accessibility` package

### Abstract

Public transportation agencies that receive federal funding in the United States are obligated under Title VI of the Civil Rights Act to ensure that changes to transit service do not disproportionately burden populations of color or low-income households.  However, existing Title VI policies only require that agencies analyze the social equity impacts of large-scale, often pre-planned changes, such as new or extended routes. The equity impacts of the often smaller-scale service changes to multiple routes that transit agencies make on a regular basis in response to operating conditions have attracted limited attention in the research literature. 

Using a case study of eight service changes implemented by the Massachusetts Bay Transportation Authority (MBTA) between December 2022 and December 2024, this study demonstrates that regular service changes can sometimes have substantial and racially disparate impacts on job access, in some cases even exceeding the impacts of the “major” projects that are covered by existing Title VI policies. The results also suggest that “quantity-of-service” measures like revenue vehicle hours, widely used in current Title VI policies to define “major” changes and disparate impacts, are flawed indicators of the user benefits and burdens of transit service changes, with measures of destination accessibility representing a more robust alternative.  Expanding the scope of transit service change equity policies and using more robust threshold measures to operationalize them can help ensure that the sometimes substantial equity impacts of regular service changes are addressed and mitigated.

