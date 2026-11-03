# Titanic Dataset Preparation & Exploratory Data Analysis

**A Data Preprocessing and Exploratory Data Analysis Project using Python**

## Overview

This project demonstrates an end-to-end data preparation workflow using the Titanic dataset. It focuses on understanding raw data, identifying data quality issues, handling missing values, performing exploratory analysis, and preparing features for machine learning applications.

The project uses Python-based data analysis and visualization libraries to transform raw data into a cleaner and more structured format.

## Project Objectives

- Inspect and understand the dataset structure.
- Identify missing values and duplicate records.
- Apply appropriate data cleaning techniques.
- Explore data distributions and relationships through visualizations.
- Transform categorical variables into numerical representations.
- Apply feature scaling using StandardScaler.
- Export the prepared dataset for further analysis.

## Technology Stack

| Category | Tools |
|---|---|
| Programming Language | Python |
| Data Manipulation | Pandas |
| Data Visualization | Matplotlib, Seaborn |
| Feature Scaling | Scikit-learn |
| Development Environment | Google Colab / Jupyter Notebook |

## Dataset

- **Name:** Titanic Dataset
- **Source:** [Seaborn Titanic Dataset](https://github.com/mwaskom/seaborn-data/blob/master/titanic.csv)
- **Domain:** Passenger survival analysis
- **Target-related column:** `survived`

## Workflow

### 1. Data Loading & Inspection
- Imported the dataset using Pandas.
- Examined initial records and dataset structure.
- Inspected columns and data types.

### 2. Data Cleaning & Preprocessing
- Identified missing values.
- Imputed missing `age` values using the median.
- Imputed missing `embarked` values using the mode.
- Removed the `deck` column.
- Removed duplicate records.

### 3. Exploratory Data Analysis
Created visualizations to explore:
- Passenger age distribution.
- Passenger survival across different classes.

### 4. Feature Transformation
- Applied one-hot encoding to categorical features such as `sex` and `embarked`.
- Applied standardization using `StandardScaler` to selected numerical features.

### 5. Data Export
- Prepared the cleaned and transformed dataset.
- Exported the processed data into CSV format for future use.

## Key Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Missing Value Treatment
- Categorical Feature Encoding
- Numerical Feature Scaling
- Data Visualization
- Python Data Analysis

## Repository Structure

```text
Titanic-Dataset-Preparation-EDA/
│
├── Titanic_Dataset_Preparation_EDA.ipynb
├── README.md
└── Titanic_Prepared_Dataset.csv
```

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Sandy7999/Titanic-Dataset-Preparation-EDA.git
```

Install dependencies:

```bash
pip install pandas matplotlib seaborn scikit-learn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and execute the cells sequentially.

## Project Outcome

The project demonstrates a structured data preprocessing pipeline, from raw dataset inspection to cleaning, visualization, feature transformation, and data export. These foundational techniques are essential for preparing reliable datasets for subsequent machine learning workflows.

## Author

**Sandesh Kondikire**

B.Tech – Artificial Intelligence & Data Science

- GitHub: [Sandy7999](https://github.com/Sandy7999)
- LinkedIn: [Sandesh Kondikire](https://www.linkedin.com/in/sandesh-kondikire/)
