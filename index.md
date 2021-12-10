
# A Comparative Analysis of Surface Warming in the Pliocene Model Intercomparison Project Phase 2 (PlioMIP2)
# Alia Wofford
# Introduction

For my CLIM680 project are the the Pliocene and control experiments from the Pliocene Model Intercomparison Project PlioMIP. PlioMIP Phase 2 was  initiated  in  2008  and its core objectives are closely aligned to the US  Geological  Survey  Project  known as  PRISM  (Pliocene  Research  Interpretation  and  Synoptic Mapping). The purpose of this study is to do a comparative analysis study of the Pliocene surface warming patterns simulated by the various climate models that participated in PlioMIP2. Additionally, the models involved in this study will be evaluated on their ability to reproduce climate signals preserved by geological climate archives. The PlioMIP focuses on a time slice of ∼3.2 million years ago in which the climate experienced significant warming. The reconstruction and understanding of the mid-Pliocene climate could allow scientists to  identify  the  dominant  components  driving the mid-Pliocene warming derived from the imposed boundary conditions. All pliocene experiments in PlioMIP2 were required to use standardized boundary condition datasets for the core midPliocene-eoi400 experiment. Whereas, control experiments utilized a standardized boundary condion datasets were set to eoi280 in reference to the Carbon Dioxide levels. In my study specifically, I am plotting surface temperature variables from each of the Pliocene and the control experiments to analyze surface warming in the global mean temperatures. The ultimate goal of this study is conduct a model-data comparison with compiled proxy data of subsurface oceanic warming during the Pliocene.


# Data and Methods
A total of 14 global climate models were analyzed in this study. Each model provided a Pliocence experiment and a control experiment. Only the surface temperature have been analyzed in this intial project. The table lists the PlioMIP2 models that were analyzed.

| Model Name|
| --- | --- |
| CCSM4  |
| CESM 1.2 | 
|CESM2 |
|COSMOS|
|EC-EARTH|
|EC-EARTH 3.3|
|IPSLCM6_LR|
|IPSLCM6_LR_2.1|
|UoFT|
|Utrecht|
|MIROC4|
|LEEDS|
|MRI_CGCM2_3|
|NorESM_L|


Monthly mean output files of surface temperature have been converted to a 12 month climatology for each model to calculate composites for the global mean temperatures for both the Pliocene and Preindustrial experiments.as well as anomalies to determine the variations in temperature between models during the Pliocene. In my dataset, there are five different models that have modified code versions of CCSM/CESM all the model configurations are  described in Ran et al., 2020. All datasets have been regridded to a regular lat-lon grid to make comparison of models more consistent. In addition all data files were converted to Kelvin. To calculate the difference for the global mean temperatures the control experiments were subtracted from the Pliocene experiment datasets for all models included in our analysis. Lastly, the study only focused on the last 100 years of each experiment for analysis.

# Results and Analysis

### Project Notebook via Github
### Conda Environment 
The environment.yml file is shown to define the environment needed to run all code successfully. 

### Figures

![1](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/12_Panel_Monthly_GlobalMean_Pliocene.png?raw=true)

Figure 1 shows the 12 month climatology calculated from the mean of all 14 models.

![2](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/12_Panel_Monthly_GlobalMean_Control.png?raw=true)

Figure 2 above shows the 12 month climatology calculated from the mean of all 14 Preindustrial control experiments.

![3](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/12_Panel_Monthly_GlobalMean_Difference.png?raw=true)

Figure 3 shows the 12 month climatology of the multi-model mean Pliocene Preindustrial control warming. The warming is polar amplified.

![4](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Multi_model_ann_mean_SurTemp.png?raw=true)

Figure 4 shows the multi model mean , annual mean surface temperature change which displays warmer temperature changes in the polar regions in both hemispheres. Specifically around the North America and Eurasia, and in the Antarctica. Whereas temperature changes are milder in the tropics and equator.

![5](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Global_Mean_SAT_SCATTER.png?raw=true)

Figure 5 shows the global mean suface temperatures for both the Preindustrial control(blue) and the Pliocene experiments(orange).

![6](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Global_Mean_tempchange_scatter.png?raw=true)

Figure 6 shows the global mean surface temperature change between the Pliocene and Preindustrial experiments. The gray line defines the limit upon which the high versus low global warming composite are based. The Pliocene minus Preindustrial Control warming ranges from 1.7 to 5.2 ◦C.
 
### Composites


![7](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/CompGlobalmean_surf_temp_high.png?raw=true)

Figure 7 shows the composite global mean surface temperatures for models with a temperature change greater than 3◦. On average these models have larger warmer temperature changes in the polar regions which specifically in the northern and southern hemisphere.

![8](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/CompGlobalmean_surf_temp_low.png?raw=true)

Figure 8 shows the composite global mean surface temperatures for experiments with a temperature change less than 3◦. In general the figure showed that warmer temperature changes were more geographically isolated in the polar regions. Specifically the warmer temperatures were seen to be the strongest over the Greenland areas in the northern hemisphere and over the Antartic polar regions in the southern hemisphere.


![9](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/CompGlobalmean_surf_temp_diff.png?raw=true)

Figure 9 shows the composite global mean surface temperatures for the Pliocene and Preindustrial control difference. In general the figure showed that all models showed agreement with warmer temperature changes that were geograpically isolated in the polar regions. Specifically the warmer temperatures were seen to be the strongest over the Greenland areas in the northern hemisphere and over the Antartic polar regions in the southern hemisphere.

![10](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Regression_Model_Mean_SurfaceTemperature_Change.png?raw=true)

Figure 10 shows the regression of the model mean surface temperature change. The warmer temperatures are seen to be stronger over the Eurasia regions and in Anarctic where as the composites are showing more warming in the northern hemisphere.


![11](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Correlation_between_ModelMean_SurfaceTemperatures.png?raw=true)

Figure 11 shows the correlation between the Model Mean surface temperatures. Contrary to the regression the correlation that most of the variance in the degree of Pliocene minus Preindustrial global mean warming is coming from model differences in the degree of tropical warming, particularly in the Atlantic and Indian Oceans, as well as the western and southern Pacific.



![12](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/CompGlobalmean_surf_temp_diff_weight.png?raw=true)

<a href="https://github.com/aliawofford1/aliawofford1.github.io/blob/8ab2294dac0a9a050a9fb8501aef801884a52220/Clim680_project_plots.ipynb"> Notebook </a>

The figures from my project notebook are saved in a seperate 'figures' subdirectory, as well as shown in the project notebook.

# Summary
The findings of the Haywood paper in regards to the temperature change. In our analysis, the Pliocene model composites showed warm temperature changes that were geographically isolated to the polar regions near Greenland and Antartica. Upon further analysis, the regression of the model mean surface temperature change showed that the warmer temparture changes were stronger over the Eurasia regions and in Anartic contrary to the composites. However, contrary to the regression the correlation revealed that the Pliocene minus Preindustrial global mean showed the most variance in global mean warming coming from model differences in the degree of tropical warming in the Atlantic and Indian Oceans. This study also provided insight to how much tropical warming could be a significant contributing factor in the increased warming that occured in the Pliocene history.

# References
Haywood, A. M., Dowsett, H. J., Dolan, A. M., Rowley, D., Abe-Ouchi, A., Otto-Bliesner, B., Chandler, M. A., Hunter, S. J., Lunt, D. J., Pound, M., &amp; Salzmann, U. (2016). The Pliocene Model Intercomparison Project (pliomip) phase 2: Scientific  objectives and experimental design. Climate of the Past, 12(3), 663–675. https://doi.org/10.5194/cp-12-663-2016 

Haywood, A. M., Tindall, J. C., Dowsett, H. J., Dolan, A. M., Foley, K. M., Hunter, S. J., Hill, D. J., Chan, W.-L., Abe-Ouchi, A., Stepanek, C., Lohmann, G., Chandan, D., Peltier, W. R., Tan, N., Contoux, C., Ramstein, G., Li, X., Zhang, Z., Guo, C., … Lunt, D. J. (2020). The Pliocene Model Intercomparison Project Phase 2: Large-scale climate features and climate sensitivity. Climate of the Past, 16(6), 2095–2123. https://doi.org/10.5194/cp-16-2095-2020 

