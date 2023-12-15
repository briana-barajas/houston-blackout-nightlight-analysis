# Houston Blackout, Nightlight Analysis
_Assessing Inequities During 2021 Houston Blackout_

## Background
In February 2021, severe winter storms in the United States caused a major power outage in the state of Texas. The loss of power resulted in over 4.5 million homes and businesses left without power, and several deaths. This analysis uses remotely sensed night light data to assess the impact and distribution of these blackouts. Data from the U.S. Census Bureau will be added to investigate if socioeconomic factors affect the recovery of power within the community.

# Repository Structure
```bash
├── data 
│   ├── ACS_2019_5YR_TRACT_48_TEXAS.gdb #folder with census layers
│   ├── gis_osm_buildings_a_free_1.gpkg #building data
│   ├── gis_osm_roads_free_1.gpkg #road data
│   └── VNP46A1 #folder containing night at light tiles
│       ├── VNP46A1.A2021038.h08v05.001.2021039064328.tif
│       ├── VNP46A1.A2021038.h08v06.001.2021039064329.tif
│       ├── VNP46A1.A2021047.h08v05.001.2021048091106.tif
│       └── VNP46A1.A2021047.h08v06.001.2021048091105.tif
├── docs
│   ├── houston-night_files 
│   │   ├── figure-html #images produced
│   │   └── libs
│   │       ├── bootstrap
│   │       ├── clipboard
│   │       └── quarto-html
│   ├── houston-night.html
│   └── houston-night.qmd
├── houston-blackout-nightlight-analysis.Rproj
└── README.md
```

# Data & References
Geofabrik Download Server (2018), OpenStreetMap Data Extracts [Date file] Available from: <https://download.geofabrik.de/> Access date: December 14, 2023.

NASA Earth Data, Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC) [Data file] Available from: <https://ladsweb.modaps.eosdis.nasa.gov/> Access date: December 14, 2023.

United States Census Bureau (2019), American Community Survey [Data file] Available from: <https://www.census.gov/programs-surveys/acs> Access date: December 14, 2023.

Wikipedia. 2021. “2021 Texas power crisis.” Last modified October 2, 2021. <https://en.wikipedia.org/wiki/2021_Texas_power_crisis.>↩︎
