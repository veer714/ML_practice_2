# ❤️ Heart Disease Prediction - EDA & Decision Tree Classifier

## 📌 Project Overview
This project explores the **UCI Heart Disease Dataset** through **Exploratory Data Analysis (EDA)** and applies a **Decision Tree Classifier** to predict the presence of heart disease.  
The workflow combines data cleaning, visualization, and machine learning to uncover insights and build a baseline predictive model.

---

## 📂 Dataset
- **Source:** UCI Heart Disease Dataset
- **Features:** Age, sex, chest pain type, blood pressure, cholesterol, fasting blood sugar, ECG results, max heart rate, exercise-induced angina, ST depression, slope, number of major vessels, thalassemia.
- **Target Variable:** Presence (1) or absence (0) of heart disease.

---

## 🔍 Workflow
1. **Data Cleaning**
   - Handle missing values
   - Encode categorical variables
   - Normalize/standardize numerical features

2. **Exploratory Data Analysis (EDA)**
   - Univariate analysis (distributions, counts)
   - Bivariate/multivariate analysis (correlation heatmaps, pairplots)
   - Feature importance visualization

3. **Decision Tree Classifier**
   - Train/test split
   - Model training using scikit-learn
   - Hyperparameter tuning (max depth, min samples split)
   - Performance evaluation (accuracy, precision, recall, F1-score)

4. **Visualization**
   - Histograms, boxplots, violin plots
   - Correlation heatmaps
   - Decision Tree visualization

---

## ⚙️ Tools & Libraries
- **Python**
- **Pandas, NumPy** – data handling
- **Matplotlib, Seaborn** – visualization
- **Scikit-learn** – Decision Tree, preprocessing, evaluation

---

## 📊 Key Insights
- Features like **chest pain type, max heart rate, ST depression** strongly influence predictions.
- The **Decision Tree Classifier** provides interpretable rules for classification.
- Model performance highlights potential for improvement with ensemble methods (Random Forest, Gradient Boosting).

---

## 🚀 Next Steps
- Compare Decision Tree with other classifiers (Logistic Regression, Random Forest, SVM).
- Apply cross-validation for robust performance metrics.
- Optimize preprocessing and feature engineering for better accuracy.
