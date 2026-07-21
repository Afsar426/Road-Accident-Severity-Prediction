
# 🚦 Road Accident Severity Prediction

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-purple?style=for-the-badge&logo=pandas">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

## 📌 Project Overview

Road accidents are one of the leading causes of injuries and fatalities worldwide. This project uses **Machine Learning** to predict the severity of road accidents based on driver, vehicle, road, weather, and environmental conditions.

The model classifies accidents into three categories:

- 🚗 Slight Injury
- 🚑 Serious Injury
- ⚠️ Fatal Injury

The goal is to assist traffic authorities, emergency responders, and city planners in making faster and better-informed decisions.

---

# 🎯 Project Objectives

- Predict accident severity using Machine Learning.
- Perform Exploratory Data Analysis (EDA).
- Clean and preprocess real-world accident data.
- Train and compare multiple classification models.
- Evaluate model performance using different metrics.
- Identify the most important factors affecting accident severity.

---

# 📂 Dataset

- **Dataset:** Road Traffic Accident Dataset
- **Records:** 12,316
- **Features:** 32
- **Target Variable:** `Accident_severity`

Target Classes:

- Slight Injury
- Serious Injury
- Fatal Injury

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 🔄 Machine Learning Workflow

### 1️⃣ Data Collection

- Loaded dataset from CSV

### 2️⃣ Exploratory Data Analysis

- Dataset overview
- Missing value analysis
- Target distribution
- Feature inspection

### 3️⃣ Data Preprocessing

- Missing value handling
- Feature engineering
- Label Encoding
- Feature selection

### 4️⃣ Data Splitting

- Training Dataset
- Testing Dataset

### 5️⃣ Model Training

Three classification models were trained:

- Logistic Regression
- Decision Tree
- Random Forest

### 6️⃣ Model Evaluation

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix

### 7️⃣ Feature Importance

Random Forest was used to identify the most influential features affecting accident severity.

---

# 📊 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **49.30%** |
| Decision Tree | **77.56%** |
| ⭐ Random Forest | **84.70%** |

### 🏆 Best Model

**Random Forest**

Accuracy:

> **84.70%**

---

# 📈 Visualizations

The project includes:

- Accident Severity Distribution
- Missing Value Analysis
- Model Accuracy Comparison
- Confusion Matrix
- Feature Importance Graph

---

# 📁 Project Structure

```
Road-Accident-Severity-Prediction
│
├── Road Traffic Accident.ipynb
├── RTA Dataset.csv
├── README.md
└── images/
```

---

# 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/Afsar426/Road-Accident-Severity-Prediction.git
```

Move into the project folder

```bash
cd Road-Accident-Severity-Prediction
```

Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run

```bash
jupyter notebook
```

Open

```
Road Traffic Accident.ipynb
```

---

# 📌 Results

- Successfully predicted road accident severity.
- Random Forest achieved the highest performance.
- Built a complete Machine Learning pipeline from preprocessing to prediction.

---

# 🔮 Future Improvements

- Hyperparameter tuning
- XGBoost implementation
- SMOTE for class balancing
- Real-time accident prediction
- Streamlit web application deployment

---

# 👨‍💻 Author

## Afsar Azam

B.Tech Artificial Intelligence

SAGE University, Indore

GitHub

https://github.com/Afsar426

LinkedIn

(Add your LinkedIn URL here)

---

# ⭐ Repository Support

If you found this project useful, consider giving it a ⭐ on GitHub.
