# Xylofy-AI-week-1-Project-
Housing Prices Prediction

## Project Overview
This project involves building a machine learning regression model to predict real estate prices based on various property features (such as area, number of bedrooms, bathrooms, etc.). The goal is to analyze a real-world dataset to determine which factors most strongly influence a property's market value.

## Dataset
The data used for this project is the **Housing Prices Dataset** sourced from Kaggle. It contains several numerical and categorical features related to house properties and their sale prices. 

* **Source:** [Housing Prices Dataset (Kaggle)](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)

## Tools & Libraries Used
* **Python 3.x**
* **Pandas** - Data manipulation and cleaning
* **Scikit-Learn** - Machine learning model building and evaluation
* **Matplotlib & Seaborn** - Data visualization

## Methodology
1. **Data Cleaning:** Handled missing values and converted categorical text variables into numeric format using one-hot encoding.
2. **Exploratory Data Analysis (EDA):** Generated histograms and correlation heatmaps to visualize feature relationships.
3. **Model Training:** Split the data into an 80/20 train-test set.
4. **Evaluation:** Trained and compared two models:
   * Linear Regression
   * Random Forest Regressor
   
## Key Findings
* The **Total Area** and **Number of Bathrooms** are the strongest predictors of house price in this dataset.
* The Random Forest Regressor outperformed the standard Linear Regression model, capturing roughly 60-70% of the variance in prices.
* Secondary amenities (like guest rooms or main road location) have less impact on price than fundamental size metrics.

## Author
**Dakshesh Verma** *(Completed for AI Week 1 Project)*
