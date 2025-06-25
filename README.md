# Task2_Exploratory-Data-Analysis-EDA

## Overview
This repository contains a comprehensive Exploratory Data Analysis (EDA) of the Titanic dataset, performed as part of an AI/ML internship task. The analysis focuses on uncovering patterns, relationships, and insights through statistical methods and data visualization.

## Objectives
- Perform initial data assessment and cleaning.
- Generate descriptive statistics and identify data distributions.
- Visualize relationships between variables.
- Draw meaningful inferences about passenger survival patterns.

## Tools & Technologies
- **Python** (Primary programming language)
- **Libraries**:
  - Pandas (Data manipulation)
  - Matplotlib & Seaborn (Static visualizations)
  - Plotly (Interactive visualizations)
- **Environment**: Google Colab

## Dataset
- **Source**: [Titanic Dataset from Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **File**: `titanic.csv`
- **Key Features**:
  - Passenger demographics (Age, Sex).
  - Travel details (Pclass, Fare, Embarked).
  - Survival status (Target variable).

## Analysis Highlights

### 1. Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) is the process of examining a dataset to understand its structure, main characteristics, and underlying patterns — before building any models or making predictions.

### 2. Data Assessment & Cleaning
- Initial data inspection with `head()` and `info()`.
- Handling missing values:
  - Age: Filled with mean values
  - Embarked: Filled with mode values

### 3. Statistical Analysis
- Calculated central tendencies (mean, median).
- Measured dispersion (standard deviation).
- Generated correlation matrix.

### 4. Key Visualizations
- **Distribution Plots**:
  - Age distribution with histogram.
  - Survival comparison with boxplots.
- **Relationship Analysis**:
  - Correlation heatmap.
  - Pairplot for multivariate relationships.
- **Interactive Visualization**:
  - Scatter plot of Age vs Fare colored by Survival (Plotly).

## Key Findings
1. **Age Distribution**:
   - Majority of passengers were between 20-40 years old.
   - Younger passengers had slightly higher survival rates.

2. **Class Impact**:
   - Strong negative correlation between Pclass and Survival.
   - Higher fares (associated with upper classes) correlated with better survival chances.

3. **Gender Patterns**:
   - Women and children had higher survival rates (visible in interactive plots).


## Learning Outcomes
- Gained proficiency in Python-based EDA workflows.
- Developed skills in statistical data analysis.
- Learned to derive business insights from visualizations.
- Enhanced ability to communicate data findings effectively.
