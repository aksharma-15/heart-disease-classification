# heart-disease-classification
An end-to-end data science project on heart disease classification using machine learning

# ❤️ Heart Disease Classification: End-to-End Machine Learning Project

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24-lightgrey.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

> **Developed by Abhay Kumar Sharma** | *Former Data Analyst Intern & Top Performer at Elevate Labs* 
> A comprehensive machine learning workflow demonstrating exploratory data analysis, feature engineering, model training, and performance evaluation to predict the presence of heart disease in patients.

---

## 📌 Project Overview
This repository contains a complete, end-to-end data science and machine learning project. The objective is to build a robust predictive model capable of diagnosing heart disease based on clinical parameters. The project serves as a showcase of structured problem-solving, clean coding practices, and advanced model evaluation techniques.

## 🎯 Problem Statement
> *Given clinical parameters about a patient, can we accurately predict whether or not they have heart disease?*

The proof-of-concept goal for this project is to strive toward a **95% accuracy** threshold in predicting heart disease, determining the viability of deploying such models in real-world clinical settings.

## 📊 The Dataset
The data is originally sourced from the well-known **Cleveland dataset** via the UCI Machine Learning Repository and Kaggle. It includes 303 patient records and 14 clinical attributes.

### Key Features
1. **age**: Age in years 
2. **sex**: 1 = male; 0 = female 
3. **cp**: Chest pain type (4 values ranging from typical angina to asymptomatic)
4. **trestbps**: Resting blood pressure (in mm Hg)
5. **chol**: Serum cholesterol in mg/dl
6. **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
7. **restecg**: Resting electrocardiographic results
8. **thalach**: Maximum heart rate achieved
9. **exang**: Exercise induced angina (1 = yes; 0 = no)
10. **oldpeak**: ST depression induced by exercise relative to rest
11. **slope**: The slope of the peak exercise ST segment
12. **ca**: Number of major vessels (0-3) colored by fluoroscopy
13. **thal**: Thallium stress result (1,3 = normal; 6 = fixed defect; 7 = reversible defect)
14. **target**: 1 = Heart Disease present, 0 = No Heart Disease 

## 🛠️ Tech Stack & Tools
The following Python-based libraries were utilized to build this pipeline:
* **Data Manipulation & Analysis:** `Pandas`, `NumPy`
* **Data Visualization:** `Matplotlib`, `Seaborn`
* **Machine Learning:** `Scikit-Learn`

## ⚙️ Workflow & Methodology
1. **Problem Definition:** Outlining the clinical problem and success criteria.
2. **Data Ingestion:** Loading the `heart-disease.csv` dataset.
3. **Exploratory Data Analysis (EDA):** Becoming a subject matter expert on the data by analyzing distributions, handling missing values, finding outliers, and mapping correlations between variables (e.g., Heart disease frequency vs. Sex).
4. **Data Preprocessing:** Splitting data into training and test sets (`train_test_split`).
5. **Modeling:** Training and comparing multiple classification algorithms.
6. **Hyperparameter Tuning:** Using `RandomizedSearchCV` and `GridSearchCV` to squeeze out maximum performance.
7. **Evaluation:** Analyzing models beyond pure accuracy using `confusion_matrix`, `classification_report`, `precision_score`, `recall_score`, `f1_score`, and `RocCurveDisplay`.

## 🧠 Machine Learning Models
To find the best predictive engine, we experimented with three distinct algorithms:
1. **Logistic Regression** (Often serves as a strong baseline for binary classification)
2. **K-Nearest Neighbors (KNN)**
3. **Random Forest Classifier** (An ensemble method for robust pattern recognition)

## 🚀 How to Run the Project
1. **Clone the repository:**
```bash
   git clone [https://github.com/aksharma-15/heart-disease-classification.git](https://github.com/aksharma-15/heart-disease-classification.git)
```
2. **Install dependencies**
   ```pip install -r requirements.txt```

3. **Launch notebook**
   ```jupyter notebook heart_disease_classification.ipynb```


Connect with me on LinkedIn - [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhay-kumar-sharma-a22a94171)
