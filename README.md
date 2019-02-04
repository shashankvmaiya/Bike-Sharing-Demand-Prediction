# Bike-Sharing-Demand-Prediction
In this project, we train a model to predict the number of bike rentals at any hour of the year given the weather conditions. The data set was obtained from the Capital Bikeshare program in Washington, D.C. which contained the historical bike usage pattern with weather data spanning two years.

We first look at several individual regression models such as Linear, Ridge, Random Forest and Gradient Boost. We then use 'Stacking' approach where the predictions from these level 1 individual models were used as meta-features for a second level model (Linear Regressor, Random Forest and Gradient Boost) to further enhance the predicting capabilities.

The key takeaway from the EDA and Modeling is that 

Below figure 
<img width=600 height=300 src="./Images/results/pred_vs_actual_rf1.png"/>