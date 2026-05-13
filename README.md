# Healthcare Mining & Burnout Prediction System

## Overview

This project focuses on analyzing mental health and burnout data in the tech industry using Data Mining and Machine Learning techniques. The notebook includes data preprocessing, exploratory data analysis (EDA), feature engineering, clustering, fuzzy logic, and feature selection using a Genetic Algorithm.

The main goal of the project is to discover patterns related to employee burnout and build an intelligent healthcare mining system that can support analysis and decision-making.

---

# Project Objectives

* Analyze mental health and burnout factors in the tech industry.
* Clean and preprocess healthcare-related data.
* Perform Exploratory Data Analysis (EDA).
* Apply feature selection using a Genetic Algorithm.
* Implement clustering techniques to group similar cases.
* Use fuzzy logic concepts for intelligent analysis.
* Evaluate and visualize the results.

---

# Dataset

The project uses the dataset:

`mental_health_burnout_tech_2026.csv`

The dataset contains information related to employee mental health, burnout indicators, and workplace factors.

---

# Technologies & Libraries Used

## Programming Language

* Python

## Libraries

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* scipy
* sklearn-extra

---

# Project Workflow

## 1. Import Libraries

The project starts by importing all required libraries for data analysis, visualization, preprocessing, clustering, and machine learning.

## 2. Load Dataset

The dataset is loaded using pandas and prepared for analysis.

## 3. Exploratory Data Analysis (EDA)

Several visualization techniques were used to understand the dataset:

* Histogram plots
* Box plots
* Count plots
* Scatter plots
* Correlation matrix

EDA helps identify:

* Data distribution
* Relationships between variables
* Outliers
* Missing values

---

# Data Preprocessing

The preprocessing stage includes:

* Handling missing values
* Detecting outliers using the IQR method
* Encoding categorical variables
* Preparing features for clustering and analysis

---

# Feature Selection Using Genetic Algorithm

Instead of using PCA, the project applies a Genetic Algorithm for feature selection.

The Genetic Algorithm helps:

* Reduce irrelevant features
* Improve model efficiency
* Select the most important variables

The notebook also compares:

* Best selected features
* Baseline feature set

---

# Clustering Techniques

## K-Medoids Clustering

K-Medoids clustering is used to group similar records while being more robust to outliers.

## Hierarchical Clustering

Hierarchical clustering is applied to visualize relationships between clusters and identify hidden structures in the dataset.

Cluster visualizations are included in the notebook.

---

# Fuzzy Logic

The project also includes fuzzy logic concepts to support intelligent healthcare analysis and decision-making.

---

# System Implementation

The notebook demonstrates the complete implementation workflow, from preprocessing to final analysis and testing.

---

# Results

The project successfully:

* Processed and analyzed healthcare burnout data
* Identified important features using Genetic Algorithms
* Applied clustering methods for pattern discovery
* Visualized insights and relationships in the dataset
* Demonstrated intelligent healthcare mining concepts

---

# File Structure

```bash
├── healthcare_mining_final.ipynb
├── mental_health_burnout_tech_2026.csv
└── README.md
```

---

# How to Run the Project

## 1. Clone the Repository

```bash
git clone https://github.com/iouhyt6e54as/data_mining.git
```

## 2. Open the Project Folder

```bash
cd data_mining
```

## 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy sklearn-extra
```

## 4. Run the Notebook

Open Jupyter Notebook and run:

```bash
jupyter notebook
```

Then open:

`healthcare_mining_final.ipynb`

---

# Future Improvements

* Build a web application for prediction and visualization.
* Apply additional machine learning models.
* Improve clustering evaluation metrics.
* Deploy the project online.

---

# Author

Developed as part of a Data Mining / Healthcare Analytics project.

---

# License

This project is for educational and academic purposes.
