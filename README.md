# bst209-final-project-Diana
Machine Learning in Healthcare Final Project

The working project file is called "NHANES_project_overview_Diana.Rmd". Temporarily, it was saved under the "data" folder.


# Project Overview

The National Health and Nutrition Examination Survey(NHANES) assesses the health and nutritional statusof adults and children in the United States.The goal is to use these covariates to predict the occurrence of diabetes, cancer, heart attack, stroke,OR depression.
   
## Research Question
   
Identify a predictive model for the risk of diabetes based on a combination of dietary, demographic, lab and examination factors  from the NHANES US national survey using Machine Learning methods.
   
## Data Source
   
The National Health and Nutrition Examination Survey (NHANES) assesses the health and nutritional status of adults and children in the United States. The `covariate_df` data frame in the `covariate_df.rData` file contains the demographic, examination, diet, and lab data from [NHANES 2013-2014](https://www.kaggle.com/datasets/cdc/national-health-and-nutrition-examination-survey). You can peruse the dictionaries for the variables on the CDC website: [demographics](https://wwwn.cdc.gov/Nchs/Nhanes/Search/variablelist.aspx?Component=Demographics&CycleBeginYear=2013), 
[examinations](https://wwwn.cdc.gov/Nchs/Nhanes/Search/variablelist.aspx?Component=Examination&CycleBeginYear=2013), 
[diet](https://wwwn.cdc.gov/Nchs/Nhanes/Search/variablelist.aspx?Component=Dietary&CycleBeginYear=2013), and
[lab](https://wwwn.cdc.gov/Nchs/Nhanes/Search/variablelist.aspx?Component=Laboratory&CycleBeginYear=2013). 

Your goal is to use these covariates to predict the occurrence of diabetes, cancer, heart attack, stroke, OR depression. The company wants you to recommend a predictive model and identify key variables that appear to be associated with the outcome disease. 
   
## Methods
* Load data 
* select outcome and covariates and perform data cleaning and processing
* Visualize the relationship between covariates and outcome (4-10 outputs)
* Build machine 3 learning model