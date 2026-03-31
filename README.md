# Heart Disease Prediction - Exploratory Data Analysis (EDA)
📌 Project Overview
This project focuses on Exploratory Data Analysis (EDA) of a heart disease dataset to uncover patterns, correlations, and insights that can aid in building predictive machine learning models. The goal is to understand the dataset thoroughly before applying ML algorithms for classification.

📂 Dataset
Source: UCI Heart Disease Dataset (commonly used in ML research)

Features: Includes patient attributes such as age, sex, chest pain type, resting blood pressure, cholesterol levels, fasting blood sugar, ECG results, maximum heart rate, exercise-induced angina, ST depression, slope, number of major vessels, and thalassemia.

Target Variable: Presence or absence of heart disease.

🔍 EDA Workflow
Data Cleaning

Handling missing values

Encoding categorical variables

Normalization/standardization of numerical features

Univariate Analysis

Distribution plots for age, cholesterol, blood pressure

Frequency counts for categorical features

Bivariate & Multivariate Analysis

Correlation heatmaps

Pairplots to visualize feature interactions

Grouped statistics by target variable

Feature Engineering

Creating derived features (e.g., age groups, risk categories)

Checking feature importance

Visualization

Histograms, boxplots, violin plots

Heatmaps for correlation

Bar charts for categorical distributions

⚙️ Tools & Libraries
Python

Pandas – data manipulation

NumPy – numerical operations

Matplotlib & Seaborn – visualization

Scikit-learn – preprocessing utilities

📊 Key Insights
Certain features (e.g., chest pain type, maximum heart rate, ST depression) show strong correlation with heart disease.

Lifestyle-related factors like cholesterol and exercise-induced angina are significant predictors.

Feature scaling improves interpretability for ML models.

🚀 Next Steps
Apply classification models (Logistic Regression, Random Forest, XGBoost).

Evaluate performance using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

Optimize models with hyperparameter tuning.

📎 How to Run
bash
# Clone the repository
git clone https://github.com/veer714/ML_practice_2.git

# Navigate to project folder
cd ML_practice_2

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Heart_Disease_EDA.ipynb
🧑‍💻 Author
Veer  
Passionate about data science, ML, and building practical solutions with clear documentation.
