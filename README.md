## Project Overview: Predicting House Prices
This project implements a comprehensive machine learning pipeline to predict residential real estate prices. The analysis covers the entire lifecycle of a data science project, including data preprocessing, exploratory analysis, and predictive modeling using regression techniques.

### Key Features:
* **Data Imputation:** Implemented specialized strategies for missing values, including median imputation for numerical data and category-based "None" labels for optional house features (e.g., Pool, Alley).
* **Outlier Detection:** Used statistical and visual methods (Boxplots and Scatter plots) to identify and handle anomalies in variables like `LotFrontage` and `GrLivArea`.
* **Regression Modeling:** Developed a regression model capable of explaining approximately **87% of the variance** in sale prices ($R^2 \approx 0.87$).
* **Performance Metrics:** Evaluated model accuracy using Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

### Technologies Used:
* **Python** (Pandas, NumPy)
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SwinSwinning/2020-HousingPricePrediction-v1/blob/main/Predict%20House%20Prices%20with%20regression%20v1.ipynb)
