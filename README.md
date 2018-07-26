# Climate_Data_Analysis

Analysis of climate data produced by CNR in the context of ECOPOTENTIAL project.

Original data description: 
  - 5 global models downscaled through RNA4 regional model
  - Historical period: 1970-2006
  - Projections: from 2006-2100, basd on two IPCC scenarios (RCP4.5 and RCP8.5)
  - Two variables: temperature and precipitation
  - Time resolution: 3h
  - Spatial resolution: 0.11º
  
Pre-processing of historical period data:
  Through CDO (Climate Data Operator), calculation of several metrics for analysis:
  Temperature: yearmean, monmean, daymin, daymax, seasonal yearmeans
  Precipitation: yearsum, monsum, yearmean, seasonal yearsums

  Resulting data to use for analysis:
  - 5 global models downscaled through RNA4 regional model (CNRM, ICHEC, IPSL, MOHC, MPI)
  - Only historical period (1970-2006)
  - Two variables: temperature and precipitation
  - Time resolution: yearly, seasonal, monthly, daily
  - Spatial resolution: 0.11º