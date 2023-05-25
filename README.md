This GitHub repository contains the code (as three separate R notebooks) and data used in the paper: "Can local management practices offset the impacts of climate change on freshwater macroinvertebrate communities?" by James A. Orr, Gianbattista Bussi, Jocelyne M.R. Hughes, Paul G. Whitehead and Michelle C. Jackson.

The folder "data" contains raw data (biomonitoring data, shapefiles, water quality data) as well as results (regression outputs, organised datasets, ecological forecats, process-based modelling outputs) from the analyses.

In "1_organisation.Rmd" we load macroinvertebrate and water quality data from the Thames catchment and we temporally and spatially join these into combined datasets for each year.

In "2_regressions.Rmd" we perform generalized linear mixed effects models on community and taxon-specific macroinvertebrate responses. The models are constructed using data between 2002 and 2020 and they are validated with data from 2021 and 2022. The outputs of the regression models are used to make ecological forecasts based on the outputs of the process-based models. 

In "3_plots.Rmd" we plot all of the figures in the main text and in the supporting information of the paper. 
