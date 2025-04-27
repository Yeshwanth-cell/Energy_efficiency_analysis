# 🏡 Energy Efficiency Analysis

## 📌 Overview
This project analyzes the energy efficiency of 12 different building shapes simulated using **Ecotect**, applying statistical and machine learning techniques.  
The primary goal is to predict the **cooling load** based on key building parameters and improve building energy performance.

---

## 📊 Dataset
The dataset consists of eight independent features influencing energy efficiency:

- **Relative Compactness** (Continuous)
- **Surface Area** (Continuous)
- **Wall Area** (Continuous)
- **Roof Area** (Continuous)
- **Overall Height** (Continuous)
- **Orientation** (Categorical)
- **Glazing Area** (Continuous)
- **Glazing Area Distribution** (Categorical)

**Target Variable:**
- **Cooling Load** (Continuous)

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was conducted using **R Studio** and included:

- Scatterplot Matrices to explore feature relationships
- Histograms to analyze feature distributions
- Correlation Analysis to identify strong predictors

---

## 📈 Statistical & Regression Analysis
Key steps taken:

- **Descriptive Statistics**: Summarized key variables
- **Correlation Analysis**: Identified strong positive/negative relationships
- **Linear Regression**: Achieved **88.7% accuracy** in predicting cooling load
- **Variance Inflation Factor (VIF) Analysis**: Assessed multicollinearity

---

## 🤖 Machine Learning Models
Several machine learning models were implemented to improve prediction accuracy:

- Perceptrons (Initial accuracy: 58%)
- Support Vector Machines (SVM)
- Neural Networks
- K-Nearest Neighbors (KNN)
- Naïve Bayes Classifier
- Decision Trees & Random Forest
- Boosting Algorithms

---

## 🔥 Key Findings
- ✅ **Relative Compactness** is a strong predictor of cooling load.
- ✅ **Surface Area** and **Roof Area** significantly affect energy efficiency.
- ✅ **Random Forest** and **Boosting** models achieved the best prediction results.

---

## 🚀 Technologies Used
- **Python**: Data preprocessing, machine learning modeling
- **R Studio**: Exploratory and statistical analysis
- **Ecotect**: Building shape simulation
- **Machine Learning Libraries**: Scikit-learn, TensorFlow

---

## 📂 Project Structure
```plaintext
├── data/              # Raw and processed data
├── eda/               # R scripts for Exploratory Data Analysis
├── models/            # Python scripts for Machine Learning models
├── reports/           # Findings, visualizations, and reports
├── README.md          # Project Overview
