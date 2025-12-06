# Phoenix Biodiversity Intactness Index Analysis

Author: Ava Robillard

### About

The Phoenix metropolitan area experienced significant increases in urban sprawl between the years of 2017 and 2020, which had implications for biodiveristy and the health of surrounding ecosystem. This repository contains a notebook `bii-analysis.ipynb` which contains a workflow for comparing the Biodiversity Intactness Index between these years.


![Phoenix, Arizona, 2024.](images/phoenix.png)


### Analysis highlights
- Geospatial data exploration and wrangling with `geopandas`
- Accessing data using a STAC (SpatioTemporal Asset Catalog) API
- NetCDF data exploration and wrangling with `xarray` and `rioxarray`
- Mapping of vector and raster data and customization with `matplotlib`


### Repository structure
```
phoenix-biodiversity
├── README.md
├── bii-analysis.ipynb  # Analysis notebook
├── data
│   └── tl_2024_04_cousub
│       └── tl_2024_04_cousub.shp
└── images
    └── phoenix.png    
```

### Data

The data for this analysis is not housed in this repository. It was downloaded into a local `data/` folder listed in the `.gitignore` from the [U.S Census Bureau's data catalog](https://catalog.data.gov/dataset/tiger-line-shapefile-current-state-arizona-county-subdivision). The BII dataset was retrieved from the [Microsoft Planetary Computer STAC catalog](https://planetarycomputer.microsoft.com/dataset/io-biodiversity), the code for which in contained in the analysis notebook.

### References

This assignment was created as a part of EDS 220: Working with Environmental Datasets, taught by Carmen Galaz García.

U.S. Census Bureau, Geography Division. (2024). TIGER/Line shapefile, current, state, Arizona, county subdivision (Publication year 2024; created 2024-10; updated 2024-10) [Data set]. U.S. Department of Commerce. Accessed December 5, 2025, from https://catalog.data.gov/dataset/tiger-line-shapefile-current-state-arizona-county-subdivision

Impact Observatory. (2017-2020). Biodiversity Inactness[io-biodiversity]. Microsoft Planetary Computer STAC catalog. Accessed December 5, 2025, from https://planetarycomputer.microsoft.com/dataset/io-biodiversity#overview 

Image: Hamilton, Matthew (2024). Retrieved on December 5, 2025 from https://unsplash.com/photos/an-aerial-view-of-a-city-with-mountains-in-the-background-akE66HU-_Kg 