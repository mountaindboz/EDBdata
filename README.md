
<!-- README.md is generated from README.Rmd. Please edit that file -->

# EDBdata

<!-- badges: start -->

[![R-CMD-check](https://github.com/mountaindboz/EDBdata/workflows/R-CMD-check/badge.svg)](https://github.com/mountaindboz/EDBdata/actions)
<!-- badges: end -->

An R data package containing data sets used in the Emergency Drought
Barrier (EDB) analysis. This data package also contains useful metadata
describing the data sets and the processing scripts used to derive the
data.

This package provides the following data tables:

-   `hab_sat_ow_delta`: Summary of Cyano Index values derived from HAB
    satellite data for four open water regions in the upper San
    Francisco Estuary (Delta): Franks Tract, Mildred Island, Clifton
    Court Forebay, and Liberty Island. Summary statistics cover the
    spring through late fall (May-Dec) in 2020 and 2021. Includes
    averages of Cyano Index for each region and date in addition to
    pixel counts within 4 Cyano Index categories.
-   `phyto_edb`: Phytoplankton community data collected by DWR’s
    Environmental Monitoring Program from 2014-2021 for stations within
    the Emergency Drought Barrier regions
-   `phyto_hab`: Phytoplankton community data of potentially toxic
    Cyanobacteria collected by DWR’s Environmental Monitoring Program at
    various locations in the Delta from 2014-2021
-   `cont_chla_daily`: Daily average and median values of continuous
    chlorophyll fluorescence measured in the water in-situ at the
    stations within the Emergency Drought Barrier regions. Data was
    collected by DWR and USGS from 2020-2021.
-   `disc_nutr_chla`: Concentrations of chlorophyll-a and three nutrient
    parameters (Dissolved Ammonia, Dissolved Nitrate + Nitrite, and
    Dissolved Ortho-phosphate) in water samples collected at various
    locations in the Delta east of Chipps Island for 2014-2021
-   `hab_toxins`: Cyanotoxin concentrations in whole-water grab samples
    collected at various locations in the Delta in 2021
-   `mc_vis_index_wq`: *Microcystis* visual index, secchi depth, and
    water temperature data collected at various locations in the Delta
    from 2007-2021

## Installation

You can install the latest version from [GitHub](https://github.com/)
with:

``` r
# install.packages("devtools")
devtools::install_github("mountaindboz/EDBdata")
```

## Data Sources

San Francisco Estuary Institute (SFEI). Harmful Algal Blooms Analysis
Tool. <https://fhab.sfei.org/>

Phytoplankton data was acquired from DWR’s Environmental Monitoring
Program through direct data requests

California Department of Water Resources (DWR) Water Data Library (WDL):
<https://wdl.water.ca.gov/WaterDataLibrary/>

USGS National Water Information System (NWIS):
<https://nwis.waterdata.usgs.gov/nwis>

`discretewq` data package (version 2.3.2):
<https://github.com/sbashevkin/discretewq/tree/v2.3.2>

Water Quality Portal hosted by the National Water Quality Monitoring
Council: <https://www.waterqualitydata.us/>
