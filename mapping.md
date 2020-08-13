# Mapping Resources
These resources are focused on victoria, australia, some are global services but these are the services i use for ardupilot. 
Some of these are "not free".

## online
* [ok2fly](https://earthexplorer.usgs.gov/)
* [weather](http://www.bom.gov.au/products/IDR023.loop.shtml)
* [Incidents & Warnings](https://www.emergency.vic.gov.au/respond/)
* [hotspots](https://hotspots.dea.ga.gov.au/)
* [mapshare](https://mapshare.vic.gov.au/MapShareVic/index.html?viewer=MapShareVic.PublicSite&locale=en-AU)
* [heritage](https://vhd.heritagecouncil.vic.gov.au/)
* [acma](https://web.acma.gov.au/rrl/site_proximity.main_page)
* [melb](http://maps.melbourne.vic.gov.au/)
* [flightaware](http://flightaware.com/live/airport/YMML)
* [flightradar](https://www.flightradar24.com/)
* [celltowers](https://www.cellmapper.net)
* [antenna](https://ozdigitaltv.com)
* [bom-satellite](http://www.bom.gov.au/australia/satellite/)
## datasources
* [usgs](https://earthexplorer.usgs.gov/)

## Radio broadcast 
* [ATC](https://www.liveatc.net/)

## OpenWeatherMap

### API-1.0
https://tile.openweathermap.org/map/{layer}/{z}/{x}/{y}.png?appid={api_key}

| Type | layer |
| --- | --- |
| Clouds | clouds_new |
| Precipitation | precipitation_new |
| Sea Level Pressure | pressure_new |
| Wind Speed | wind_new |
| Temperature | temp_new |

### 2.0
http://maps.penweathermap.org/maps/2.0/weather/{op}/{z}/{x}/{y}?

| {Op}  Meaning     Unit of measurement
| --- | --- | --- |
| PAC0    | Convective precipitation | mm |
| PR0     | Precipitation intensity | mm/s |
| PA0     | Accumulated precipitation  | mm |
| PAR0    | Accumulated precipitation - rain  | mm |
| PAS0    | Accumulated precipitation - snow   |  mm |
| SD0     | Depth of snow   | m |
| WS10    | Wind speed at an altitude of 10 meters  | m/s |
| WND     | Joint display of speed wind (color) and wind direction (arrows), received by U and V components | m/s |
| APM     | Atmospheric pressure on mean sea level | hPa |
| TA2     | Air temperature at a height of 2 meters | °C |
| TD2     | Temperature of a dew point | °C |
| TS0     | Soil temperature 0-10 сm | K |
| TS10    | Soil temperature >10 сm | K |
| HRD0    | Relative humidity  | % |
| CL      | Cloudiness  | % |

