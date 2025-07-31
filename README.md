# 🌧️ Rainfall Prediction using Machine Learning

Predicting whether it will rain tomorrow based on historical weather data using various preprocessing techniques and a classification model.

---

## 📊 Dataset

- **Source**: [Kaggle - Weather Dataset (Rattle Package)](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)
- **Total Rows**: ~29,000
- **Features**: Multiple weather parameters such as Temperature, Rainfall, Humidity, WindSpeed, etc.

---

## ✅ Problem Statement

The objective is to predict whether it will **rain tomorrow** (`RainTomorrow`) based on today's weather conditions.

---

## 🔍 Preprocessing Steps

- **Label Encoding** for binary categorical features like `RainToday`.
- **One-Hot Encoding** for multi-category features like `Location`, `WindDir`, etc.
- **Missing Value Handling** by dropping or imputing depending on feature significance.
- **Feature Scaling** using **RobustScaler** to handle outliers effectively.
- **Train-Test Split** with 80% training and 20% testing.

---

## 🤖 Model Overview

- **Model Type**: Binary Classification
- **Final Accuracy**: `0.8557`

### 📈 Classification Report:

| Metric | Class 0 (No Rain) | Class 1 (Rain) |
|--------|------------------|----------------|
| Precision | 0.89 | 0.71 |
| Recall    | 0.93 | 0.58 |
| F1-Score  | 0.91 | 0.64 |

- **Overall Accuracy**: `85.57%`
- **Macro Avg F1**: `0.78`
- **Weighted Avg F1**: `0.85`

### 🧮 Confusion Matrix

|               | Predicted No | Predicted Yes |
|---------------|--------------|----------------|
| **Actual No** | 21,157       | 1,515          |
| **Actual Yes**| 2,682        | 3,738          |

---

## 🧠 Technologies Used

- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **Matplotlib, Seaborn** (for visualization)
- **Jupyter Notebook**

---

## 📌 Key Learnings

- Importance of encoding and scaling in preprocessing.
- Dealing with imbalanced datasets (notice Class 1 performance).
- Interpreting classification metrics beyond just accuracy.

---


---

## 🚀 Future Improvements

- Use **SMOTE** or **Class Weights** to balance the dataset.
- Try **Ensemble Models** (RandomForest, XGBoost).
- Add **Feature Engineering** and **Hyperparameter Tuning**.
- Deploy the model using **Flask** or **Streamlit** for real-time predictions.

---

# 🙋‍♂️ Author
Brijesh Rakhasiya
AI/ML Enthusiast | Data Scientist | Problem Solver


## 📄 License

This project is licensed under the MIT License.

---
**Made ❤️ by Brijesh Rakhasiya**e.



