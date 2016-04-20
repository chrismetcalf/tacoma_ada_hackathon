#Data Sources for Hackathon

This list is a work in progress.  Please feel free to edit this data source list to improve what we have.

# OpenStreetMap Data
| Data Element  | Data Source   | Status   | Comments  |
|---|---|---|---|
| Wheel chair - Nodes  |[OSM Nodes](http://overpass-turbo.eu/s/fCp)   | Available  | Lots of data that needs to be further filtered  |


# Transit Data
| Data Element  | Data Source   | Status   | Comments  |
|---|---|---|---|
| [Transit Routes] (data/pierce_transit/pierce_transit_routes.geojson)  | Pierce Transit  | Available  |   |
| [Transit Schedules] (/data/pierce_transit/GTFS_2016_04_01.zip)  | Pierce Transit  | Available  | Available in [Google GTFS] (https://developers.google.com/transit/gtfs/reference) format  |
| [Transit Stops] (data/pierce_transit/pierce_transit_stop.geojson) | Pierce Transit | Available | |
| [Transit Boundary] (data/pierce_transit/pierce_transit_boundary.geojson) | Pierce Transit | Available  | |
| [Transit Centers] (data/pierce_transit/pierce_transit_centers_and_park_rides.geojson) | Pierce Transit | Available | |
| [Client scrubbed data for hackathon] (data/pierce_transit/hackathon_client_scrubbed.geojson) | Pierce Transit | Available ||
| [Ramps and Walkways] (https://services2.arcgis.com/fBDXdj7Zh91YF2mv/ArcGIS/rest/services/Sidewalks/FeatureServer) | Pierce Transit |[Check out the WebMap](https://piercetransit.maps.arcgis.com/apps/Viewer/index.html?appid=3cbc91e763634248af9c7d01de39acb3)|

<b>NOTE:</b>  There is more data in the two Esri File Geodatabases that were provided to the team from Pierce Transit.  These files exist here:

- [Esri File Geodatabase with ADA ramp information and more 1 of 2](https://github.com/GeoEngineers/tacoma_ada_hackathon/blob/master/data/pierce_transit/UWT_Hackathon.gdb.zip)
- [Esri File Geodatabase with ADA ramp information and more 2 of 2](https://github.com/GeoEngineers/tacoma_ada_hackathon/blob/master/data/pierce_transit/UWT_Hackathon2.gdb.zip)

# Transportation Data
| Data Element  | Data Source   | Status   | Format  |
|---|---|---|---|
| Pierce County Roads  | [Pierce County GIS](http://gisdata.piercecowa.opendata.arcgis.com/datasets/69c348eaed60458389f8d5c1fb3e5a1f_0 "Title")  |  Available  | GeoJSON, Esri Shapefile  |
| Pierce County Utility Data   | [Pierce County GIS](http://gisdata.piercecowa.opendata.arcgis.com/datasets?q=Utilities "Utilities")  | Available  | GeoJSON, Esri Shapefile   |



# Land Use Data
| Data Element  | Data Source   | Status   | Format  |
|---|---|---|---|
| Pierce County Taxlots  | [Pierce County GIS](http://gisdata.piercecowa.opendata.arcgis.com/datasets/6ccf2793657c493fa8623676a6dbc653_0)  | Available  | GeoJSON, Esri Shapefile  |
| City of Tacoma Zoning |[City of Tacoma, WA] (http://wspdsmap.ci.tacoma.wa.us/samples/zoning.zip) | Available | Esri Shapefile |
| City of Tacoma Mobility Master Plan (MoMaP) | [City of Tacoma, WA] (http://wspdsmap.ci.tacoma.wa.us/samples/MoMap.zip) | Available | Esri Shapefile

# Census Data
| Data Element  | Data Source   | Status   | Format  |
|---|---|---|---|
| Census 2010 Tracts  | [US Census](http://wspdsmap.ci.tacoma.wa.us/samples/censusblocks2010.zip)  | Available  | Esri Shapefile

## Full Datasets List
- OpenStreetMap http://www.openstreetmap.org/
- Pierce County, WA GIS data: http://gisdata.piercecowa.opendata.arcgis.com/
- City of Tacoma, Socrata data feed: https://data.cityoftacoma.org/
- City of Tacoma, GIS Data: https://www.cityoftacoma.org/government/city_departments/community_and_economic_development/geographic_information_systems__gis_/
- Transit data
-- Looks like Pierce County GTFS data is available but FTP does not resolve: https://code.google.com/archive/p/googletransitdatafeed/wikis/PublicFeeds.wiki

## Additional Datasets which may be of value
- Pierce County Open Data Portal http://gisdata.piercecowa.opendata.arcgis.com/
