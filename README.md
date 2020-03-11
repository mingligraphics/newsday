Income and Child Opportunity Level:

You can see the project published on: https://mingligraphics.github.io/newsday/

**** About The Data:

I narrow both the income and Chidren Opportunity Score/Level data to Long Island census tracts. Both of them are measured at the national level so that they are comparable.

* In order to map the data, we could use a shapefile of New York with geoid information.
https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.2015.html
https://www.census.gov/cgi-bin/geo/shapefiles/index.php
https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2015&layergroup=Census+Tracts

** Household income by census Tracts
https://datausa.io/profile/geo/nassau-county-ny
https://datausa.io/profile/geo/suffolk-county-ny
https://datausa.io/profile/geo/new-york-ny

** New York State household income standards:
https://statisticalatlas.com/state/New-York/Household-Income (Use national standards)

** New York State shapefile
http://gis.ny.gov/gisdata/inventories/details.cfm?DSID=927

**** How Did I Make The Graphics:

I used Pandas to build and merge my dataframes. I used seaborn to plot the chart. The two maps were created in Qgis and then I threw everything in Adobe illustrator to make them prettier. I used sawhorse to build the whole page.

**** Limitation About The Project:

1. The household income is perhaps one of the underlying indicators of the Children Oppotunity Index itself, so the findings may not be very suprising. In a way, it emphasizes the high correlation between economic status and children's opportunity level.

2. For the map, I tried to categorize Long Island income levels into five categories based on the national standard. However, the "very high", "high" or "low" classification is somewhat subjective.




