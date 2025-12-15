# Description
This document contains the basic metadata and descriptions for the <code>sysc_buildings_retrofit_inventory</code> geopackage. <code>sysc_buildings_retrofit_inventory</code> contains building-level modelled data on residential embodied and operational carbon emissions associated with different retorfit scenarios. An extended explanation of the modelling undertaken can be found in [Zune et al. (2025)](http://dx.doi.org/10.2139/ssrn.5909647). Note the the provided values are indicative estimates based on worst case assumption about the performance of the existing buildings in 2025. Carbon factors used for grid electricity and gas are also reflect UK national emission factors in 2025.

This work was funded by Research England as part of the South Yorkshire Sustainability Centre at the University of Sheffield.

Cite this data product as
> Zune, M., Arbabi, H., Densley Tingley, D. (2025). Regional Retrofit, Net-Zero Aspirations, and their Whole Life Carbon Burden: South Yorkshire Residential Buildings Retrofit Inventory. [DOI HERE]()

along with its accompanying research output as
> Zune, M., Arbabi, H., Densley Tingley, D. (November 26, 2025). Regional Retrofit, Net-Zero Aspirations, and their Whole Life Carbon Burden. Available at SSRN: https://ssrn.com/abstract=5909647. doi: [10.2139/ssrn.5909647](http://dx.doi.org/10.2139/ssrn.5909647)


# Data fields
* uprn: Unique Property Reference Number associated with the polygon.
* toid: OS Topographic Identifier associated with the polygon.
* treated_floor_area [m2]: Estimated gross floor area based on polygon footprint and height.
* Archetype: One of 15 assigned archetypes of 
    * DT-V: Detached Victorian
    * SD-V: Semi-Detached Victorian
    * B-DT: Detached Bungalow
    * DT-R: Detached Rectangular
    * SD-S: Semi-Detached Small
    * T-RE: End-Terrace Rectangular 
    * SD-R: Semi-Detached Rectangular
    * T-GM: Mid-Terrace Georgian
    * T-VE: End-Terrace Victorian
    * T-VM: Mid-Terrace Victorian
    * DT-L: Detached Large
    * B-SD: Semi-Detached Bungalow
    * T-RM: Mid-Terrace Rectangular
    * T-GE: End-Terrace Georgian
    * None
* Annual Operational Carbon, Existing [kgCO2e/m2]
* Annual Operational Carbon, System Retrofit [kgCO2e/m2]
* Annual Operational Carbon, Fabric Retrofit [kgCO2e/m2]
* Annual Operational Carbon, Whole-house Retrofit [kgCO2e/m2]
* Average Embodied Carbon, System Retrofit [kgCO2e/m2]
* Average Embodied Carbon, Fabric Retrofit [kgCO2e/m2]
* Average Embodied Carbon, Whole-house Retrofit [kgCO2e/m2]
* Min Embodied Carbon, Fabric Retrofit [kgCO2e/m2]
* Max Embodied Carbon, Fabric Retrofit [kgCO2e/m2]
* Min Embodied Carbon, Whole-house Retrofit [kgCO2e/m2]
* Max Embodied Carbon, Whole-house Retrofit [kgCO2e/m2]
* Annual Carbon Savings, System Retrofit [kgCO2e/m2]
* Annual Carbon Savings, Fabric Retrofit [kgCO2e/m2]
* Annual Carbon Savings, Whole-house Retrofit [kgCO2e/m2]
* Embodied Carbon Payback, System Retrofit [years]
* Embodied Carbon Payback, Fabric Retrofit [years]
* Embodied Carbon Payback, Whole-house Retrofit [years]
* Annual Operational Carbon, Existing [tCO2e]
* Annual Operational Carbon, System Retrofit [tCO2e]
* Annual Operational Carbon, Fabric Retrofit [tCO2e]
* Annual Operational Carbon, Whole-house Retrofit [tCO2e]
* Average Embodied Carbon, System Retrofit [tCO2e]
* Average Embodied Carbon, Fabric Retrofit [tCO2e]
* Average Embodied Carbon, Whole-house Retrofit [tCO2e]
* Min Embodied Carbon, Fabric Retrofit [tCO2e]
* Max Embodied Carbon, Fabric Retrofit [tCO2e]
* Min Embodied Carbon, Whole-house Retrofit [tCO2e]
* Max Embodied Carbon, Whole-house Retrofit [tCO2e]
* Annual Carbon Savings, System Retrofit [tCO2e]
* Annual Carbon Savings, Fabric Retrofit [tCO2e]
* Annual Carbon Savings, Whole-house Retrofit [tCO2e]
* geometry: Polygon geometry used to infer floor area and archetype.

# Geogpackage information
Projected CRS: EPSG:27700

Name: OSGB36 / British National Grid 

Axis Info [cartesian]:
- Easting (metre)
- Northing (metre)

Area of Use:
- United Kingdom (UK) - offshore to boundary of UKCS within 49°45N to 61°N and 9°W to 2°E; onshore Great Britain (England, Wales and Scotland). Isle of Man onshore.
- Bounds: (-9.01, 49.75, 2.01, 61.01)

Coordinate Operation:
- British National Grid
- method: Transverse Mercator

Datum: Ordnance Survey of Great Britain 1936
- Ellipsoid: Airy 1830

- Prime Meridian: Greenwich
