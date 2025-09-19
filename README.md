# 🏦 Loan Approval Prediction  

This project tackles the **binary classification** problem of predicting whether a loan application will be **Approved or Rejected**.  
The analysis explores **EDA, data preprocessing, class imbalance handling, and multiple ML models** including **Decision Tree, Random Forest, Logistic Regression, and XGBoost**, followed by evaluation and comparison.  

---

### 📌 Project Overview  

- **Data Preprocessing**: Encoded categorical variables (Graduate/Not Graduate, Yes/No, Approved/Rejected), handled missing values, and split the dataset into training and test sets.  
- **Exploratory Data Analysis (EDA)**: Generated correlation heatmaps and boxplots to understand variable relationships.  
- **Class Imbalance Handling**: Applied **SMOTE** (Synthetic Minority Oversampling Technique) to balance target classes.  
- **Models Trained**: Logistic Regression, Decision Tree, Random Forest, and XGBoost.  
- **Evaluation**: Used accuracy, precision, recall, F1-score, and ROC-AUC to measure performance.  

---

### 🛠️ Tech Stack  

- **Python**  
- **Pandas, NumPy** → Data manipulation and preprocessing  
- **Matplotlib, Seaborn** → Data visualization  
- **Scikit-learn** → Model training, evaluation, and hyperparameter tuning  
- **Imbalanced-learn (SMOTE)** → Oversampling for imbalanced classes  
- **XGBoost** → Gradient boosting classifier  

---

### 📂 Dataset  

The dataset contains demographic and financial details of applicants, including:  

- Applicant’s **education level** (Graduate / Not Graduate)  
- **Self-employed status** (Yes / No)  
- **Loan status** (Approved / Rejected – target variable)  
- Other numerical and categorical features affecting loan approval.  

---

### 📊 Data & Model Analysis  

- Cleaned categorical inconsistencies (e.g., leading/trailing spaces).  
- Applied **correlation heatmaps** and **boxplots** to visualize relationships.  
- Balanced the target variable using **SMOTE**.  
- Trained multiple ML models to compare performance.  

---

### 🤖 Models Implemented  

- **Logistic Regression** → Simple linear classifier for baseline performance  
- **Decision Tree** → Interpretable tree-based classifier  
- **Random Forest** → Ensemble bagging model for robust predictions  
- **XGBoost** → Gradient boosting model optimized for performance  

---

### 📈 Model Evaluation & Insights  

- **Accuracy, Precision, Recall, and F1-score** reported for all models.  
- Random Forest and XGBoost generally showed the **best trade-off between recall and precision**.  

---

### 📷 Visualizations  

- Correlation heatmap of features  
- Boxplots of key variables  
