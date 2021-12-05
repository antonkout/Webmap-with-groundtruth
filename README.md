# Webmap-with-groundtruth
This repository contains a jupyter notebook of a web-map image database of oil spill events worldwide.

### Required Python Libraries
------------------------------------------------

```
geopandas == 0.9.0
rasterio == 1.1.0
folium == 0.12.1
pyproj == 2.6.1
```

### Description
------------------------------------------------
A Web map image database for the visualization of the ground truth imagery. The map is constructed with <b>folium</b> module and geopandas dataframes, plotting the exact coordinates of the oil spill event. The Sentinel-2 images that cover the presented oil spill events are RGB composites that are transformed from <b>.tiff</b> to <b>.png</b> format adjusting the contrast and the gamma value for visibility reasons. Also the satellite images where cropped around the oil spill event.
