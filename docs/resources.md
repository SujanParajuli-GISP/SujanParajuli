---
hide:
  - toc
  - navigation
---

# Resources

A curated library of GIS &amp; Remote Sensing data sources, tools, libraries, courses and
tutorials. Compiled from study notes and saved posts, with every link pointing to the
**official source** (data provider, documentation or course home) rather than to any
social-media post.

!!! note "How to use this page"
    - The **Data** sections are tables: *Data · Uses · Link · Output format*.
    - The **Tools, Libraries, Learning** sections are annotated link lists.
    - Availability, resolution and licensing change over time &mdash; always confirm on the
      provider's site before using a dataset in production.

---

## 1. Land Use / Land Cover data

| Data | Uses | Link | Output format |
|------|------|------|---------------|
| **GlobeLand30** | 30 m global land cover (2000 / 2010 / 2020) from China's National Geomatics Center; baseline LULC mapping and change detection | <http://www.globallandcover.com/> | GeoTIFF (tiled raster) |
| **ESA WorldCover** | 10 m global land cover for 2020 &amp; 2021 from Sentinel-1 + Sentinel-2 | <https://esa-worldcover.org/> | GeoTIFF (COG) |
| **Copernicus Global Land Cover** | 100 m annual global land cover, 2015&ndash;2019 (Sentinel + PROBA-V) | <https://land.copernicus.eu/en/products/global-dynamic-land-cover> | GeoTIFF, NetCDF |
| **ESA CCI Land Cover v2** | 300 m annual global maps, 1992&ndash;2020; long-term climate / LULC studies | <https://www.esa-landcover-cci.org/> | NetCDF, GeoTIFF |
| **Esri 10 m Land Cover** | High-resolution annual global land cover from Sentinel-2 (Impact Observatory) | <https://livingatlas.arcgis.com/landcoverexplorer/> | GeoTIFF, tile/imagery service |
| **USGS Global Land Cover Characterization (GLCC)** | 1 km global land cover from 1992&ndash;93 AVHRR; historical baseline | <https://www.usgs.gov/centers/eros/science/usgs-eros-archive-land-cover-products-global-land-cover-characterization-glcc> | GeoTIFF, BIL |
| **MODIS Land Cover (MCD12Q1)** | 500 m annual global land cover, 2001&ndash;present; multiple classification schemes | <https://lpdaac.usgs.gov/products/mcd12q1v061/> | HDF-EOS, GeoTIFF |
| **MODIS Land Cover CMG (MCD12C1)** | 0.05&deg; (&asymp;5.6 km) global land cover climatology | <https://lpdaac.usgs.gov/products/mcd12c1v061/> | HDF-EOS, GeoTIFF |
| **SERVIR Regional Land Cover** | Regional LULC products for developing regions (Africa, HKH, Mekong, Amazonia) | <https://www.servirglobal.net/> | GeoTIFF |
| **Global Forest Change (Hansen / GLAD)** | 30 m tree cover, annual forest loss &amp; gain, 2000&ndash;present | <https://glad.earthengine.app/view/global-forest-change> | GeoTIFF |
| **Global Land Survey (GLS)** | 30 m orthorectified Landsat epochs; tree cover, bare ground, surface water | <https://www.usgs.gov/centers/eros/science/global-land-survey-gls> | GeoTIFF |
| **Global Urban Footprint (DLR)** | &asymp;12 m global built-up mask from TanDEM-X radar | <https://geoservice.dlr.de/web/maps/eoc:guf> | GeoTIFF |
| **FAO GLC-SHARE** | &asymp;1 km global land-cover fractions harmonised from national datasets | <https://data.apps.fao.org/> | GeoTIFF |
| **IPUMS Terra (TerraPop)** | Integrated land cover + population &amp; demographic microdata | <https://terra.ipums.org/> | GeoTIFF, CSV |
| **OpenStreetMap land use** | Community-mapped land-use / land-cover polygons | <https://www.openstreetmap.org/> &middot; <https://download.geofabrik.de/> | Shapefile, GeoJSON, `.osm.pbf` |

---

## 2. Open geospatial data platforms

| Data | Uses | Link | Output format |
|------|------|------|---------------|
| **Humanitarian Data Exchange (HDX)** | Population, admin boundaries, infrastructure, crisis data | <https://data.humdata.org/> | Shapefile, GeoJSON, CSV |
| **WRI Data Explorer / Resource Watch** | Environmental &amp; natural-resource datasets, deforestation, water risk | <https://datasets.wri.org/> | Shapefile, GeoJSON, CSV, API |
| **Koordinates** | Global marketplace of open environmental, infrastructure &amp; social geodata | <https://koordinates.com/> | Shapefile, GeoJSON, KML, CSV |
| **OpenStreetMap** | Roads, buildings, POIs, land use, boundaries | <https://www.openstreetmap.org/> | `.osm.pbf`, Shapefile, GeoJSON |
| **HydroSHEDS** | Rivers, lakes, basins, flow direction / accumulation | <https://www.hydrosheds.org/> | Shapefile, GeoTIFF |
| **Natural Earth** | 1:10m / 1:50m / 1:110m cultural &amp; physical vector + raster | <https://www.naturalearthdata.com/> | Shapefile, GeoTIFF |
| **FAO GeoNetwork / Hand-in-Hand** | Agriculture, fisheries, land &amp; water datasets | <https://data.apps.fao.org/> | Shapefile, GeoJSON, GeoTIFF, WMS |
| **European Environment Agency (EEA)** | CORINE land cover, air quality, biodiversity, noise | <https://www.eea.europa.eu/en/datahub> | Shapefile, GeoPackage, GeoTIFF |
| **Global Forest Watch** | Forest cover, loss / gain, fire alerts, land use | <https://www.globalforestwatch.org/> | Shapefile, GeoJSON, GeoTIFF, API |
| **DIVA-GIS** | Country-level admin, climate, elevation, species data | <https://www.diva-gis.org/gdata> | Shapefile, GeoTIFF |
| **Esri Open Data Hub** | Tens of thousands of open government / organisation layers | <https://hub.arcgis.com/> | Shapefile, GeoJSON, CSV, KML, API |
| **Free GIS Data (R. Wilson)** | Categorised index of 500+ free raster &amp; vector data sources | <https://freegisdata.rtwilson.com/> | Directory / link list |
| **GISGeography &ndash; Free GIS Data** | Curated list of best global raster &amp; vector datasets | <https://gisgeography.com/best-free-gis-data-sources-raster-vector/> | Directory / link list |

---

## 3. Elevation, terrain &amp; bathymetry

| Data | Uses | Link | Output format |
|------|------|------|---------------|
| **OpenTopography** | Global &amp; regional DEMs (SRTM, Copernicus, NASADEM, ALOS) and lidar point clouds | <https://opentopography.org/> | GeoTIFF, LAS / LAZ |
| **USGS EarthExplorer** | SRTM, ASTER GDEM, NED / 3DEP, plus Landsat &amp; declassified imagery | <https://earthexplorer.usgs.gov/> | GeoTIFF |
| **Copernicus DEM (GLO-30 / GLO-90)** | 30 m &amp; 90 m global elevation from TanDEM-X | <https://dataspace.copernicus.eu/> | GeoTIFF |
| **ALOS World 3D-30m (AW3D30)** | 30 m global DSM from JAXA | <https://www.eorc.jaxa.jp/ALOS/en/dataset/aw3d30/aw3d30_e.htm> | GeoTIFF |
| **USGS 3DEP / The National Map** | US 1 m&ndash;1/3 arc-second DEMs and lidar | <https://apps.nationalmap.gov/downloader/> | GeoTIFF, LAS / LAZ |
| **GEBCO** | Global gridded bathymetry &amp; topography | <https://www.gebco.net/data-products-gridded-bathymetry-data> | NetCDF, GeoTIFF, Esri ASCII |
| **Global River Widths from Landsat (GRWL)** | River centrelines &amp; channel widths at mean discharge | <https://doi.org/10.5281/zenodo.1297434> | Shapefile, GeoTIFF |
| **HydroSHEDS DEM / HydroRIVERS / HydroLAKES** | Hydrologically conditioned elevation and derived networks | <https://www.hydrosheds.org/products> | GeoTIFF, Shapefile |

---

## 4. Hydrology &amp; water resources

| Data | Uses | Link | Output format |
|------|------|------|---------------|
| **NASA Earth Observations (NEO)** | Browse-ready global rasters: precipitation, soil moisture, LST, vegetation | <https://neo.gsfc.nasa.gov/> | GeoTIFF, PNG, CSV, NetCDF |
| **GPM / IMERG** | Near-real-time &amp; research global precipitation, 0.1&deg; half-hourly | <https://gpm.nasa.gov/data/directory> | HDF5, NetCDF, GeoTIFF |
| **USGS National Water Information System (NWIS)** | US streamflow, groundwater levels, water quality | <https://waterdata.usgs.gov/nwis> | RDB, CSV, WaterML, JSON |
| **JRC Global Surface Water** | Surface-water occurrence, change &amp; seasonality, 1984&ndash;present (30 m) | <https://global-surface-water.appspot.com/> | GeoTIFF |
| **ESA Climate Change Initiative (CCI)** | Long-term ECV records: soil moisture, sea level, snow, lakes | <https://climate.esa.int/> | NetCDF |
| **NASA Earthdata (MODIS / SMAP / GPM)** | Snow cover, soil moisture, land-surface temperature, precipitation | <https://www.earthdata.nasa.gov/> | HDF, NetCDF, GeoTIFF |
| **USGS National Hydrography Dataset (NHD / WBD)** | US rivers, water bodies, watershed boundaries | <https://www.usgs.gov/national-hydrography> | File geodatabase, Shapefile |
| **WWF Freshwater Ecoregions of the World (FEOW)** | Global freshwater ecoregion boundaries | <https://www.feow.org/> | Shapefile |
| **FAO AQUASTAT** | Country-level water-resource &amp; irrigation statistics | <https://www.fao.org/aquastat/> | CSV, API |

---

## 5. Climate &amp; atmosphere

| Data | Uses | Link | Output format |
|------|------|------|---------------|
| **CHIRPS** | 0.05&deg; quasi-global rainfall, 1981&ndash;present; drought &amp; agriculture monitoring | <https://www.chc.ucsb.edu/data/chirps> | GeoTIFF, NetCDF, BIL |
| **Copernicus Climate Data Store (CDS)** | ERA5 reanalysis, seasonal forecasts, climate projections, ECVs | <https://cds.climate.copernicus.eu/> | NetCDF, GRIB |
| **ECMWF ERA5** | Hourly global reanalysis: temperature, precipitation, wind, pressure | <https://www.ecmwf.int/en/forecasts/dataset/ecmwf-reanalysis-v5> | GRIB, NetCDF |
| **World Bank Climate Change Knowledge Portal** | Country climate baselines, risks &amp; projections | <https://climateknowledgeportal.worldbank.org/> | CSV, NetCDF, API |
| **NASA POWER** | Global meteorology &amp; solar-radiation data for energy / agriculture | <https://power.larc.nasa.gov/> | CSV, NetCDF, GeoJSON, API |
| **WorldClim** | 1 km climatologies &amp; 19 bioclimatic variables; species &amp; ecology modelling | <https://worldclim.org/> | GeoTIFF |
| **Global Historical Climatology Network (GHCN)** | Station precipitation &amp; temperature records | <https://www.ncei.noaa.gov/products/land-based-station/global-historical-climatology-network-daily> | CSV, fixed-width |
| **NOAA Climate Data Records (CDR)** | Long-term, satellite-based essential climate variables | <https://www.ncei.noaa.gov/products/climate-data-records> | NetCDF |
| **NASA FIRMS** | Near-real-time active fire / thermal anomalies (MODIS, VIIRS) | <https://firms.modaps.eosdis.nasa.gov/> | Shapefile, CSV, KML, WMS |
| **Copernicus Marine Service (CMEMS)** | Sea-surface temperature, sea level, salinity, ocean colour | <https://marine.copernicus.eu/> | NetCDF |
| **CMIP6 (ESGF)** | Coupled climate-model projections used in IPCC assessments | <https://aims2.llnl.gov/> | NetCDF |
| **Argo floats** | Global ocean temperature, salinity &amp; pressure profiles | <https://argo.ucsd.edu/> | NetCDF |
| **FLUXNET** | Eddy-covariance carbon, water &amp; energy flux tower records | <https://fluxnet.org/data/fluxnet2015-dataset/> | CSV |
| **Berkeley Earth** | Gridded global land / ocean temperature and air-pollution data | <https://berkeleyearth.org/data/> | NetCDF, CSV |
| **NASA SEDAC** | Gridded population (GPW), poverty, infrastructure, hazards | <https://sedac.ciesin.columbia.edu/> | GeoTIFF, Shapefile, CSV |
| **UNEP &ndash; World Environment Situation Room (WESR)** | Global environmental indicators &amp; geospatial layers | <https://wesr.unep.org/> | CSV, GeoTIFF, API |

---

## 6. Satellite imagery &amp; Earth-observation archives

| Data | Uses | Link | Output format |
|------|------|------|---------------|
| **USGS EarthExplorer** | Landsat 1&ndash;9, Sentinel-2, MODIS, NAIP, declassified &amp; historical imagery | <https://earthexplorer.usgs.gov/> | GeoTIFF |
| **Copernicus Data Space Ecosystem** | Full Sentinel-1 / 2 / 3 / 5P archive &amp; on-the-fly processing | <https://dataspace.copernicus.eu/> | SAFE, GeoTIFF, NetCDF |
| **NASA Earthdata Search** | Cross-mission discovery &amp; download across NASA DAACs | <https://search.earthdata.nasa.gov/> | HDF, NetCDF, GeoTIFF |
| **Sentinel Hub EO Browser** | Quick visual browse &amp; export of Sentinel, Landsat, MODIS | <https://apps.sentinel-hub.com/eo-browser/> | GeoTIFF, PNG, JPG |
| **Microsoft Planetary Computer** | STAC catalog + hosted compute for global EO datasets | <https://planetarycomputer.microsoft.com/> | COG, STAC, Zarr |
| **Google Earth Engine** | Petabyte multi-source catalog with cloud analysis | <https://earthengine.google.com/> | EE assets, GeoTIFF export |
| **STAC Index** | Directory of public SpatioTemporal Asset Catalogs | <https://stacindex.org/> | STAC JSON |

---

## 7. Historical &amp; time-lapse imagery viewers

| Data | Uses | Link | Output format |
|------|------|------|---------------|
| **Google Earth Pro (desktop)** | Historical-imagery time slider back to the 1930s&ndash;80s in places | <https://www.google.com/earth/versions/> | On-screen, image / KMZ export |
| **Esri Wayback Imagery** | Every published version of Esri World Imagery since 2014 | <https://livingatlas.arcgis.com/wayback/> | Tile service, on-screen |
| **USGS LandLook** | Fast visual browse of the Landsat &amp; Sentinel-2 archive | <https://landlook.usgs.gov/> | On-screen, GeoTIFF via EarthExplorer |
| **NASA Worldview** | Daily full-resolution global browse imagery (GIBS), 2000&ndash;present | <https://worldview.earthdata.nasa.gov/> | JPEG, PNG, GeoTIFF, KMZ |
| **Planet Education &amp; Research Program** | High-cadence PlanetScope / RapidEye archive for qualifying researchers | <https://www.planet.com/industries/education-and-research/> | GeoTIFF |

---

## 8. Spectral indices references

| Data | Uses | Link | Output format |
|------|------|------|---------------|
| **Index DataBase (IDB)** | 500+ remote-sensing indices with formulas, sensors &amp; band mappings | <https://www.indexdatabase.de/> | Web reference |
| **ArcGIS Pro Indices Gallery** | Documentation for built-in raster indices (NDVI, NDWI, NDBI, &hellip;) | <https://pro.arcgis.com/en/pro-app/latest/help/data/imagery/indices-gallery.htm> | Web reference |
| **Sentinel Hub Custom Scripts / Index DB** | Ready-to-run evalscripts for dozens of Sentinel-2 indices | <https://custom-scripts.sentinel-hub.com/custom-scripts/sentinel-2/indexdb/> | JavaScript evalscripts |

---

## 9. Quick reference &mdash; geospatial data by type

| Need | Where to get it | Output format |
|------|-----------------|---------------|
| Administrative boundaries (country / state / district) | GADM &nbsp;<https://gadm.org/> &middot; geoBoundaries &nbsp;<https://www.geoboundaries.org/> &middot; Natural Earth &nbsp;<https://www.naturalearthdata.com/> &middot; OCHA COD &nbsp;<https://data.humdata.org/> | Shapefile, GeoPackage, GeoJSON |
| 30 m Digital Elevation Model | SRTM / NASADEM / Copernicus GLO-30 via OpenTopography &nbsp;<https://opentopography.org/> &middot; USGS EarthExplorer &nbsp;<https://earthexplorer.usgs.gov/> | GeoTIFF |
| 90 m Digital Elevation Model | SRTM v3 / Copernicus GLO-90 &nbsp;<https://srtm.csi.cgiar.org/> | GeoTIFF |
| Coarse DEM (225 m&ndash;1 km) | GTOPO30 / GMTED2010 &nbsp;<https://www.usgs.gov/coastal-changes-and-impacts/gmted2010> | GeoTIFF |
| Rainfall | CHIRPS &nbsp;<https://www.chc.ucsb.edu/data/chirps> &middot; GPM IMERG &nbsp;<https://gpm.nasa.gov/data/directory> | GeoTIFF, NetCDF, HDF5 |
| Climate (temperature, bioclim) | WorldClim &nbsp;<https://worldclim.org/> &middot; TerraClimate &nbsp;<https://www.climatologylab.org/terraclimate.html> | GeoTIFF, NetCDF |
| Land use / land cover | ESA WorldCover &nbsp;<https://esa-worldcover.org/> &middot; ESRI 10 m &nbsp;<https://livingatlas.arcgis.com/landcoverexplorer/> | GeoTIFF |
| Geology | USGS &nbsp;<https://mrdata.usgs.gov/> &middot; OneGeology &nbsp;<https://portal.onegeology.org/> | Shapefile, WMS |
| Global administrative / place names | GeoNames &nbsp;<https://www.geonames.org/> | CSV, TXT, API |
| Active fire | NASA FIRMS &nbsp;<https://firms.modaps.eosdis.nasa.gov/> | Shapefile, CSV, KML |
| Soil | SoilGrids (ISRIC) &nbsp;<https://soilgrids.org/> &middot; FAO/HWSD &nbsp;<https://www.fao.org/soils-portal/> | GeoTIFF |
| Moon elevation model | LOLA / LRO &nbsp;<https://pgda.gsfc.nasa.gov/products/54> &middot; USGS Astrogeology &nbsp;<https://astrogeology.usgs.gov/> | GeoTIFF, cube |
| 1 m elevation / lidar | USGS 3DEP &nbsp;<https://apps.nationalmap.gov/downloader/> &middot; OpenTopography &nbsp;<https://opentopography.org/> | GeoTIFF, LAS / LAZ |
| Population (gridded) | WorldPop &nbsp;<https://www.worldpop.org/> &middot; SEDAC GPW &nbsp;<https://sedac.ciesin.columbia.edu/> | GeoTIFF |

---

## 10. Biodiversity &amp; ecology data

| Data | Uses | Link | Output format |
|------|------|------|---------------|
| **GBIF** | Global species-occurrence records | <https://www.gbif.org/> | CSV (Darwin Core), API |
| **IUCN Red List** | Species conservation status &amp; range maps | <https://www.iucnredlist.org/> | Shapefile, CSV, API |
| **Ramsar Sites Information Service** | Wetlands of international importance | <https://rsis.ramsar.org/> | Shapefile, CSV, API |
| **Protected Planet (WDPA / WD-OECM)** | World database of protected &amp; conserved areas | <https://www.protectedplanet.net/> | Shapefile, GeoPackage, CSV |
| **Map of Life** | Modelled species distributions &amp; range maps | <https://mol.org/> | GeoTIFF, API |
| **AquaMaps** | Modelled global marine-species ranges | <https://www.aquamaps.org/> | CSV, ASCII grid |
| **UNEP-WCMC Ocean Data Viewer** | Mangroves, seagrass, coral reefs, MPAs | <https://data.unep-wcmc.org/> | Shapefile, GeoTIFF |
| **BIEN** | Plant-species occurrence &amp; functional traits | <https://bien.nceas.ucsb.edu/bien/> | R package, CSV |
| **NOAA Digital Coast** | Coastal lidar, land cover, benthic &amp; socioeconomic data | <https://coast.noaa.gov/digitalcoast/> | GeoTIFF, LAZ, Shapefile |

---

## 11. Desktop &amp; web GIS software

- **[QGIS](https://qgis.org/)** &mdash; free, open-source desktop GIS; the standard companion to ArcGIS Pro.
- **[ArcGIS Online](https://www.arcgis.com/)** &mdash; Esri's cloud Web GIS; feature-rich, built for organisations and non-programmers.
- **[CARTO](https://carto.com/)** &mdash; cloud-native spatial analytics on PostgreSQL/PostGIS; strong for developers, usable without code.
- **[Mango Map](https://mangomap.com/)** &mdash; simple no-code web-map publishing.
- **[GIS Cloud](https://www.giscloud.com/)** &mdash; desktop-like web GIS with mobile data collection.
- **[Mapbox](https://www.mapbox.com/)** &mdash; developer platform for fast, highly customised vector maps.

### LiDAR &amp; point-cloud tools

- **[CloudCompare](https://www.cloudcompare.org/)** &mdash; open-source 3D point-cloud and mesh processing.
- **[WhiteboxTools / Whitebox GAT](https://www.whiteboxgeo.com/)** &mdash; 500+ geoprocessing tools for terrain, hydrology and lidar.
- **[Orfeo Toolbox (OTB)](https://www.orfeo-toolbox.org/)** &mdash; open-source remote-sensing image processing, including lidar support.

### Network / graph visualisation

- **[Gephi](https://gephi.org/)** &middot; **[VOSviewer](https://www.vosviewer.com/)** &middot; **[Cytoscape](https://cytoscape.org/)** &middot; **[Kumu](https://kumu.io/)** &middot; **[NodeXL](https://nodexl.com/)** &middot; **[Graphia](https://graphia.app/)** &middot; **[Graphistry](https://www.graphistry.com/)** &middot; **[SocNetV](https://socnetv.org/)**

### Popular QGIS plugins

QuickMapServices, Semi-Automatic Classification Plugin, qgis2web, Lat Lon Tools, Profile Tool,
mmqgis, Qgis2threejs, LAStools, QuickOSM, GeoCoding, QTiles &mdash; all installable from the
official plugin repository: <https://plugins.qgis.org/>

---

## 12. Python libraries for GIS &amp; Remote Sensing

| Library | Purpose | Link |
|---------|---------|------|
| **GeoPandas** | Vector data as pandas GeoDataFrames | <https://geopandas.org/> |
| **Shapely** | Geometric objects &amp; operations | <https://shapely.readthedocs.io/> |
| **Fiona** | Read / write vector formats (OGR) | <https://fiona.readthedocs.io/> |
| **GDAL / OGR** | Core raster + vector translation library | <https://gdal.org/> |
| **Rasterio** | Pythonic raster I/O &amp; processing | <https://rasterio.readthedocs.io/> |
| **rioxarray** | Rasterio + xarray for labelled raster arrays | <https://corteva.github.io/rioxarray/> |
| **Xarray** | N-dimensional labelled arrays / data cubes | <https://docs.xarray.dev/> |
| **pyproj** | Coordinate reference systems &amp; transforms | <https://pyproj4.github.io/pyproj/> |
| **PySAL** | Spatial statistics, ESDA, spatial econometrics | <https://pysal.org/> |
| **scikit-image** | Image processing (texture, segmentation) | <https://scikit-image.org/> |
| **scikit-learn** | Machine learning for classification / regression | <https://scikit-learn.org/> |
| **Folium** | Leaflet.js interactive web maps | <https://python-visualization.github.io/folium/> |
| **ipyleaflet** | Interactive maps inside Jupyter | <https://ipyleaflet.readthedocs.io/> |
| **geemap** | Google Earth Engine + interactive mapping | <https://geemap.org/> |
| **leafmap** | Analysis-ready interactive mapping, no EE needed | <https://leafmap.org/> |
| **OSMnx** | Download &amp; analyse OpenStreetMap street networks | <https://osmnx.readthedocs.io/> |
| **contextily** | Basemap tiles for static maps | <https://contextily.readthedocs.io/> |
| **h3-py** | Uber's hexagonal hierarchical spatial index | <https://h3geo.org/docs/> |
| **kepler.gl / pydeck** | Large-scale interactive geospatial visualisation | <https://kepler.gl/> &middot; <https://deckgl.readthedocs.io/> |
| **Cartopy** | Cartographic projections &amp; map plotting | <https://scitools.org.uk/cartopy/> |
| **WhiteboxTools (Python)** | Terrain, hydrology &amp; lidar geoprocessing | <https://www.whiteboxgeo.com/> |
| **RSGISLib** | Remote-sensing raster processing &amp; OBIA | <https://www.rsgislib.org/> |
| **scikit-mobility** | Human-mobility &amp; trajectory analysis | <https://scikit-mobility.github.io/scikit-mobility/> |

---

## 13. Learning &mdash; courses

- **[Introduction to GIS Programming (GEOG&nbsp;312)](https://geog-312.gishub.org/)** &mdash; Qiusheng Wu, University of Tennessee; Python from basics to geospatial workflows (free notebooks + video).
- **[Spatial Data Management (GEOG&nbsp;414)](https://geog-414.gishub.org/)** &mdash; Qiusheng Wu; DuckDB, PostGIS, GeoPandas, Google Earth Engine, PMTiles.
- **[Spatial Data Management with DuckDB](https://duckdb.gishub.org/)** &mdash; companion book (Python).
- **[Introduction to GIS Programming](https://gispro.gishub.org/)** &mdash; companion book (Python).
- **[GEOG&nbsp;486: Cartography and Visualization](https://www.e-education.psu.edu/geog486/)** &mdash; Penn State open courseware; cartographic design, thematic and multiscale web mapping.
- **[Automating GIS Processes](https://autogis-site.readthedocs.io/)** &mdash; University of Helsinki; geospatial analysis with GeoPandas &amp; friends.
- **[Introduction to Python for Geographic Data Analysis](https://pythongis.org/)** &mdash; University of Helsinki open textbook.
- **[NASA ARSET](https://appliedsciences.nasa.gov/what-we-do/capacity-building/arset)** &mdash; free applied remote-sensing trainings, introductory to advanced (SAR, flood, air quality, land cover, disasters).
- **[Analyzing US Census Data](https://walker-data.com/census-r/)** &mdash; Kyle Walker; methods, maps and models in R.
- **[Geographic Data Science with Python](https://geographicdata.science/book/)** &mdash; Rey, Arribas-Bel &amp; Wolf; open textbook.
- **[Spatial Thoughts](https://spatialthoughts.com/)** / **[courses.spatialthoughts.com](https://courses.spatialthoughts.com/)** &mdash; Ujaval Gandhi; QGIS, GEE, Python full courses.
- **[Software Carpentry](https://software-carpentry.org/lessons/)** &mdash; foundational shell, Git and Python lessons.
- **[CS50x](https://cs50.harvard.edu/x/)** &mdash; Harvard's introduction to computer science.

### LiDAR-specific courses

- **[Mastering LiDAR Data Processing](https://academy.rockrobotic.com/p/mastering-lidar-data-processing)** &mdash; ROCK Academy; point clouds, DEMs, classification.
- **[Introduction to Lidar](https://coast.noaa.gov/digitalcoast/training/intro-lidar.html)** &mdash; NOAA Digital Coast; short interactive modules.
- **[UAS-Based Mapping &amp; Laser Scanning](https://www.classcentral.com/course/uas-based-mapping-laser-scanning-52891)** &mdash; Purdue University; drone-lidar workflows.
- **[Lidar in GIS (GEOG 5525)](https://sites.geography.unt.edu/~pdong/courses/4525/GEOG5525.pdf)** &mdash; University of North Texas course notes.

---

## 14. Learning &mdash; tutorials &amp; recommended practices

- **[UN-SPIDER Recommended Practices](https://www.un-spider.org/advisory-support/recommended-practices)** &mdash; step-by-step disaster-mapping workflows in QGIS, R, Python and Google Earth Engine:
    - [Burn severity mapping](https://www.un-spider.org/advisory-support/recommended-practices/recommended-practice-burn-severity/in-detail) (Landsat 8 / Sentinel-2; QGIS, R, GEE, Python)
    - [Agricultural drought monitoring with GEE](https://www.un-spider.org/advisory-support/recommended-practices/recommended-practice-agriculture-drought-monitoring/step-by-step)
    - [Flood mapping with GEE and Sentinel-1](https://www.un-spider.org/advisory-support/recommended-practices/recommended-practice-google-earth-engine-flood-mapping/step-by-step)
- **[1000 GIS / Remote Sensing Applications](https://gisgeography.com/remote-sensing-applications/)** &mdash; GISGeography's catalogue of use cases across disciplines.
- **[Above-Ground Biomass with ML &amp; Remote Sensing](https://medium.com/@sandrosena/modeling-above-ground-biomass-with-machine-learning-and-remote-sensing-e82a9ea9926f)** &mdash; walkthrough by Sandro Sena · [code on GitHub](https://github.com/sdesena/above-ground-biomass-machine-learning).
- **[Forest AGB regression with the EnMAP-Box](https://enmap-box.readthedocs.io/en/latest/usr_section/application_tutorials/biomass_regression/tutorial.html)** &mdash; hyperspectral biomass mapping tutorial.
- **[Satellite Image Deep Learning &ndash; techniques](https://github.com/satellite-image-deep-learning/techniques)** &mdash; comprehensive index of models, datasets and papers.
- **[geemap tutorials](https://geemap.org/tutorials/)** &amp; **[leafmap tutorials](https://leafmap.org/)** &mdash; large libraries of notebook + video walkthroughs.

### Pre-trained GeoAI models

- **[Kaggle Models](https://www.kaggle.com/models)** (formerly TensorFlow Hub) &middot; **[PyTorch Hub](https://pytorch.org/hub/)** &middot; **[Hugging Face Models](https://huggingface.co/models)** &middot; **[IBM Model Asset eXchange](https://developer.ibm.com/exchanges/models/)** &middot; **[NVIDIA NGC Catalog](https://catalog.ngc.nvidia.com/)** &middot; **[Source Cooperative](https://source.coop/)** (formerly Radiant MLHub) &middot; **[ArcGIS Living Atlas](https://livingatlas.arcgis.com/)** (search `dlpk`).

---

## 15. Cheat sheets

- **[Python](https://www.pythoncheatsheet.org/)** &middot; **[Pandas (PDF)](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)** &middot; **[NumPy (PDF)](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Numpy_Python_Cheat_Sheet.pdf)** &middot; **[Matplotlib (PDF)](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_Matplotlib_Cheat_Sheet.pdf)**
- **[scikit-learn (PDF)](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Scikit_Learn_Cheat_Sheet_Python.pdf)** &middot; **[GeoPandas / Shapely / GeoPy](https://github.com/prasunkgupta/python-cheat-sheets/blob/master/geopandas-shapely-geopy.ipynb)** &middot; **[Git (PDF)](https://education.github.com/git-cheat-sheet-education.pdf)**

---

## 16. YouTube channels

Search links (channel handles change over time):

| Channel | Focus |
|---------|-------|
| [Open Geospatial Solutions (Qiusheng Wu)](https://www.youtube.com/@giswqs) | Open-source GIS, Earth Engine, geemap / leafmap |
| [Spatial Thoughts (Ujaval Gandhi)](https://www.youtube.com/@SpatialThoughts) | Full courses, QGIS, GEE, Python |
| [Milos Makes Maps](https://www.youtube.com/results?search_query=Milos+Makes+Maps) | Cartography &amp; mapping in R |
| [John Nelson / Adventures in Mapping](https://www.youtube.com/@AdventuresinMapping) | Map design &amp; visual effects in ArcGIS |
| [GIS Simplified](https://www.youtube.com/results?search_query=GIS+Simplified) | Beginner tutorials &amp; tips |
| [Geospatial World](https://www.youtube.com/@GeospatialWorld) | Industry news, interviews, trends |
| [Hans van der Kwast](https://www.youtube.com/@HansvanderKwast) | QGIS for hydrology &amp; open data |
| [Klas Karlsson](https://www.youtube.com/results?search_query=Klas+Karlsson+QGIS) | QGIS tutorials |
| [Hatari Labs](https://www.youtube.com/results?search_query=Hatari+Labs) | QGIS / Python spatial analysis, groundwater |
| [GeoDelta Labs](https://www.youtube.com/results?search_query=GeoDelta+Labs) | Practical GIS &amp; Python tutorials |
| [Krishna Lodha](https://www.youtube.com/results?search_query=Krishna+Lodha+GIS) | Web GIS, live sessions |
| [GIS &amp; RS Solution](https://www.youtube.com/results?search_query=GIS+and+RS+Solution) | GIS, remote sensing, environmental modelling |

---

*Compiled from Sujan Parajuli personal study notes. Corrections and additions welcome via the contact page.*
