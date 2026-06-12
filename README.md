# Medical Insurance Cost Analysis and Prediction System

## Project Overview

The Medical Insurance Cost Analysis and Prediction System is a Machine Learning project that analyzes customer insurance data and predicts medical insurance charges. The project uses Exploratory Data Analysis (EDA), Linear Regression, Multiple Linear Regression, and Logistic Regression to understand factors affecting insurance costs and classify customers based on risk levels.

The system helps insurance companies estimate premiums more accurately, identify high-risk customers, and support data-driven decision-making.

---

## Problem Statement

Health insurance companies collect large volumes of customer information such as age, gender, BMI, number of children, smoking habits, region, and medical insurance charges.

Manual analysis of this data is difficult and may lead to inaccurate premium estimation and poor risk assessment.

This project aims to automate insurance cost analysis and prediction using machine learning techniques.

---

## Objectives

* Analyze customer demographic and insurance data.
* Perform data cleaning and preprocessing.
* Conduct Exploratory Data Analysis (EDA).
* Identify factors influencing insurance charges.
* Build Linear Regression models for charge prediction.
* Build Logistic Regression models for customer classification.
* Categorize customers into cost-based risk groups.
* Create an interactive dashboard for visualization and reporting.

---

## Dataset Information

### Dataset Source

Kaggle

### Dataset Name

Medical Cost Personal Dataset

### Dataset Link

https://www.kaggle.com/datasets/mirichoi0218/insurance

---

## Dataset Features

| Feature  | Description                  |
| -------- | ---------------------------- |
| age      | Age of customer              |
| sex      | Gender of customer           |
| bmi      | Body Mass Index              |
| children | Number of dependent children |
| smoker   | Smoking status               |
| region   | Residential region           |
| charges  | Medical insurance charges    |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-Learn
* Streamlit

---

## Project Workflow

### 1. Data Collection

* Load dataset from Kaggle
* Explore dataset structure
* Understand feature types

### 2. Data Cleaning & Preprocessing

* Check missing values
* Remove duplicate records
* Verify data types
* Encode categorical variables

### 3. Exploratory Data Analysis (EDA)

* Analyze customer demographics
* Study insurance charge distribution
* Compare smoker and non-smoker costs
* Identify influential variables

### 4. Data Visualization

* Bar Charts
* Histograms
* Scatter Plots
* Box Plots
* Pie Charts
* Correlation Heatmaps

### 5. Risk Analysis

Customers are categorized into:

#### Low Cost Customers

* Insurance charges below threshold

#### Medium Cost Customers

* Moderate insurance charges

#### High Cost Customers

* High insurance charges
* Higher medical expense risk

### 6. Simple Linear Regression

Objective:
Predict insurance charges using age.

Independent Variable:

* age

Dependent Variable:

* charges

### 7. Multiple Linear Regression

Objective:
Predict insurance charges using multiple customer attributes.

Independent Variables:

* age
* bmi
* children
* smoker

Dependent Variable:

* charges

### 8. Logistic Regression

Objective:
Classify customers into:

* Low Cost Customer (0)
* High Cost Customer (1)

Target Variable:

* insurance_category

---

## Model Evaluation Metrics

### Linear Regression & Multiple Linear Regression

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

### Logistic Regression

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

---

## Dashboard Features

Interactive dashboard includes:

* Insurance Charges Distribution
* Age vs Charges Analysis
* BMI vs Charges Analysis
* Smoker vs Non-Smoker Comparison
* Region-wise Charges Analysis
* Gender-wise Charges Analysis
* Correlation Heatmap
* High Cost vs Low Cost Customer Distribution

### Interactive Filters

* Age Filter
* Gender Filter
* Region Filter
* Smoker Filter
* Number of Children Filter

---

## Installation

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn streamlit
```

---

## Running the Project

### Run Prediction System

```bash
python medical_insurance_prediction.py
```

### Run Dashboard

```bash
streamlit run app.py
```

---

## Expected Outcomes

* Accurate insurance charge prediction
* Better premium estimation
* Identification of high-risk customers
* Improved policy planning
* Enhanced risk assessment
* Data-driven insurance decision making

---

## Key Insights

* Smoking significantly impacts insurance costs.
* Age and BMI influence premium amounts.
* Multiple Linear Regression generally performs better than Simple Linear Regression.
* Logistic Regression helps classify customers into risk categories.
* Insurance companies can use these insights for premium optimization.

---

## Future Enhancements

* Random Forest Regression
* XGBoost Regression
* Advanced Risk Scoring
* Real-Time Insurance Prediction
* Cloud Deployment
* Mobile Dashboard Application

---
Visualization

<img width="472" height="312" alt="image" src="https://github.com/user-attachments/assets/9d266c19-279b-4988-a5b1-33f4989ca392" />
<img width="460" height="318" alt="image" src="https://github.com/user-attachments/assets/070c2102-dd32-4ae6-bdb0-128576e60cbf" />
<img width="518" height="301" alt="image" src="https://github.com/user-attachments/assets/c7aa4ce2-b726-4bc3-9acb-07d957408a81" />
<img width="526" height="355" alt="image" src="https://github.com/user-attachments/assets/38106077-a2e1-4944-9927-1cede548418d" />

## Conclusion

The Medical Insurance Cost Analysis and Prediction System demonstrates how Machine Learning can be applied in the insurance industry to predict medical charges and identify high-risk customers. By combining EDA, Regression Models, Logistic Regression, and Dashboard Visualization, the project provides valuable insights that support accurate premium estimation and strategic business decisions.
