# Vermont Lakes + Ponds Bathymetry

[![](felt-map.png)](https://felt.com/map/Vermont-Lakes-Ponds-Bathymetry-dcDtYi3NT36UCpbrhi6udA)

## Sources

Vermont bathymetric data: https://geodata.vermont.gov/datasets/VTANR::bathymetric-data/about

### Lake Champlain

Bathymetric data https://geodata.vermont.gov/datasets/7f451335fc6644e7a7376adbcd6282df_2/about

### Description

Lake Champlain Bathymetry points for general mapping purposes only.

The `ElevationDEM_LKCHDEM` data layer includes bathymetric data derived \[from\] NOAA nautical charts. All points were digitized from the RF 40,000 scale NOAA charts for Lake Champlain. The original data released in 1992 did not include information from Mallets Bay north and from the Crown Point bridge south. VCGI added data for these missing areas in 2003 by taking points from the LCBP data bundle (LAKEBATH). VCGI also replaced the shoreline points in 2010 using the shoreline as defined in the VHDCARTO dataset.

#### License

VCGI and the State of VT make no representations of any kind, including but not limited to the warranties of merchantability or fitness for a particular use, nor are any such warranties to be implied with respect to the data, service, or application.

### Combined tile server

Tile server: https://vcgi.maps.arcgis.com/home/item.html?id=d78e581061df41ff848bf46c920607ac

## Running the scripts

### Requirements

- `ogr2ogr` (comes with [GDAL](https://gdal.org))
- QGIS contour plugin
- `qgis_process` (comes with [QGIS](https://qgis.org/))
