# Car Price Prediction: Multiple Linear Regression 

##  Overview
This repository contains a Jupyter Notebook (`Assignment7.ipynb`) that builds a predictive machine learning model to estimate the offer price of a Toyota Corolla based on various vehicle attributes. The project covers the entire machine learning pipeline, from initial exploratory data analysis to the deployment of advanced regularization techniques.

##  Dataset Features
The model utilizes the following vehicle attributes to predict the target variable (`Price`):
* **Age:** Age of the vehicle in years
* **KM:** Accumulated Kilometers on the odometer
* **FuelType:** Fuel Type (Petrol, Diesel, CNG)
* **HP:** Horse Power
* **Automatic:** Transmission type (Yes=1, No=0)
* **CC:** Cylinder Volume in cubic centimeters
* **Doors:** Number of doors
* **Weight:** Weight in Kilograms
* **Quarterly_Tax:** Vehicle tax rate

##  Key Machine Learning Workflows

### 1. Exploratory Data Analysis (EDA) & Preprocessing
* Generated statistical summaries and visualizations to understand feature distributions.
* Pre-processed the data for modeling, including encoding categorical variables (like `FuelType`) and handling any data inconsistencies.

### 2. Model Building & Iteration
* Split the dataset into 80% training and 20% testing sets to ensure objective evaluation.
* Built **three distinct Multiple Linear Regression (MLR) models** iteratively, interpreting the coefficients to understand feature impact on the car's price.

### 3. Model Evaluation
* Evaluated model performance on the testing dataset using standard regression metrics to gauge predictive accuracy.

### 4. Advanced Regularization
* Applied **Lasso (L1)** and **Ridge (L2)** regression methods to handle potential multicollinearity, prevent overfitting, and improve model generalization.

##  Technical Interview Q&A
This notebook also includes detailed written answers to common data science interview questions regarding:
1. The definitions, differences, and utility of **Normalization vs. Standardization**.
2. Strategies and techniques used to identify and address **multicollinearity** in multiple linear regression models.

##  Technologies Used
* **Python 3**
* **Jupyter Notebook**
* **Libraries:** `pandas`, `numpy`, `scikit-learn` (for ML modeling and metrics), `matplotlib`, `seaborn`
