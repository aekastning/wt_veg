# Vegetation Disturbances in Water Tracks on the North Slope, AK

## Contents
NS_plots.ipynb maps watersheds on the North Slope and plots the track-intertrack NDVI of water tracks.

NS_sheds.csv contains a list of HydroATLAS level 10 watersheds on the North Slope that were analyzed for water track abundance and delayed green-up water tracks.

---

toolik_plots.ipynb plots and fits a GAM to field data collected near the Toolik Field Station, AK. 

toolik_transects.csv contains field data collected at field sites near the Toolik Field Station, AK.

---

spectral-change-plots.ipynb contains workflows to access Sentinel-2 imagery acquired via Google Earth Engine.

..._ndvi_19-25.csv files contain the mean NDVI of a water track and surrounding intertrack for each available image date, calculated using spectral-change-plots.ipynb.

shapefiles contains the boundaries of features, which were used to clip NDVI data.
