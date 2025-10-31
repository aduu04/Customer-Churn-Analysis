# 📊 Customer Churn Prediction Analysis

## Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on a telecom customer dataset to identify key factors driving **customer churn** (attrition). The goal is to understand which customer attributes and service features are most associated with a customer leaving the company, providing actionable insights for retention strategies.

---

## Key Findings on Churn Drivers
The analysis of the dataset revealed several significant patterns related to customer churn:

* **Overall Churn Rate:** The dataset shows a baseline churn rate of **26.54%**.
* **Contract Type:** Customers on a **Month-to-month** contract churn significantly more often than those with One-year or Two-year contracts.
* **Tenure:** Customers with **low tenure** (1-2 months) have the highest churn rate, indicating that early experience with the service is a critical point for retention. Conversely, long-term customers are very loyal.
* **Senior Status:** **Senior Citizens** show a higher rate of churn compared to non-senior customers.
* **Service Add-ons:** The presence of **Online Security** and **Tech Support** services strongly correlates with lower churn, suggesting these add-ons improve customer retention.
* **Internet Service:** Customers using **Fiber Optic** internet have a noticeably higher churn rate.
* **Payment Method:** The **Electronic Check** payment method is associated with the highest customer churn.

---

## Technical Skills & Libraries
* **Programming Language:** Python
* **Data Manipulation:** `pandas` (for loading, cleaning, and aggregating data)
* **Numerical Operations:** `numpy` (for handling numerical arrays)
* **Data Visualization:** `matplotlib` and `seaborn` (for creating informative plots, histograms, and bar charts)
* **Analysis:** Exploratory Data Analysis (EDA) focusing on churn distribution across categorical and numerical features.

---

## Data & Notebook
* **Dataset:** `Customer Churn.csv`
* **Notebook:** `TCA.ipynb` (Contains all cleaning, EDA, and visualization code.)
