# T2D-prediction-automated-feature-engineering
This repository shows the codes used to explore the effectiveness of Automated Feature Engineering in combination with a Hybrid Data-Driven Feature selection approach using the Whitehall II Dataset. 

The title of the thesis that explored this was: "Type 2 Diabetes Prediction Using Automated Feature Engineering and Data-Driven Feature Selection - Revealing Undiscovered Predictors". The main goal was to compare the features that are engineered and selected through a manual approach, with the features derived through an automated approach. 

The data used for this research is the Whitehall II data, which is not publicly available. The code made available in this repository functions as a guideline to replicate the proposed method using different data. The automated feature engineering (AFE) notebook shows how AFE was applied, and how the correct data types were assigned. 

The order in which I used the notebooks is:
1. data_set_creation - shows how I created the DataFrame with all the features of interest
2. data_cleaning - shows how I cleaned the data 
3. automated_feature_engineering - shows how I automatically engineered features using FeatureTools (includes Minimum Redundancy Maximum Relevance Feature Selection)
4. LogisticRegression & XGBoost - shows how I fitted two models on the engineered features (includes hyperparameter tuning and SHAP plots)
