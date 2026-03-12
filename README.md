# Swansea Flood Risk vs Deprivation Analysis

An analysis of whether more deprived areas in Swansea face greater flood 
risk exposure, combining WIMD 2019 with NRW flood zone polygons at LSOA level.

## Research Question
> Do more deprived areas in Swansea face greater flood risk exposure?

## Project Structure
```
Swansea-Flood-And-Deprivation-Analysis/
├── data/                  # Raw data files (not tracked by git)
├── notebooks/             # Analysis notebook
├── outputs/               # Generated maps and charts
├── .gitignore
└── README.md
```

## Data Sources
| Dataset                   | Source                    | Link                                                                                                                      |
|---------------------------|---------------------------|---------------------------------------------------------------------------------------------------------------------------|
| LSOA 2011 Boundaries      | ONS Open Geography Portal | https://geoportal.statistics.gov.uk/datasets/ons::lower-layer-super-output-areas-december-2011-boundaries-ew-bfc-v3/about |
| WIMD 2019                 | StatsWales                | https://www.swansea.gov.uk/wimd2019?lang=en                                                                               |
| Flood Map: Rivers and Sea | DataMapWales (NRW)        | https://datamap.gov.wales/layergroups/inspire-nrw:FloodMapforPlanningFloodZones2and3                                      |

## Requirements
pip install geopandas pandas matplotlib scipy