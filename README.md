### PREDICTING THE FUNCTIONAL STATE OF TANZANIAN WATER PUMPS

#### Problem Statement:

Tanzania, as a developing country, struggles with providing clean water to its population of over 57,000,000. There are many waterpoints already established in the country, but some are in need of repair while others have failed altogether.

For this project I need to build a classifier to predict the condition of a water well, using information about the sort of pump, when it was installed, etc. The final model will classify the condition of water wells into 3 categories namely

functional - the waterpoint is operational and there are no repairs needed

functional needs repair - the waterpoint is operational but needs repairs

non-functional - the waterpoint is not operational

By predicting the pumps which are functional but needs repair, decreases the overall cost for the Tanzanian Ministry of Water. Which can improve the maintenance operations of the water pumps and make sure that clean, potable water is available to communities across Tanzania.

#### Plan:

1.Understanding Data

2.Cleaning and Exploring Data

3.Preparing Data to Modeling

4.Ternary Target Modeling

5.Visualizations

6.Conclusions

7.Future work

#### Data

The data for this project comes from the Taarifa waterpoints dashboard, which aggregates data from the Tanzania Ministry of Water.

You may find and download the data here https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/23/ after signing up for the competition.

In this project, I will use train set and train label set (contains the status of every Pump Observatin in the training dataset).


#### Conclusions

My model can predict the functionality of the water wells with 80% accuracy. That number is high enough but my model can use some hyperparameter optimization to get that number even better.

Based on my research I can recommend :

1.Make functional wells one of the State priorities (including budgeting, financial incentives).

2.Create a strategy plan on preventing of emerging new non functional wells.

#### Future Work:

1.Solve Imbalanced target problem by using SMOTE oversampling technique to create balanced data.

2.Use Grid Search to Optimise CatBoost Parameters and/or KNN

3.Create a visual representation of how different values affect predictions (feature importance with catboost)


