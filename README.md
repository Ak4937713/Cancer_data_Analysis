# Cancer_data_Analysis
This repository contains information related to Cancer data Analysis. 
## 📌 Objective

To understand key characteristics of tumor samples and identify which features are most associated with **malignant Tumor diagnoses**. This includes visual analysis, statistical summary, and insight generation.

## 📊 Dataset Overview

- 📁 Source: https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset
- 🔢 Features: 30 numeric predictors (e.g., mean radius, texture, concavity)
- 🎯 Target: `diagnosis` (Malignant = 0, Benign = 1)

# Question
- What patterns in the data are associated with malignant tumors?

# 🧪 Cancer Dataset EDA & Dashboard Workflow

## 📥 1. Data Collection
- [x] Choose a dataset
- [x] Download from a trusted source
- [x] Understand dataset context

## 🧹 2. Data Cleaning
- [x] Check for missing values
- [x] Handle nulls
- [x] Convert categorical variables
- [x] Check for duplicates

## 📊 3. Exploratory Data Analysis (EDA)
- [x] Summary stats
- [x] Class distribution
- [x] Correlation heatmap
- [x] removal of columns with the help of heatmap
- [x] Skeweness detection and removal of outliers

## 📈 4. Visualization & Insights
- [x] Key plots
- [x] Trend highlights
- [x] Pattern recognition

## 📊 5. Dashboard Creation
- [x] Choose visualization tool
- [x] Import data
- [x] Add visuals & filters

## 📤 6. Sharing & Export
- [x] Save dashboard
- [x] Export visuals
- [x] Write summary insights
- [x] Upload to GitHub + share

## 🔍 Key Insights from EDA
- Malignant tumors generally have higher values for radius, area, and concavity-related features.
- Outliers in the dataset are mostly valid and stem from extreme cancer cases.
- Log transformation reduces skewness and brings features closer to a normal distribution.
- Features like `radius_mean`, `concavity_mean`, and `symmetry_mean` are strong indicators of malignancy.
- Visualizations (donut chart, stacked column chart) show clear separation between benign and malignant classes.

