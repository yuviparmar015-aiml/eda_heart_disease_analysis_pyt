# ❤️ Heart Disease EDA Analysis

## 📌 Project Description

This project performs **Exploratory Data Analysis (EDA)** on a heart disease dataset to identify important factors that contribute to heart disease.

The analysis includes **data cleaning, visualization, and correlation analysis** to understand patterns between different health parameters.

---

## 🎯 Objective

* To analyze heart disease dataset
* To identify key features affecting heart disease
* To visualize patterns using graphs
* To gain insights for future machine learning models

---

## 📂 Dataset Information

* Source: UCI Machine Learning Repository / Kaggle
* Total Rows: 303
* Total Columns: 14

### Important Features:

* **age** → Age of the person
* **sex** → Gender (0 = Female, 1 = Male)
* **cp** → Chest pain type
* **trestbps** → Resting blood pressure
* **chol** → Cholesterol level
* **thalach** → Maximum heart rate achieved
* **exang** → Exercise-induced angina (0 = No, 1 = Yes)
* **oldpeak** → ST depression (important indicator)
* **target** → 0 = No disease, 1 = Disease

---

## 🛠️ Tools & Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## 📊 Steps Performed (EDA Process)

1. Data Loading
2. Data Inspection
3. Data Cleaning
4. Handling Missing Values
5. Outlier Detection using IQR
6. Univariate Analysis
7. Bivariate Analysis
8. Correlation Analysis
9. Data Visualization

---

## 📈 Key Insights

* Chest pain type (**cp**) has a strong relationship with heart disease
* Higher **oldpeak** values indicate higher chances of disease
* Most affected age group is **40–60 years**
* **Exercise-induced angina (exang)** is a strong indicator
* Maximum heart rate (**thalach**) is inversely related to disease risk

---

## 📸 Visualizations

Some important graphs used in this project:

* Count Plot (Chest Pain vs Disease)
* Age Group Analysis
* Correlation Heatmap
* Distribution Plots

*(You can add images in an `images/` folder and link them here)*

---

## 🚀 How to Run the Project

1. Clone this repository
2. Open the notebook in Google Colab / Jupyter Notebook
3. Run all the cells step by step

---

## 📌 Conclusion

EDA helped in identifying important health parameters that affect heart disease.
These insights can be useful for building predictive machine learning models in the future.

---

## 📁 Project Structure

```
├── eda_heart_disease_analysis.ipynb
├── heart.csv
├── README.md
└── images/
```

---

## 🙋 Author

**Yuvraj Parmar**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
