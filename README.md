# ❤️ Heart Disease Prediction — Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple)

---

## 📌 Project Overview

This project performs a **comprehensive Exploratory Data Analysis (EDA)** on a heart disease dataset to identify **key medical and demographic factors** contributing to heart disease.

The focus is on:

* Understanding feature distributions
* Identifying strong predictors
* Extracting **data-driven insights**
* Supporting future machine learning models

---

## 🎯 Objectives

* Analyze patient health data to detect patterns
* Identify high-risk groups based on features
* Understand relationships between variables
* Generate insights for early detection of heart disease

---

## 📂 Dataset Information

The dataset includes the following key features:

| Feature  | Description                     |
| -------- | ------------------------------- |
| age      | Age of patient                  |
| sex      | Gender (0 = Female, 1 = Male)   |
| cp       | Chest pain type                 |
| trestbps | Resting blood pressure          |
| chol     | Cholesterol level               |
| thalach  | Maximum heart rate              |
| exang    | Exercise-induced angina         |
| oldpeak  | ST depression                   |
| target   | Heart disease (1 = Yes, 0 = No) |

---

## 🧹 Data Preprocessing

* Removed duplicate entries
* Checked missing values
* Standardized column formats
* Verified categorical encoding

### 💡 Insight:

Clean and consistent data ensures reliable and accurate analysis.

---

## 🔄 Feature Engineering

The target variable was transformed for better interpretation:

```python
df["target"] = 1 - df["target"]
```

### 💡 Insight:

Consistent labeling improves clarity in analysis and visualization.

---

## 📊 Exploratory Data Analysis

---

## 👨‍⚕️ 1. Gender-Based Analysis

### 📊 Results:

* **Females (0)** → ~75% disease rate
* **Males (1)** → ~45% disease rate

### 🔍 Interpretation:

Females show a significantly higher proportion of heart disease cases in this dataset.

### ⚠️ Note:

This is dataset-specific and should not be generalized.

---

## ❤️ 2. Chest Pain Type Analysis

### 📊 Results:

| Chest Pain Type | Disease Probability |
| --------------- | ------------------- |
| 0               | ~27%                |
| 1               | ~82%                |
| 2               | ~79%                |
| 3               | ~69%                |

### 🔥 Key Insight:

* **Chest pain types 1 and 2 are the strongest indicators**
* Type 0 shows minimal risk

---

## 🏃 3. Exercise-Induced Angina

### 📊 Results:

* exang = 1 → High disease probability (~70%+)
* exang = 0 → Lower disease probability

### 💡 Insight:

Heart stress during exercise strongly correlates with disease presence.

---

## 📉 4. ST Depression (Oldpeak)

### 📊 Results:

* Higher values correspond to higher disease probability

### 💡 Insight:

Oldpeak is one of the most **clinically significant indicators** in this dataset.

---

## 💓 5. Maximum Heart Rate (Thalach)

### 📊 Results:

* Lower heart rate → Higher disease risk
* Higher heart rate → Lower disease risk

### 💡 Insight:

Indicates inverse relationship with heart disease.

---

## 🎂 6. Age Group Analysis

### 📊 Results:

| Age Group | Disease % |
| --------- | --------- |
| 20–30     | ~100%     |
| 30–40     | ~64%      |
| 40–50     | ~67%      |
| 50–60     | ~46%      |
| 60–70     | ~37%      |
| 70–80     | ~85%      |

### ⚠️ Important:

* Younger group may have fewer samples → possible bias

### 💡 Insight:

Risk generally increases with age, especially in older groups.

---

## 🔥 Correlation Analysis

* Strong indicators:

  * Chest pain (cp)
  * Oldpeak
  * Thalach (inverse)
  * Exang

* Weak indicators:

  * Cholesterol
  * Resting BP

### 💡 Insight:

Not all medically important features show strong statistical correlation.

---

## 🔗 Multivariate Insights

Heart disease is influenced by a **combination of factors** rather than a single feature.

### Example High-Risk Profile:

* High oldpeak
* Low thalach
* exang = 1

👉 Indicates strong probability of heart disease

---

## 🧠 Key Findings

1. Chest pain type 1 & 2 → ~80% disease probability
2. Females show higher disease percentage (~75%)
3. Exercise-induced angina significantly increases risk
4. Higher oldpeak strongly correlates with disease
5. Lower max heart rate indicates higher risk
6. Age plays a critical role in disease patterns

---

## ⚖️ Advantages & Limitations

### ✅ Advantages:

* Identifies high-risk factors
* Improves understanding of medical data
* Supports predictive modeling

### ❌ Limitations:

* Dataset-specific patterns
* Correlation ≠ causation
* Possible sampling bias

---

## 🎯 Conclusion

This analysis demonstrates that heart disease is a **multi-factor problem** influenced by:

* Chest pain type
* Heart stress indicators (oldpeak, exang)
* Heart performance (thalach)
* Demographic features (age, gender)

### 💡 Final Insight:

**Chest pain type and oldpeak emerge as the most powerful predictors in this dataset.**

---

## 🚀 Future Work

* Apply Machine Learning models
* Perform feature selection
* Build prediction system
* Develop dashboard visualization

---

## 📸 Sample Visualizations

(Add your saved graphs here)

* Heatmap
* Chest pain vs disease
* Age group analysis
* Gender analysis

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 👤 Author

**Yuvraj Parmar**

---

## ⭐ Final Note

> “EDA helps uncover patterns, but not causation. Proper validation is required before making real-world decisions.”
