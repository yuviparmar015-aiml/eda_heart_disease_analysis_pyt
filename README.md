# ❤️ Heart Disease EDA Analysis

## 📌 Project Overview

This project presents a comprehensive **Exploratory Data Analysis (EDA)** of a heart disease dataset to identify key factors influencing the presence of heart disease.

The analysis involves **data preprocessing, statistical exploration, and visualizations** to uncover meaningful patterns and relationships among clinical features.

---

## 🎯 Objectives

* Analyze the heart disease dataset using EDA techniques
* Identify significant features influencing heart disease
* Visualize relationships between variables
* Generate insights to support future predictive modeling

---

## 📂 Dataset Details

* **Source:** UCI Machine Learning Repository / Kaggle
* **Number of Records:** 303
* **Number of Features:** 14

### Key Features:

* **age** → Age of the individual
* **sex** → Gender (0 = Female, 1 = Male)
* **cp** → Chest pain type
* **trestbps** → Resting blood pressure
* **chol** → Serum cholesterol level
* **thalach** → Maximum heart rate achieved
* **exang** → Exercise-induced angina (0 = No, 1 = Yes)
* **oldpeak** → ST depression induced by exercise
* **target** → Presence of heart disease (0 = No, 1 = Yes)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## 📊 Methodology

The following steps were performed during the analysis:

1. Data Loading and Inspection
2. Data Cleaning and Preprocessing
3. Handling Missing Values
4. Outlier Detection using IQR method
5. Univariate Analysis
6. Bivariate Analysis
7. Correlation Analysis
8. Data Visualization

---

## 📈 Key Findings

* Chest pain type (**cp**) shows a strong correlation with heart disease
* Higher values of **oldpeak** are associated with increased risk
* Individuals aged **40–60 years** show higher incidence
* **Exercise-induced angina (exang)** is a significant indicator
* **Maximum heart rate (thalach)** is inversely related to disease risk

---

## 📊 Visualizations

The analysis includes the following visualizations:

* Count plots (Chest Pain vs Target)
* Age-based analysis
* Correlation heatmap
* Distribution plots

> Note: Visual outputs can be found in the `images/` directory.

---

## 🚀 Getting Started

### Steps to Run:

1. Clone this repository
2. Open the notebook in Google Colab or Jupyter Notebook
3. Execute all cells sequentially

---

## 📌 Conclusion

The EDA process highlights key clinical features that influence heart disease.
These insights can serve as a foundation for building accurate machine learning models for prediction.

---

## 📁 Project Structure

```
├── eda_heart_disease_analysis.ipynb
├── heart.csv
├── README.md
└── images/
```

---

## 👤 Author

**Yuvraj Parmar**

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
