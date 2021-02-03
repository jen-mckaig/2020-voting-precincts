# State Voting Precinct Files for BigQuery & Data Studio

Repo for 2020 state voting precincts or districts.  Each state shapefile has been converted into a [pseudo-GeoJSON CSV file](https://medium.com/google-cloud/how-to-load-geographic-data-like-zipcode-boundaries-into-bigquery-25e4be4391c8), a format that allows you to upload to BigQuery or use in Google Sheets. This file format can also be used with the Data Studio Community Visualization [Choromap](https://datastudio.google.com/u/0/reporting/4617cbac-3514-4c8d-a999-a3cb6683e579/page/N9GUB) built by [Michael Hodge](https://github.com/datasciencecampus/community-visualizations/tree/main/choromap) to easily map election outcomes. 

The shapefiles have been taken directly from the 2020 Census VTD files. If the VTD shapefiles were not included in the census data, they are extracted from the Secretary of State or a state geo-database. 

CA - includes precinct shapefiles from [2020 general primary](https://statewidedatabase.org/election.html)


