# Marine Aquaculture Suitability Mapping

<img src="https://www.marinemammalcenter.org/storage/app/uploads/public/ec8/271/d6d/thumb__2400_0_0_0_auto.jpg"/>

#### Purpose

The purpose of this repository was to create a function that shows you which Exclusive Economic Zones (EEZs) along the U.S. West Coast have the most potential for developing marine aquaculture with a map. The only arguments needed for this function are minimum and maximum sea surface temperature, minimum and maximum depth, and the name of the species of interest.

#### Contents

This repository contains:

```         
.
├── aquaculture_analysis_files
│   ├── figure-html
│   └── libs
├── aquaculture_analysis.html
├── aquaculture_analysis.qmd
├── data
│   ├── average_annual_sst_2008.tif
│   ├── average_annual_sst_2009.tif
│   ├── average_annual_sst_2010.tif
│   ├── average_annual_sst_2011.tif
│   ├── average_annual_sst_2012.tif
│   ├── depth.tif
│   ├── wc_regions_clean.dbf
│   ├── wc_regions_clean.prj
│   ├── wc_regions_clean.shp
│   └── wc_regions_clean.shx
├── marine-aquaculture-suitability-mapping.Rproj
└── README.md
```

#### Contributors

-   Austin Martinez

#### Data Access

The data was used was sourced from the following locations:

-   Sea Surface Temperature data: NOAA’s 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1 <https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php>.

-   Bathymetry data: The General Bathymetric Chart of the Oceans (GEBCO) <https://www.gebco.net/data-products/gridded-bathymetry-data#area>.

-   Exclusive Economic Zones data: <https://www.marineregions.org/eez.php>

-   Species data: <https://www.sealifebase.ca/search.php>

#### References

-   NOAA Coral Reef Watch. (2018). Daily global 5km satellite sea surface temperature anomaly (Version 3.1). National Oceanic and Atmospheric Administration. <https://coralreefwatch.noaa.gov/satellite/analyses_sst_anom.php> (Accessed November 26, 2025)

-   GEBCO Compilation Group. (2025). GEBCO_2025 Grid: Global ocean and land terrain model Data set. General Bathymetric Chart of the Oceans. <https://www.gebco.net> (Accessed November 26, 2025)

-   Flanders Marine Institute (VLIZ). (2025). Maritime Boundaries: Exclusive Economic Zones (EEZ) Data set. MarineRegions.org. <https://www.marineregions.org> (Accessed November 26, 2025)

-   Palomares, M. L. D., & Pauly, D. (Eds.). (2025). SeaLifeBase (Version 04/2025) Database. SeaLifeBase. <http://www.sealifebase.org>

-   Global Seafood Alliance. (2019, March 27). What is aquaculture and why do we need it? Global Seafood Alliance. <https://www.globalseafood.org/what-is-aquaculture-and-why-do-we-need-it>
