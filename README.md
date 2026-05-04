# Rainfall Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on predicting whether it will rain the next day in Sydney using historical weather data from 2008 to 2017. The objective is to build and evaluate multiple Machine Learning classification models capable of forecasting rainfall based on meteorological observations such as temperature, humidity, pressure, cloud cover, and rainfall levels.

The project demonstrates a complete end-to-end Machine Learning workflow including data preprocessing, exploratory data analysis, model training, evaluation, and prediction.

---

# 📂 Dataset Information

Dataset File: `sydney_rain prediction.xlsx`

The dataset contains weather observations with the following features:

| Feature | Description |
|---|---|
| Date | Observation date |
| Location | Weather station location |
| MinTemp | Minimum temperature (°C) |
| MaxTemp | Maximum temperature (°C) |
| Rainfall | Rainfall amount (mm) |
| Evaporation | Evaporation level (mm) |
| Sunshine | Bright sunshine hours |
| Humidity9am | Humidity at 9 AM (%) |
| Humidity3pm | Humidity at 3 PM (%) |
| Pressure9am | Atmospheric pressure at 9 AM |
| Pressure3pm | Atmospheric pressure at 3 PM |
| Cloud9am | Cloud cover at 9 AM |
| Cloud3pm | Cloud cover at 3 PM |
| Temp9am | Temperature at 9 AM |
| Temp3pm | Temperature at 3 PM |
| RainToday | Rain occurrence today (0/1) |
| RainTomorrow | Target variable (0/1) |

---

# 🎯 Problem Statement

The goal of this project is to develop a Machine Learning model that predicts rainfall for the next day (`RainTomorrow`) using historical weather observations.

Accurate rainfall prediction is valuable for:
- Agriculture planning
- Disaster management
- Transportation safety
- Water resource management
- Daily weather forecasting

---

# ⚙️ Approach

The project follows these major steps:

1. Data Collection
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Prediction & Comparison

---

# 🤖 Machine Learning Models Used

The following classification algorithms were implemented and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naïve Bayes

---

# 🛠️ Tech Stack

## Programming Language
- Python

## Libraries & Frameworks
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- OpenPyXL
- Jupyter Notebook

---

# 📊 Model Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Best Performing Model
Random Forest Classifier achieved the best performance with approximately:

| Metric | Score |
|---|---|
| Accuracy | 85–90% |
| Precision | 0.87 |
| Recall | 0.84 |
| F1-Score | 0.85 |

---

# 📈 Key Insights

- Humidity and cloud cover were highly influential in rainfall prediction.
- Atmospheric pressure showed a strong relationship with rainfall occurrence.
- Ensemble learning methods performed better than traditional classifiers.
- Data preprocessing significantly improved model accuracy.

---

# 🚀 Future Improvements

Possible future enhancements include:

- Implementing XGBoost or LightGBM
- Hyperparameter tuning
- Real-time weather API integration
- Deep learning models (LSTM)
- Web application deployment using Flask or Streamlit
- Multi-city rainfall forecasting

---

# ▶️ How to Run the Project

## Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/rainfall-prediction-ml.git
cd rainfall-prediction-ml
