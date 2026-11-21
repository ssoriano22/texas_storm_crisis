# EDS223 HW4: Satellite Data Analysis of Winter Storm Impacts on the Texas Power Grid

## Description

This repository contains files related to the HW4 assignment "Identifying the impacts of extreme weather" for EDS223, part of the UCSB MEDS 2027 graduate program. In this project, pre- and post-storm VIIRS NASA Earth night lights satellite imagery was used to estimate the power grid impact of the February 7-16, 2021 winter storm in Houston, Texas, USA.

The below directory tree maps out the layout of this repository:

```
.
├── .gitignore
│   └── data                                  # All data in gitignore
│       ├── gis_osm_buildings_a_free_1.gpkg   # OSM Residence data
│       ├── gis_osm_roads_free_1.gpkg         # OSM Motorway data
│       └── VNP46A1                           # VIIRS Satellite data
├── README.md
├── texas_storm_crisis.pdf                    # Analysis PDF
└── texas_storm_crisis.qmd                    # Analysis QMD
```

## Data

Night Lights Data: NASA Level-1 and Atmosphere Archive and Distribution System (LAADS) DAAC. (2019). VIIRS/NPP Daily Gridded Day Night Band 500m Linear Lat Lon Grid Night (Collection 1) [Data set]. Goddard Space Flight Center. [https://doi.org/10.5067/VIIRS/VNP46A1.001](https://doi.org/10.5067/VIIRS/VNP46A1.001)

Roads and Houses Data: OpenStreetMap contributors. (2021). Texas OpenStreetMap - roads and buildings [Data set]. Geofabrik. [https://download.geofabrik.de/north-america/us/texas.html](https://download.geofabrik.de/north-america/us/texas.html)

2021 Texas power crisis. (2021, October 2). In Wikipedia. Retrieved November 20, 2026, from https://en.wikipedia.org/wiki/2021_Texas_power_crisis

## Authors

Sophia Soriano - [GitHub](https://github.com/ssoriano22), [LinkedIn](https://www.linkedin.com/in/smsoriano22/)

## References

[EDS223](https://eds-223-geospatial.github.io/) - [UCSB MEDS 2027](https://bren.ucsb.edu/masters-programs/master-environmental-data-science)
