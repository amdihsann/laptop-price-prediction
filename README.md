# Laptop Price Prediction using Machine Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/117OSDT3jXGNNcLkTdxI6bcrm4uBNHQbk?usp=sharing)

A data-driven project to predict laptop prices based on their technical specifications. This model aims to help consumers, especially students, make informed purchasing decisions.

---

## Project Overview

Choosing a laptop can be overwhelming due to the vast number of options and complex specifications. This project addresses this challenge by developing a machine learning model that provides a reliable price estimate based on a laptop's features. By analyzing a dataset of over 1300 laptops, we built a regression model that demystifies laptop pricing.

The project covers the complete data science workflow:
* **Data Cleaning & Preprocessing:** Handling outliers and preparing the dataset for modeling.
* **Exploratory Data Analysis (EDA):** Visualizing the data to uncover key insights and correlations between features and price.
* **Feature Engineering:** Creating new features to improve the model's predictive power.
* **Modeling & Evaluation:** Building, comparing, and evaluating several regression models to select the best performer.

## Key Stakeholders
This solution provides value to several key groups:
* **Students & Consumers:** As end-users, they get a reliable tool to estimate prices and make smarter, more confident purchasing decisions.
* **Retailers & Businesses:** Companies can use the model's insights for competitive pricing, product segmentation, and better inventory management.
* **Data Analysts & Developers:** The project serves as a practical case study on building a complete regression model, from data cleaning to evaluation.

## Key Insights
Our analysis reveals that core specifications such as RAM, CPU speed, and storage size are the primary drivers of a laptop's price. Specialized types like Workstation and Gaming laptops consistently command the highest prices, a fact attributed to their premium components like powerful GPUs and high-resolution displays.

Interestingly, the brand's influence on price is less significant than that of the core hardware, suggesting a market where consumers prioritize performance and value over brand loyalty. The most competitive price point was found to be concentrated in the €700–€800 range.

## Model Performance

After comparing several algorithms (Linear Regression, Decision Tree, and Random Forest), the **Random Forest Regressor** was selected as the final model for its superior performance and stability.

* **Final Result:** The model achieved an **R-squared (R²) score of 0.90**. This indicates that the model can explain 90% of the price variance based on the provided features.

##  Tech Stack

* **Python**
* **Pandas** for data manipulation and analysis.
* **NumPy** for numerical operations.
* **Scikit-learn** for machine learning modeling and evaluation.
* **Matplotlib** & **Seaborn** for data visualization.
* **Google Colab** as the development environment.







