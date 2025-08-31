# Week-1
This is my github repository for my first AICTE internship. I am creating a ML model on water potability through which we can detect whether the water is safe or not based on its chemical properties

**Project Overview**
This project is part of my AICTE Internship. The goal is to analyze and predict whether water is safe (potable) or unsafe (not potable) for human consumption, based on various water quality parameters.

The dataset used is Water Potability Dataset
, which contains measurements like pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic Carbon, Trihalomethanes, and Turbidity.

**Steps Completed So Far**
**1. Exploratory Data Analysis (EDA)**
Checked dataset shape, columns, and data types.

Identified missing values in some features (e.g., ph, Sulfate, Trihalomethanes).

Plotted correlation heatmap to study relationships between variables.

Checked class imbalance in target variable (Potability).

**2. Data Preprocessing**
Missing Values: Handled using mean imputation.

Feature Scaling: Applied StandardScaler to normalize values.

Imbalance Handling: Used SMOTE to balance classes

