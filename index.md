## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/aliawofford1/aliawofford1.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

# Comparative Analysis of Pliocene Models Investigating Variations In Global Mean Temperature  
# Alia Wofford
# Introduction
My datasets I chose for my CLIM680 project are the the Pliocene model and control experiments from the Pliocene Model Intercomparison Project (PLIOMP). PLIOMP was  initiated  in  2008  and its core objectives are closly aligned to the US  Geological  Survey  Project  known as  PRISM  (Pliocene  Research  Interpretation  and  SynopticMapping). The purpose of this study is to do a multi model comparative analysis study of Pliocene models by analyzing the changes in the global mean temperatures between models. The PlioMIP project is a cooperative international intiative that analyzes the consistency of model predictions simulating the Pliocene climate. Models involved in the study can then be evaluated  their ability to reproduce climate signals preserved by geological climate archives. The Pliocence climate focuses on a ~∼3.3 to 3 million years ago time scale in which the climate experienced significant warming. The reconstruction and understanding of the mid-Pliocene climate could allow scientists to  identify  the  dominant  components  driving the mid-Pliocene warming derived from the imposed boundary conditions. In my study I specifically, am using surface temperature variables in the various Pliocene experiments and control model simulations to analyze global mean temperature. The overaching goal of this study is conduct a model-data comparison with compiled proxy data to reconstuct the oceanic warming patterns seen in the Pliocene time period.



# Data
A total of 14 models were analyzed in this study. Each model provided a Pliocence experiment and a control experiment. Only the surface temperature variables were included and analyzed in this project.The following are the datasets that are being used in my project.

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




### PLIOCENCE DATA CALCULATION 
Annual means files from surface temperature (CAM) have been converted to a 12 month climatology for each model to calculate composites for the global mean temperatures for each model as well as anomalies to determine the variations in temperature between models during the Pliocene.
Each model experiment ran for a total of 100 years. In my dataset there are three different CCSM/CESM models code versions  all of which model configurations are  described in Ran et al., 2020. In all POP ocean datasets has been regridded to a regular lat-lon grid to make comparison of models more consistent with the (CAM) surface temperature datasets. In addition all data files were converted to Kelvin. To calculate the anomly for the global mean temperatures the control experiment datasets for all models were includeded in our data. All pliocene experiments in PlioMIP2 were required to use standardized boundary condition datasets for the
core midPliocene-eoi400 experiment. Whereas, control experiments utilized a standardized boundary condion datasets were set to eoi280 in reference to the Carbon Dioxide levels.Lastly,each experiment consisted of the last 100 years of each experiment for analysis..

# Results and Analysis
### Project Notebook via Github
### Conda Environment 
The environment.yml file is shown to define the environment needed to run all code successfully. 
### Figures


![1](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/12_Panel_Monthly_GlobalMean_Pliocene.png?raw=true)

Figure 1 shows the 12 month annual climatology calculated from the mean of all 14 experiments.

![2](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/12_Panel_Monthly_GlobalMean_Control.png?raw=true)

Figure 2 above shows the 12 month annual climatology calculated from the mean of all 14 control experiments.

![3](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/12_Panel_Monthly_GlobalMean_Difference.png?raw=true)
Figure 3 shows the 12 month annual climatology global mean diference calculated from the difference in the Pliocene experiments- control experiments from all 14 experiments. The yellow areas seen in the polar regions of the northen and southern hemisphere suggest warmer temperatures are more prominent in these regions.

![4](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Multi_model_ann_mean_SurTemp.png?raw=true)
Figure 4 shows the multi model mean surface temperature change which displayed warmer temperature changes in the polar regions in both hemisphere. Specifically around the North America and Eurasia, and in the Antarctica . Whereas temperature changses were milder in the tropics and equator.

![5](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Global_Mean_SAT_SCATTER.png?raw=true)
Figure 5 shows the global mean suface temperatures for both the control(blue) and the pliocene experiments(orange). Model experiments were seen to have generally higher global mean surface temperatures than the control group.

![6](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Global_Mean_tempchange_scatter.png?raw=true)
Figure 6 shows the global mean surface temperature change between models. The gray line defines the limit in which to composite my datasets. Our findings of temperature change showed that compared to each of the contributing from the experiment ranged from 1.7 to 5.2 ◦C.
 
### Composites


![7](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/CompGlobalmean_surf_temp_high.png?raw=true)
Figure 7 shows the composite global mean surface temperatures for experiments with a temperature change greater than 3◦. In general the figure showed warmer temperature changes in the polar regions which specifically in the northern and southern hemisphere.

![8](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/CompGlobalmean_surf_temp_low.png?raw=true)
Figure 8 shows the composite global mean surface temperatures for experiments with a temperature change less than 3◦. In general the figure showed that warmer temperature changes were more geographically isolated in the polar regions. Specifically the warmer temperatures were seen to be the strongest over the Greenland areas in the northern hemisphere and over the Antartic polar regions in the southern hemisphere.


![9](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/CompGlobalmean_surf_temp_diff.png?raw=true)

Figure 9 shows the composite global mean surface temperature difference . In general the figure showed variablility in te models as it showed where models agree The temperature change showed that the global mean temperatures for the modes are strongest over the Greenland are in the northern hemisphere and that less models.

![10](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Regression_Model_Mean_SurfaceTemperature_Change.png?raw=true)
Figure 10 shows the regression of the model mean surface temperature change. The warmer temperatures are seen to be stronger over the Eurasia regions and in Anarctic where as the composites are showing more warming in the northern hemisphere .


![11](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/Correlation_between_ModelMean_SurfaceTemperatures.png?raw=true)
Figure 11 shows the correlation between the Model Mean surface temperatures. Contrary to the regression the correlation shows strong warm temperatures coming more so from the tropics in the eastern and western warm pool tongue.



![12](https://github.com/aliawofford1/aliawofford1.github.io/blob/main/docs/assets/CompGlobalmean_surf_temp_diff_weight.png?raw=true)


The figures from my project notebook are saved in a seperate 'figures' subdirectory, as well as shown in the project notebook.
# Summary
The study showed that the models did match the findings of the Haywood paper in regards to the temperature change. Warm temperature changes were seen to be stronger in the polar regions of the northern and southern hemisphere. However with our correlation we were seeing temperature difference that was coming from the tropics in the eastern and western warm pool tongue. This study also provide insight on the dynamics of determing how much of an influence the eastern and westen warm pool tongue could be a significant contributing factor to warming in the Pliocene history. 



