# Calls-for-Service-City-of-New-Orleans
This repository contains the R code to import all of the calls for service data from the City of New Orleans' open data site, concatenate the data into one database, and clean the TypeText column of the data.

We will be updating this ReadMe as the project develops.

Between Steps 1 and 2, I bring the data into QGIS to convert the GPS coordinates. In the data on the open source site, 
GPS coordinates are given in NAD83 format. I convert to WGS84 for analysis in Tableau and for consistency with more 
popular tools.
