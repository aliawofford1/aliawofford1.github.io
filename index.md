## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/aliawofford1/aliawofford1.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

# Comparative Analysis of Pliocene Models Investigating Variations In Global Mean Temperature  
# Alia Wofford
# Introduction
My datasets I chose for my CLIM680 project are the the Pliocene model and control experiments from the Pliocene Model Intercomparison Project (PLIOMP). The purpose of this study is to do a multi model comparative analysis study of Pliocene models by analyzing the changes in the global mean temperatures between models. Specifically, I am using the upper ocean temperatures and surface temperature variables in the various Pliocene experiments and control model simulations to make this comparison. The overaching goal of this study is conduct a model-data comparison with compiled proxy data to reconstuct the oceanic warming patterns seen in the Pliocene time period.


# Data
The following are datasets that are being used in my project:
-CCSM4 (CESM with CAM4 atmosphere) + CONTROL
-CESM 1.2 (CESM with CAM5 atmosphere) + CONTROL
-CESM2 (CESM with CAM6 atmosphere)+ CONTROL
-COSMOS + CONTROL
-EC-EARTH 3.3 + CONTROL


### PLIOCENCE DATA CALCULATION 
Annual means files from both ocean temperature (POP) and land temperature (CAM) have been converted to a 12 month climatology for each model to calculate composites for the global mean temperatures for each model as well as anomalies to determine the variations in temperature between models during the Pliocene.
Each model experiment ran for a total of 100 years. In my dataset there are three different CCSM/CESM models code versions  all of which model configurations are  described in Ran et al., 2020. In all POP ocean datasets has been regridded to a regular lat-lon grid to make comparison of models more consistent with the (CAM) surface temperature datasets. In addition all data files were converted to Kelvin. To calculate the anomly for the global mean temperatures the control experiment datasets for all models were includeded in our data. 
# Results and Analysis
### Project Notebook via Github
### Conda Environment 
The environment.yml file is shown to define the environment needed to run all code successfully. 
### Figures


![1](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/12_Panel_Monthly_GlobalMean_Pliocene.png?raw=true)

![2](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/12_Panel_Monthly_GlobalMean_Control.png?raw=true)


![3](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/12_Panel_Monthly_GlobalMean_Difference.png?raw=true)




![4](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/CompGlobalmean_surf_temp_diff.png?raw=true)


![5](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/CompGlobalmean_surf_temp_diff_weight.png?raw=true)


![6](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/CompGlobalmean_surf_temp_high.png?raw=true)


![7](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/CompGlobalmean_surf_temp_low.png?raw=true)


![8](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Correlation_between_ModelMean_SurfaceTemperatures.png?raw=true)


![9](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Correlation_ModelMean_SurfaceTemperatures_Difference.png?raw=true)


![10](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Global_Mean_SAT_SCATTER.png?raw=true)


![11](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Global_Mean_tempchange_scatter.png?raw=true)


![12](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Multi_model_ann_mean_SurTemp.png?raw=true)


![13](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/R_Array_ModelMean_Surface_Temperature.png?raw=true)


![14](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Regression_Model_Mean_SurfaceTemperature_Change.png?raw=true)



The figures from my project notebook are saved in a seperate 'figures' subdirectory, as well as shown in the project notebook.
# Summary



