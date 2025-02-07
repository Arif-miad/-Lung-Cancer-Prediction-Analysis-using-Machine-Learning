# 🩺 Lung Cancer Prediction & Analysis using Machine Learning

## 📌 Project Overview
Lung cancer is one of the deadliest diseases globally, and early detection is crucial for improving survival rates. This project involves **advanced Exploratory Data Analysis (EDA)** and **machine learning classification models** to analyze lung cancer cases, risk factors, smoking trends, and healthcare accessibility across **25 of the world's most populated countries**.

## 📊 Dataset Details
- **Total Records:** 220,632 individuals
- **Features:** 21 columns
- **Key Variables:**
  - `Age`, `Gender`, `Smoker`, `Years_of_Smoking`, `Family_History`
  - `Lung_Cancer_Diagnosis`, `Air_Pollution_Exposure`, `Occupational_Exposure`
  - `Healthcare_Access`, `Annual_Lung_Cancer_Deaths`, `Lung_Cancer_Prevalence_Rate`
- **Target Variable:** `Lung_Cancer_Diagnosis` (Binary Classification: Yes/No)

## 🔍 Exploratory Data Analysis (EDA)
We performed **50+ visualizations**, including:

### 📌 **Univariate Analysis**
- **Histogram & KDE:** Distribution of numerical features
- **Box Plot & Violin Plot:** Outlier detection & spread
- **Count Plot & Bar Chart:** Categorical feature analysis

### 📌 **Bivariate Analysis**
- **Scatter Plot & Pair Plot:** Relationship between numerical features
- **Heatmap & Correlation Matrix:** Feature correlations

### 📌 **Geospatial Analysis**
- **World Map Visualization**: Shows lung cancer cases by country

## 🤖 Machine Learning Models
We implemented **Top 10 Classification Models** for prediction:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Gradient Boosting (XGBoost, CatBoost, LightGBM)
5. Support Vector Machine (SVM)
6. k-Nearest Neighbors (KNN)
7. Naive Bayes
8. Multi-layer Perceptron (MLP Neural Network)
9. AdaBoost Classifier
10. Stacking Classifier

## 📏 Model Evaluation
We used multiple metrics for model evaluation:
- **Accuracy, Precision, Recall, F1-score**
- **Confusion Matrix** (Heatmap)
- **AUC-ROC Curve** (Performance visualization)
- **Feature Importance Plot** (For tree-based models)

## 📂 Project Structure
```
📦 Lung_Cancer_Analysis
├── 📄 README.md  # Project documentation
├── 📂 dataset  # Dataset files (CSV)
├── 📂 notebooks  # Jupyter Notebooks for analysis
├── 📂 models  # Trained ML models
└── 📂 visualizations  # Saved plots & charts
```

## 🚀 Results & Insights
- **Key Risk Factors Identified**: Smoking, Air Pollution, Family History
- **Random Forest & XGBoost** provided the highest accuracy (~95%)
- **Healthcare Access** plays a crucial role in survival rates
- **Countries with high pollution levels** show increased lung cancer prevalence

## 🔗 Links
- 📌 **Kaggle Notebook**: [View Full Notebook](www.linkedin.com/in/arif-miah-8751bb217)
- 🔗 **LinkedIn Profile**: [Connect with me](https://www.linkedin.com/in/arifmia)

## 💡 Future Scope
- Improving deep learning models for enhanced prediction accuracy
- Analyzing genetic & environmental factors in greater detail
- Building a web app for lung cancer risk assessment

---

### 📢 Feel free to ⭐ this repository if you find it useful! 🚀

