**Project Title: Used Car Price Prediction**

**Introduction:**
This project aims to predict the prices of used cars based on various features such as car age, odometer reading, cylinders, and more. We explore different regression models to find the best-performing one for this task.

**Key Findings:**

**Model Performance:**  
We evaluated three regression models: Linear Regression, Decision Tree, and Random Forest. The Random Forest model outperformed the others with the lowest RMSE, indicating superior predictive performance.

- **Linear Regression:**
  - RMSE: 0.796
  - MAE: 0.582
  - R-squared: 0.364

- **Decision Tree:**
  - RMSE: 0.678
  - MAE: 0.454
  - R-squared: 0.539

- **Random Forest:**
  - RMSE: 0.652
  - MAE: 0.437
  - R-squared: 0.573

**Significant Features:**  
In all models, car age, odometer, and cylinders were found to be the most influential features affecting the predicted prices of used cars. Conversely, features such as title status, condition, and region had minimal influence on the predictions.

**Data Quality:**  
Ensuring high-quality data significantly enhances model performance. Preprocessing steps such as handling missing values, treating outliers, and feature engineering contributed to improved accuracy in predicting car prices.

**Conclusion:**
The Random Forest model demonstrated the best performance in predicting used car prices. Features like car age, odometer reading, and cylinder count were identified as key factors influencing the prices. By ensuring data quality and utilizing appropriate regression models, accurate predictions can be made for used car prices, aiding both buyers and sellers in making informed decisions.