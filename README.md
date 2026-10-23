# GGIS 407 – Lab 3: Geovisualization and Geospatial Object Manipulation

Two Jupyter notebooks for GGIS 407 (University of Illinois Urbana-Champaign), set up to run on the
[I-GUIDE JupyterHub](https://jupyter.i-guide.io) with the `iguide` kernel.

| Notebook | Covers |
| --- | --- |
| `Lab3_PythonVisualization.ipynb` | Matplotlib, Cartopy, GeoPandas `explore()`, and Folium (including a choropleth map) |
| `Lab3_GeospatialDataManipulation.ipynb` | Vector data with Shapely and raster data with Rasterio |

## Data

- `data/Chicago_Community.geojson`: Chicago community area boundaries (City of Chicago), from the
  CyberGIS Center's notebook repository.
- `data/us-states.json`: U.S. state boundaries, from the [folium](https://github.com/python-visualization/folium) example data.
- `data/us-states-covid.csv`: cumulative COVID-19 cases and deaths by state as of March 23, 2023, from
  [The New York Times](https://github.com/nytimes/covid-19-data) (non-commercial use with attribution).
- `data/CDL_2024_Champaign.tif`: 2024 Cropland Data Layer for Champaign County, IL (USDA NASS). it is included in this repository. 
- The saved Chicago web map uses [Esri](https://www.esri.com/) World Street Map tiles, which load without an
  API key in saved HTML files (OpenStreetMap's tile servers block those).

Adapted by Anand Padmanabhan from earlier CyberGISX course notebooks.
