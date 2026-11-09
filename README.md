Determining best EEZ's for oysters on the North American West Coast

# Purpose
The purpose of this repository is to determine which Exclusive Economic Zones (EEZ) on the west coast are best suited for oyster cultiavtion, along with writing a function can output suitable areas based on given ideal temperature and depth ranges. The first map shows the amount of suitable area in EEZ's for oysters in general, while the second map uses the automated function to generate a map of suitable areas for the Pacific Oyster. The maps generated were made using R, mainly with the terra, tidyverse, and tmap packages.

# Repository layout
Included in this repository is /data/, which includes annual average ocean surface temperatures, ocean depth, and EEZ zones, the MIT liscence, and Oyster_Suitability_Analysis.qmd, which contains all code to wrangle the data and generate the pdf, also contained in this repository.

# Data access
R Packages used: sf, terra, tidverse, tmap, elevatr, tigris, viridisLite, glue   

Average annual sea surface temperature was taken from [NOAA’s 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1.](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php) from the years 2008 to 2012.

Depth data was taken from the [General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data-products/gridded-bathymetry-data#area).

Exclusive Economic Zone boundaries were taken from [Marineregions.org](https://www.marineregions.org/eez.php).

# Authors

Liam Sarmiento

# References

All pulled data
https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view

Average Annual Surface Temperature
https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php

Ocean Depth
https://www.gebco.net/data-products/gridded-bathymetry-data#area

EEZ Regions
https://www.marineregions.org/eez.php