# EDA-and-Preprocessing-ML-Assignment
# Data Preprocessing and Analysis Assignment

This repository contains the steps and processes implemented for data preprocessing, exploration, analysis, encoding, and feature scaling. Below is an outline of the tasks completed and their descriptions.

---

## Dataset Overview
The sample dataset consists of six features:

- **Company**: Name of the company (categorical).  
- **Age**: Age of individuals (numerical).  
- **Salary**: Salary of individuals (numerical).  
- **Place**: Location of individuals (categorical).  
- **Country**: Country of residence (categorical).  
- **Gender**: Gender of individuals (binary categorical: 0 for male, 1 for female).  

---

## Steps Performed  

### 1. **Data Exploration**
- Identified and listed unique values for each feature along with their lengths.
- Conducted statistical analysis to summarize the dataset.
- Renamed columns for consistency and readability.

### 2. **Data Cleaning**
- Located and treated missing values:
  - Replaced the value `0` in the `Age` column with `NaN`.
  - Addressed missing values in all columns by applying techniques like replacement with the mean/median/mode.
- Removed duplicate rows to ensure data integrity.
- Identified and handled outliers for numerical columns.

### 3. **Data Analysis**
- Filtered data where:
  - `Age > 40`
  - `Salary < 5000`
- Created visualizations:
  - Scatter plot for `Age` vs. `Salary`.
  - Count plot representing the number of people from each `Place`.

### 4. **Data Encoding**
- Converted categorical variables into numerical representations:
  - Used **One-Hot Encoding** for multi-category columns.
  - Applied **Label Encoding** for binary categorical columns.

### 5. **Feature Scaling**
- Scaled numerical features to standardize the dataset:
  - Applied **StandardScaler** to normalize the data distribution.
  - Applied **MinMaxScaler** for feature scaling to a range between 0 and 1.

---

## Outcomes
This project demonstrates the following:
1. Efficient preprocessing and cleaning of a dataset to prepare it for analysis.
2. Use of various encoding techniques for categorical data.
3. Application of feature scaling to optimize data for machine learning algorithms.
4. Visual representation and interpretation of insights derived from the dataset.

---

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Usage
Clone this repository and explore the code for detailed implementation of the steps. All tasks are modularized and documented for better understanding.
