#  House Price Prediction Using Machine Learning

##  About the Project

Estimating the value of a house is one of the most important challenges in the real estate industry. The price of a property depends on several factors such as area, number of bedrooms, bathrooms, parking facilities, furnishing status, and location-related features.

In this project, I developed a Machine Learning model that predicts house prices using property-related information. The project covers the complete data science workflow, including data exploration, preprocessing, visualization, model training, evaluation, and interpretation of results.

This project was completed as part of my Data Science Internship to gain practical experience in applying machine learning techniques to real-world business problems.

---

##  Project Objective

The main objective of this project is to:

- Predict house prices using machine learning algorithms.
- Identify the factors that have the greatest impact on property value.
- Compare different regression models and evaluate their performance.
- Generate insights that can help buyers, sellers, and real estate businesses make informed decisions.

---

##  Dataset Information

The dataset contains information about residential properties, including:

- Area
- Number of Bedrooms
- Number of Bathrooms
- Number of Stories
- Parking Availability
- Air Conditioning
- Basement Availability
- Guest Room Availability
- Furnishing Status
- Preferred Area
- House Price (Target Variable)

Dataset Source:

https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

---

##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

##  Project Workflow

### 1. Data Exploration

- Loaded the dataset using Pandas
- Explored data structure and feature information
- Checked for missing values
- Checked for duplicate records

### 2. Data Preprocessing

- Removed duplicate entries
- Converted categorical variables into numerical format
- Prepared the dataset for machine learning models

### 3. Model Development

Two regression models were implemented:

#### Linear Regression

A simple and interpretable regression model used as a baseline approach.

#### Random Forest Regressor

An ensemble learning algorithm capable of capturing complex relationships within the data.

---

##  Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

After evaluation, Linear Regression achieved slightly better performance on this dataset, indicating that the relationship between the available features and house prices is relatively linear.

---

##  Visualizations

The following visualizations were created to better understand the dataset and model performance:

- House Price Distribution Histogram
- Correlation Heatmap
- Actual vs Predicted Price Scatter Plot
- Feature Importance Analysis

---

##  Key Findings

Some of the most influential factors affecting house prices were:

- Property Area
- Number of Bathrooms
- Parking Availability
- Air Conditioning
- Preferred Area

The analysis showed that larger properties with better amenities generally have higher market values.

---

##  Business Insights

Based on the analysis, real estate businesses can improve pricing strategies by focusing on features that significantly influence property value. Properties with larger areas, additional bathrooms, parking spaces, and modern amenities tend to attract higher prices and greater buyer interest.

---

##  Future Improvements

Potential enhancements for this project include:

- Hyperparameter tuning for better model performance
- Testing advanced algorithms such as XGBoost
- Building an interactive web application using Streamlit
- Deploying the model for real-time predictions

---

##  Author

### Mandeep Kumar Roshan

B.Tech Computer Science and Engineering  
Lovely Professional University (LPU)

Aspiring Data Scientist | Machine Learning Enthusiast | Python Developer

---

⭐ If you found this project useful, feel free to star the repository.
