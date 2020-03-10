** Check what the dataset is about. It is a 2015 data about five different counties in New York State and 
in New York-Newark-Jersey City, NY-NJ-PA Metro Area. 
To know the exact county and area, we need to introduce another dataset (census data with geoid and countyflips)

** Since the dataset is about the same state and metro area, so it would make sense to use columns that 

** In order to map the data, we could use a shapefile of New York with geoid information.
https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.2015.html
https://www.census.gov/cgi-bin/geo/shapefiles/index.php
https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2015&layergroup=Census+Tracts

** Join by attribute (geoid)

** color different block according to COI national and metro, find out that New York Metro Area 

** explanation of data 
http://diversitydatakids.org/sites/default/files/2020-01/ddk_coi2.0_technical_documentation_20200115-1.pdf

** household income by census Tracts
https://datausa.io/profile/geo/nassau-county-ny
https://datausa.io/profile/geo/suffolk-county-ny
https://datausa.io/profile/geo/new-york-ny

** New York State household income standards:
https://statisticalatlas.com/state/New-York/Household-Income
Use national standards

** New York State shapefile
http://gis.ny.gov/gisdata/inventories/details.cfm?DSID=927

** Things to notice in the original data:
Note that we did not use absolute thresholds based on opportunity score values to distinguish areas by 
levels of opportunity. For instance, if we used absolute thresholds we would classify areas as high 
opportunity if they had opportunity scores above a certain numeric value threshold that was deemed “high” 
(e.g., opportunity scores that are 2 or more standard deviation above aver- age). Instead, the opportunity 
levels were based on ranking a given set of census tracts from low- est to highest and then sorting them 
into different categories. Because this approach was based on rankings and percentiles based on a specific 
set of tracts, the opportunity level of a given tract de- pends on the set of tracts included in the 
rank- ings. While they tend to be highly correlated, this is why nationally and metro- or 
state-standard- ized opportunity levels generally differ, because the former uses all tracts 
in the U.S. to define per- centiles for opportunity levels, while the latter only uses tracts 
in a given metro area or state.

** I struggled to categorize income levels into five categories without taken account into the population.
But according to the text above, the intention of the model is to compare tracts within the state. So if my 
standards are set to compare within the state, the two can compare to each other.

** In Long Island, Income gap leads to unequal opportunity for children
    In Long Island, children in poorer neighborhoods get less oppotunities 


