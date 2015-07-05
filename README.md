# EscherichiaChoropleth
Georgia Tech: CS4460 Intro to Data Visualization: Inseok Huang, Raghav Kaul, Sung Im

**Download instructions: **
Clone the repository into a directory of your choice. Unzip the file and change into the newly created directory. Open the html file.

## Choropleth Projection
Choropleth map using U.S. county data from U.S. Census Bureau. Currently assigns random color value for each county within the range of color sequence defined in the css selection.

## File Description
**us_sung.json** 

This file is a TopoJSON file created using GDAL to filter and convert the original shape-file to GeoJSON format and TopoJSON to then convert the GeoJSON to TopoJSON format setting the object identifiers as the FIPS county codes.

The shape-files (.shp) were downloaded from the U.S. Census Bureau website:

[U.S. Census Bureau](http://www.census.gov/geo/maps-data/data/tiger-line.html)

**index.html**

The main display of the visualization. Uses the example color sequence from Bostock's choropleth example at 

[D3JS Website](d3js.org)
