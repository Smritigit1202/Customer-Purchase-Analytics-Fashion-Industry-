# Customer Purchase Analysis

## Overview
This project analyzes customer purchase behavior using a retail sales dataset. It includes data preprocessing, exploratory data analysis (EDA), customer segmentation via RFM analysis, and predictive modeling to determine purchase likelihood. The goal is to extract insights and improve customer engagement strategies.

## Features Implemented
### 1️⃣ Data Preprocessing
- Handles **missing values**
- Removes **duplicates**
- Converts **data types** to appropriate formats

### 2️⃣ Exploratory Data Analysis (EDA)
- **Gender Distribution** visualization
- **Orders by Age Group** analysis
- **Top-Selling Products** identification
- **Monthly Revenue Trends** tracking

### 3️⃣ Customer Segmentation (RFM Analysis)
- **Recency:** Days since last purchase
- **Frequency:** Number of purchases
- **Monetary Value:** Total amount spent
- Identifies **high-value customers**

### 4️⃣ Predicting Purchase Likelihood (Machine Learning)
- Defines **target variable** (High-value customer or not)
- Uses **Logistic Regression Model**
- Performs **feature scaling**
- Splits data into **training and testing sets**
- Evaluates using **accuracy score, confusion matrix, and classification report**

### 5️⃣ Saving Processed Data
- **Cleaned dataset** (`processed_sales_data.csv`)
- **RFM analysis results** (`rfm_analysis.csv`)

## Requirements
Install the necessary dependencies using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run
1. Open the Jupyter Notebook (`customer_analysis.ipynb`).
2. Run all cells sequentially to preprocess data, analyze trends, segment customers, and train the model.
3. Review the generated insights and model predictions.

## Next Steps
- Improve feature engineering for better segmentation.
- Experiment with advanced machine learning models (e.g., Random Forest, XGBoost).
- Enhance visualization insights, such as regional sales trends.

## Author
**Smriti Aggarwal**
