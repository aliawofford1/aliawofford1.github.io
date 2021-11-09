# Compartive analysis of Pliocene Models Investigating Variations In Global Mean Temperature 
# Alia Wofford
# Introduction
My datasets I chose for my CLIM680 project are the the Pliocene model and control experiments from the Pliocene Model Intercomparison Project (PLIOMP). The purpose of this study is to do a multi model comparative analysis study of Pliocene models by analyzing the changes in the global mean temperatures between models. Specifically, I am using the upper ocean temperatures and surface temperature variables in the various Pliocene experiments and control model simulations to make this comparison. The overaching goal of this study is conduct a model-data comparison with compiled proxy data to reconstuct the oceanic warming patterns seen in the Pliocene time period.


# Data
The following are datasets that are being used in my project:
-CCSM4 (CESM with CAM4 atmosphere)
-CESM 1.2 (CESM with CAM5 atmosphere)
-CESM2 (CESM with CAM6 atmosphere)
-COSMOS
-EC-EARTH 3.3 

Replacing the ERA-interim reanalysis, ERA5 is the fifth generation ECMWF reanalysis for the global climate and weather for the past 4 to 7 decades. Using data from 1979 onwards, ERA5 provides monthly estimates for a large number of atmospheric, ocean-wave, and land-surface quantities. Data has been regridded to a regular lat-lon grid of 0.25 degrees for the reanalysis and 0.5 degrees for the uncertainty estimate. 
Variables utilized are 'total precipitation', the sum of large scale and convective precipitation that is the accumulated liquid and frozen water, comprising rain and snow, that falls to the Earth's surface, with 1 day accumulation period for monthly averaged reanalysis. Units are meters. 'Total cloud cover' is also used as a dimensionless quantity that varies from 0 to 1, being the proportion of a grid box covered by cloud. 'Total column water vapor', more commonly called precipitable water, is also utilized, defined as the total amount of water vapor in a colun extending from the surface of the Earth to the top of the atmosphere. This is measured in kgm^-2. A land-sea mask, a dimensionless quantity, that represents the proportion of land, as opposed to ocean or inland waters in a grid box, is also utilized. Values above 0.5 can be comprised of a mixture of land and inland water, but not ocean. 
### PLIOCENCE DATA CALCULATION 
Annual means files from both ocean temperature (POP) and land temperature (CAM) have been converted to a 12 month climatology for each model to calculate composites for the global mean temperatures for each model as well as anomalies to determine the variations in temperature between models during the Pliocene.
# Results and Analysis
### Project Notebook via Github
### Conda Environment 
The environment.yml file is shown to define the environment needed to run all code successfully. 
### Figures
The figures from my project notebook are saved in a seperate 'figures' subdirectory, as well as shown in the project notebook.
# Summary



