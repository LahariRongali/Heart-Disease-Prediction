🫀 Heart Disease Prediction Using Machine Learning

This project predicts the likelihood of heart disease in patients using clinical data and multiple machine learning algorithms. It demonstrates a complete ML workflow—from data preprocessing to model evaluation—focused on healthcare analytics.

## 📌 Problem Statement

Heart disease is one of the leading causes of death globally. Early detection through machine learning can help clinicians make informed decisions and improve patient outcomes. This project uses patient health metrics to classify whether an individual is at risk of heart disease.

## 📊 Dataset Overview

The dataset contains 14 clinical features:

| Feature      | Description                                      |
|--------------|--------------------------------------------------|
| `age`        | Age of the patient                               |
| `sex`        | Sex (1 = male; 0 = female)                       |
| `cp`         | Chest pain type (0–3 categorical values)         |
| `trestbps`   | Resting blood pressure (mm Hg)                   |
| `chol`       | Serum cholesterol (mg/dl)                        |
| `fbs`        | Fasting blood sugar > 120 mg/dl (1 = true)       |
| `restecg`    | Resting ECG results (0–2 categorical values)     |
| `thalach`    | Maximum heart rate achieved                      |
| `exang`      | Exercise-induced angina (1 = yes)                |
| `oldpeak`    | ST depression induced by exercise                |
| `slope`      | Slope of peak exercise ST segment (0–2 values)   |
| `ca`         | Number of major vessels (0–3)                    |
| `thal`       | Thalassemia (1 = normal; 2 = fixed; 3 = reversible) |
| `target`     | Diagnosis (1 = heart disease; 0 = no heart disease) |

## 🧠 ML Workflow

- **Preprocessing**:
  - Handled missing values
  - Encoded categorical features
  - Scaled numerical features
- **Algorithms Used**:
  - Logistic Regression
  - Naive Bayes
  - Support Vector Machine
  - K-Nearest Neighbors
  - Decision Tree
  - XGBoost
  - Neural Network (MLP)
- **Evaluation Metrics**:
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC-AUC Curve

## 🏆 Model Performance

| Algorithm              | Accuracy (%) |
|------------------------|--------------|
| Logistic Regression    | 85.25        |
| Naive Bayes            | 85.25        |
| Support Vector Machine | 81.97        |
| K-Nearest Neighbors    | 67.21        |
| Decision Tree          | 81.97        |
| XGBoost                | 83.61        |
| Neural Network         | 81.97        |

> ✅ Best performing models: **Logistic Regression** and **Naive Bayes**, both achieving **85.25% accuracy**

## 📁 Repository Structure
Heart-Disease-Prediction/ │ ├── Heart_Disease_Prediction.ipynb # Main notebook with code and results ├── Heart_Disease_Prediction.html # HTML export of the notebook ├── README.md # Project documentation

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn

