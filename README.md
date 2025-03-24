# SOC-Modeling-Data-Preparation-and-Optimization
SOC change (2009–2018) was calculated, data cleaned, categorical variables one-hot encoded, and stored in a CSV. A Random Forest model was trained, and GridSearchCV optimized hyperparameters. 5-fold cross-validation determined the best parameters, improving model accuracy.

# Data
The LUCAS-SOIL-2018 CSV file contains the identification code “PointID” of the sample points and data of physical and chemical properties for each sample. This “PointID” is unique for the 2018 LUCAS soil survey, as documented in https://ec.europa.eu/eurostat/web/lucas/data/primary-data/2018
