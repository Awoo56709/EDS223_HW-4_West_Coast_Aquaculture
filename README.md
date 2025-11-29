# Suitability of Aquaculture by Species



![Oyster EEZ](Oyster EEZ.png)

# Repository's Purpose

This project is to determine suitable environments of species for aquaculture given certain parameters. This repository focuses specifically on oyster suitability in the westcoast region of the United States. Secondly, to produce a workflow and function to reproduce similar output given parameters related to species, depth and sea surface temperature.

# Data Access and Sources

While data sources are stored within the repository, direct sources are linked below:

-   Species depth and temperature requirements Data on species’ environmental tolerances were accessed through [SeaLifeBase](https://www.sealifebase.ca/search.php), an online database providing biological and ecological information for marine species. [Accessed November 24, 2025]

-   Sea surface temperature (SST) Average annual SST rasters were obtained from [NOAA’s Coral Reef Watch](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php) 5-km Sea Surface Temperature Anomaly Product, which provides global, high-resolution satellite-derived SST data. [Accessed November 24, 2025]

-   Bathymetry Ocean depth data were sourced from the [General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data-products/gridded-bathymetry-data#area) Gridded Bathymetry Data, a global dataset of seafloor topography. [Accessed November 24, 2025]

-   Exclusive Economic Zone (EEZ) boundaries EEZ shapefiles were accessed from [Marine Regions](https://www.marineregions.org/eez.php), which provides authoritative global maritime boundaries and geographic information. [Accessed November 24, 2025]

# Repository Structure

``` text
├── .gitignore
│   └── data
│        └── average_annual_sst_2008.tif
│        ├── average_annual_sst_2009.tif
│        ├── average_annual_sst_2010.tif
│        ├── average_annual_sst_2011.tif
│        ├── average_annual_sst_2012.tif
│        ├── depth.tif
│        ├── wc_regions_clean.dbf
│        ├── wc_regions_clean.prj
│        ├── wc_regions_clean.shp
│        └── wc_regions_clean.shx
├── EDS223_HW-4_West_Coast_Aquaculture.Rproj
├── HW_4.qmd
└── README.md
 ```

# Acknowledgements

-   NOAA Coral Reef Watch for sea surface temperature rasters
-   GEBCO for global bathymetry data
-   Marine Regions for EEZ boundary shapefiles
-   SeaLifeBase for species environmental requirements
-   UCSB MEDS Program and Staff for guidance in reproducible workflows, coding strategies
-   R packages that made this analysis possible

# References

-   SeaLifeBase. (n.d.). Species depth and temperature requirements. Retrieved November 24, 2025, from <https://www.sealifebase.ca/search.php>

-   NOAA Coral Reef Watch. (n.d.). 5-km Sea Surface Temperature Anomaly Product. Retrieved November 24, 2025, from <https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php>

-   GEBCO. (n.d.). Gridded Bathymetry Data. Retrieved November 24, 2025, from <https://www.gebco.net/data-products/gridded-bathymetry-data#area>

-   Marine Regions. (n.d.). Exclusive Economic Zones (EEZs). Retrieved November 24, 2025, from <https://www.marineregions.org/eez.php>
