# Homework Assignment 3
# Prioritizing potential aquaculture

[Assignment Link](https://eds-223-geospatial.github.io/assignments/HW3.html)

This assignment explores the suitable area for marine aquaculture along the West Coast of the United States, particularly for oysters (assigned choice) and squids (personal choice).

The data are from the following:
- Aquaculture suitable growing conditions: [SeaLifeBase]()
- Sea surface temperature: [NOAA 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1]()
- Bathymetry: [General Bathymetric Chart of the Oceans]()
- Exclusive Economic Zones: [Marineregions.org]()

The deliverables include a map of suitable habitat areas and the area broken down by region (Washington, Oregon, Northern California, Central California, and Southern California) for oysters and squids.

## Repo Structure:
```{r}
.
├── aquaculture_analysis.pdf               # Assignment pdf
├── aquaculture_analysis.qmd               # Assignment quarto doc
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
└── README.md
```

## Contributors
Author: Kelly Loo\
Instructor: Annie Adams\
Teaching Assistant: Mary Salami