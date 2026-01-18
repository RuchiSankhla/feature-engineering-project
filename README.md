#Feature Engineering Project — Employee Attrition Prediction

#Project Overview
This project focuses on performing **Feature Engineering** on the **Employee Attrition Prediction Dataset** obtained from Kaggle.  
The goal of this project is to clean, preprocess, and transform raw HR data into a structured format suitable for predictive modeling.  
All the tasks were carried out using **Python** in **Jupyter Notebook**.

---

#Objectives
- To handle missing, duplicate, and noisy data.  
- To detect and treat outliers.  
- To encode categorical variables for machine learning compatibility.  
- To scale and normalize numerical features.  
- To create and select meaningful features for better model performance.

---

#Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

#Steps Performed

#Data Cleaning  
- Removed irrelevant columns such as *Employee_ID*.  
- Handled missing values using mean, median, and mode imputation.  
- Treated noisy data (e.g., unrealistic values like age > 100).  
- Removed duplicate records.

#Data Encoding  
- Converted categorical columns using **Label Encoding** and **One-Hot Encoding**.

#Feature Scaling  
- Applied **StandardScaler** and **MinMaxScaler** for normalization and standardization.

#Feature Transformation  
- Created new derived features (like total working years, experience level, etc.).  
- Applied **binning** for continuous variables (e.g., salary categories → Low, Medium, High).

#Feature Selection  
- Used **Correlation Matrix** and **Feature Importance** to identify relevant features.

---

#Results
After applying feature engineering techniques:
- The dataset became clean, consistent, and ready for model training.  
- Outliers were reduced, and scaling improved uniformity across features.  
- The transformed dataset is now suitable for classification models such as Logistic Regression, KNN, and Decision Tree.

---

#Files Description
| File Name | Description |
|------------|-------------|
| `feature_engineering.ipynb` | Main Jupyter notebook containing the complete analysis |
| `README.md` | Overview of the entire project |
| `data/` | Folder containing dataset |

---

Author
Ruchi Sankhla   
Feature Engineering and Data Preprocessing using Python.

---

🔗 Dataset Source
Kaggle:[Employee Attrition Prediction Dataset](https://www.kaggle.com)  





