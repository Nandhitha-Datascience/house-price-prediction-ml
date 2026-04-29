# 🏡 House Price Prediction using Machine Learning

## Objective
The goal of this project is to predict house prices based on key features such as living area, quality, and other property characteristics using machine learning techniques.

## Dataset
The dataset contains information about residential properties, including:
- Living Area (GrLivArea)
- Overall Quality (OverallQual)
- Garage Capacity (GarageCars)
- Basement Area (TotalBsmtSF)
- Year Built (YearBuilt)
- Sale Price (Target Variable)

## Data Preprocessing
- Handled missing values using median imputation  
- Converted and cleaned data formats  
- Applied **log transformation** to reduce skewness in target variable  
- Performed **feature scaling** using StandardScaler  

## Model Building
The following models were implemented and compared:
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

## Model Performance

| Model              | R² Score|
|------------------- |---------|
| Linear Regression  | 0.83    |
| Decision Tree      | 0.77   |
| Random Forest      | 0.84   |

Linear Regression & Random Forest performed the best for this dataset.

## Visualization
### Actual vs Predicted Prices
This plot compares actual house prices with predicted values.

Key Insights:
- Most predictions are close to actual values  
- Model performs well for mid-range prices  
- Some deviation exists for extreme values  

## Key Insights
- Overall quality and living area are strong predictors of house price  
- Proper preprocessing significantly improves model performance  
- Simpler models like Linear Regression can perform well with the right features  

## Conclusion
This project demonstrates how data preprocessing and feature selection can improve model accuracy and help build reliable prediction systems.

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
