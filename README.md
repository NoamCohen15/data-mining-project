# Data Mining Course - Final Project
## Ariel University

The data taken from: https://www.kaggle.com/datasets/rtatman/188-million-us-wildfires

*Project goal*: Build a model for predicting the cause of the fire, based on the existing features in the data and adding external features.

*NoteBooks:*

1. First irrelevant features selection.ipynb - notebooks that :  Initial selection of features from the given features.
   
2. First EDA + Basline Random Forest.ipynb : Execute EDA for the selected features in the previous notebook, also creating a baseline with f1_score as evaluation metric.
   
3. Time.ipynb : Creating time based features.
   
4. Elevation.ipynb : Extraction of external data for the observations, adding Elevation given Latitude and Longitude.
   
5. Weather.ipynb : Extraction of external data for the observations, adding Weather features given Latitude, Longitude, Elevation and Date.
   
6. All preprocess + choose model.ipynb : Combining all previous notebooks results, creating full pipeline and final model. 
