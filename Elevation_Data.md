# Elevation Data

## Formats

### DTED
Digital Terrain Elevation Data (DTED®) is a standard mapping format designed by the NGA. Each file or cell contains a matrix of vertical elevation values spaced at regular horizontal intervals measured in geographic latitude and longitude units. File size is approximately 25 MB for 1-arc-second data files and approximately 3 MB for 3-arc-second data files.

### BIL
Band interleaved by line (BIL) is a binary raster format with an accompanying header file which describes the layout and formatting of the file. File size is approximately 7 MB for 1-arc-second data files and approximately 1 MB for 3- arc-second data files.

### GeoTIFF
Georeferenced Tagged Image File Format (GeoTIFF) is a TIFF file with embedded geographic information. This is a standard image format for GIS applications. File size is approximately 25 MB for 1-arc-second data files and approximately 3 MB for 3-arc-second data files.

## Datasource
[ USGS ](https://earthexplorer.usgs.gov/)
[ AU.DEM-Lidar_5m ](https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata/89644)

# Shuttle Radar Topography Mission (SRTM) 1 Arc-Second Global
| Projection | Geographic |
| --- | --- |
| Horiz Datum | WGS84 |
| Vert Datum | EGM96 |
| Spatial Resolution | 1 arc-second for global coverage (~30 meters) |

The Shuttle Radar Topography Mission (SRTM) is a joint project between the National Geospatial-Intelligence Agency (NGA) and the National Aeronautics and Space Administration (NASA).  The objective of this project is to produce digital topographic data for 80% of the Earth's land surface (all land areas between 60º north and 56° south latitude), with data points located every 1-arc-second (approximately 30 meters) on a latitude/longitude grid.  The absolute vertical accuracy of the elevation data will be 16 meters (at 90% confidence). This radar system will gather data that will result in the most accurate and complete topographic map of the Earth's surface that has ever been assembled.

shuttle Endeavour February 11-22, 2000. The National Aeronautics and Space Administration (NASA) and the National Geospatial-Intelligence Agency (NGA) participated in an international project to acquire radar data which were used to create the first near-global set of land elevations.

The radars used during the SRTM mission were actually developed and flown on two Endeavour missions in 1994. The C-band Spaceborne Imaging Radar and the X-Band Synthetic Aperture Radar (X-SAR) hardware were used on board the space shuttle in April and October 1994 to gather data about Earth's environment. The technology was modified for the SRTM mission to collect interferometric radar, which compared two radar images or signals taken at slightly different angles. This mission used single-pass interferometry, which acquired two signals at the same time by using two different radar antennas. An antenna located on board the space shuttle collected one data set and the other data set was collected by an antenna located at the end of a 60-meter mast that extended from the shuttle. Differences between the two signals allowed for the calculation of surface elevation.

Endeavour orbited Earth 16 times each day during the 11-day mission, completing 176 orbits. SRTM successfully collected radar data over 80% of the Earth's land surface between 60° north and 56° south latitude with data points posted every 1 arc-second (approximately 30 meters).

# GMTED 2010
The USGS and the National Geospatial-Intelligence Agency (NGA) have collaborated on the development of a notably enhanced global elevation model called the Global Multi-resolution Terrain Elevation Data (GMTED2010), which has replaced GTOPO30 as the elevation dataset of choice for global and continental scale applications.

# Digital Elevation Model (DEM) of Australia derived from LiDAR 5 Metre Grid
The Digital Elevation Model (DEM) 5 Metre Grid of Australia derived from LiDAR represents a National 5 metre (bare earth) DEM which has been derived from some 236 individual LiDAR surveys between 2001 and 2015 covering. All available 1 metre resolution LiDAR-derived DEMs have been compiled and resampled to 5 metre resolution datasets for each survey area, and then merged into a single dataset for each State. These State datasets have also been merged into a 1 second resolution national dataset. The sourced datasets have been captured to standards that are generally consistent with the Australian ICSM LiDAR Acquisition Specifications with require a fundamental vertical accuracy of at least 0.30m (95% confidence) and horizontal accuracy of at least 0.80m (95% confidence). All 1-metre DEMs were resampled to 5-metre-resolution using a neighbourhood-mean method for analysis. Error surfaces were created along with the DEMs by calculating the difference with the National DEM.

