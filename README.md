This project applies Machine Learning regression techniques to predict bike rental demand based on historical usage and environmental conditions.
The dataset comes from the UCI Bike Sharing Dataset, containing hourly and daily rental counts with weather and temporal features.

The goal is to compare different regression models (linear and tree-based) and evaluate which performs best for predicting rental demand.

Structure:
**Data preprocessing**  
  - Missing values handling  
  - Feature engineering (seasonality, weather, holidays, working day flags)  
  - Train/test split  
**Exploratory Data Analysis (EDA)**  
  - Correlation heatmaps  
  - Demand trends across **season, weekday, and weather**
**Models tested**  
  - Linear Regression  
  - Ridge & Lasso Regression  
  - Random Forest Regressor  
  - Gradient Boosting Regressor  
**Evaluation Metrics**  
  - R² Score  
  - RMSE (Root Mean Squared Error)  
  - MAE (Mean Absolute Error)  
