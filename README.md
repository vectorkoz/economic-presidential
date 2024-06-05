# economic-presidential
This repo contains 2 projects exploring the relationship between economic indicators and results of U.S. Presidential elections from 1976 to 2020, while using using Python, Jupyter Notebook, scikit-learn, pandas, geopandas, numpy, scipy, matplotlib, seaborn.

Note: feature-selection-linear-regression was completed in September 2023, 2020-US-presid-election-by-state-classification was completed in January 2024.
## Brief summary of the projects
 - Data cleaning, data wrangling, creating a custom dataset
 - Feature engineering
 - Linear Regresssion models
 - Feature selection with Lasso Regression
 - Logistic Regression models
 - Support Vector Machines (with and without kernels)
 - Random Forest models
 - Gradient Boosting models
 - Ensemble learning
 - Model explanations: Gini importance, permutation feature importance, LIME.
 - Choropleths (geographic plots).
 - High scores achieved predicting 2020 election results on 1976-2016 data (see below).
![Choropleth showing a prediction for the 2020 election](https://github.com/vectorkoz/economic-presidential/blob/main/2020-US-presid-election-by-state-classification/data/winner_-_Stacking.png?raw=true)

## Data summary
 - [U.S. President 1976–2020](https://doi.org/10.7910/DVN/42MVDX) - state-level results of U.S. Presidential electionsin 1976-2020 by MIT Election Data and Science Lab. 
 - [State-level economic data](https://apps.bea.gov/regional/histdata/releases/0921spi/index.cfm) - historical data on employment, income, taxes, benefits etc., by U.S. Bureau of Economic Analysis.

## feature-selection-linear-regression
 - [Data cleaning code](https://github.com/vectorkoz/economic-presidential/blob/main/feature-selection-linear-regression/presid_cleaning.ipynb)
 - [Feature engineering code](https://github.com/vectorkoz/economic-presidential/blob/main/feature-selection-linear-regression/pres%2Becon_feature_engineering.ipynb)
 - [Resulting dataset](https://github.com/vectorkoz/economic-presidential/blob/main/feature-selection-linear-regression/data/data.csv)
 - [Linear regression models and detained project summary](https://github.com/vectorkoz/economic-presidential/blob/main/feature-selection-linear-regression/project_feature_selection.ipynb)

## 2020-US-presid-election-by-state-classification
 - [Feature enginnering for classification](https://github.com/vectorkoz/economic-presidential/blob/main/2020-US-presid-election-by-state-classification/feateng.ipynb)
 - [Code for all classification models, choropleths and model explanations](https://github.com/vectorkoz/economic-presidential/blob/main/2020-US-presid-election-by-state-classification/project_classification.ipynb)
 - [Full report on the project](https://github.com/vectorkoz/economic-presidential/blob/main/2020-US-presid-election-by-state-classification/REPORT.pdf)
