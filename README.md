# 🩺 Disease Diagnosis Prediction

## 📌 Objective

To build a machine learning model that can predict the likelihood of diseases such as **diabetes** or **heart disease** based on patient medical data, enabling early detection and prevention.

---

## 📊 Dataset

- **PIMA Indians Diabetes Dataset**  
  Source: [Kaggle - PIMA Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

---

## 🔁 Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Distribution of key medical features
- Correlation between features and diagnosis
- Outlier detection and class balance

### 2. Data Preprocessing
- Handling missing values
- Scaling numerical features (StandardScaler)
- Encoding categorical features (if any)

### 3. Feature Selection
- Correlation matrix
- Tree-based feature importance

### 4. Model Training
Models used:
- Gradient Boosting (LightGBM / XGBoost)
- Support Vector Machine (SVM)
- Multi-Layer Perceptron (Neural Network)

### 5. Model Evaluation
Metrics used:
- Accuracy
- Precision, Recall, F1-Score
- AUC-ROC Curve

---

## 📈 Outcome

A medical prediction system that:
- Helps healthcare professionals identify high-risk individuals
- Offers explainable and actionable predictions
- Can be integrated into preventive healthcare workflows

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- scikit-learn
- LightGBM / XGBoost
- imbalanced-learn (SMOTE)
- Streamlit (optional for UI)

---

## 📎 How to Run

1. Clone this repository  
   ```bash
   git clone https://github.com/Taha-Saleem-43/Disease-Diagnose-prediction.git
   cd Disease-Diagnosis-prediction
