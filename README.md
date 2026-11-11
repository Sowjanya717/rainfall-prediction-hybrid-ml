
# 🌧️ Rainfall Prediction Using Hybrid Machine Learning Models

## 📌 Project Overview

This project focuses on predicting rainfall using Machine Learning and Deep Learning techniques.

It explores a hybrid stacking approach that combines a Gated Recurrent Unit (GRU) model and an XGBoost model, with Linear Regression as a meta-learner.

The project was completed as part of my MSc Artificial Intelligence and Data Science dissertation at Edinburgh Napier University.

## 🎯 Project Objectives

- Analyse historical rainfall and weather data.
- Perform data cleaning and preprocessing.
- Explore rainfall patterns across different seasons, months and geographical regions.
- Develop a hybrid GRU and XGBoost stacking model.
- Compare the proposed model with traditional Machine Learning models.
- Evaluate model performance using regression metrics.

## 📊 Dataset

The project uses the Indian Rainfall and Weather Prediction Dataset.

- Observations: 970,339
- Weather stations: 458
- Data period: 2015–2025
- Target variable: Rainfall

Dataset source:
https://www.kaggle.com/datasets/ameydilipmorye/indian-rainfall-and-weather-data

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- XGBoost
- Matplotlib
- Seaborn
- Google Colab

## ⚙️ Methodology

The project follows these main steps:

1. Dataset loading and inspection.
2. Data cleaning and preprocessing.
3. Exploratory Data Analysis (EDA).
4. Feature engineering.
5. Chronological dataset splitting.
6. Training baseline Machine Learning models.
7. Developing the GRU model.
8. Implementing the hybrid stacking architecture.
9. Model evaluation and comparison.

## 🤖 Models Implemented

The following models were developed and evaluated:

- Linear Regression
- Support Vector Regression (SVR)
- Random Forest Regression
- XGBoost Regression
- Proposed Hybrid Stacking Model (GRU + XGBoost + Linear Regression)

## 📈 Model Performance

The dissertation reported the following results for the proposed stacking model:

| Evaluation Metric | Result |
|---|---:|
| MAE | 1.668 |
| MSE | 6.394 |
| RMSE | 2.529 |
| R² Score | 0.572 |

The proposed stacking model achieved the lowest MAE, MSE and RMSE, and the highest R² score among the five models compared.

Random Forest achieved a slightly better sMAPE than the proposed stacking model.

## 🔍 Key Learning Outcomes

Through this project, I gained experience in:

- Working with a large weather dataset.
- Data preprocessing and exploratory data analysis.
- Feature engineering.
- Machine Learning model development.
- Deep Learning using TensorFlow and Keras.
- Model evaluation and performance comparison.
- Hybrid ensemble learning.

## ⚠️ Limitations

The GRU input in this implementation used one timestep rather than a multi-day sliding window. The project also focused on historical structured weather data and did not include real-time forecasting or deployment.

## 🚀 Future Improvements

- Implement multi-day sliding-window sequences.
- Explore additional Machine Learning and Deep Learning architectures.
- Improve model generalisation.
- Develop a real-time rainfall prediction application.

## 👩‍💻 Author

**Sowjanya Vasireddy**

MSc Artificial Intelligence and Data Science Graduate  
Edinburgh Napier University

Interested in Artificial Intelligence, Data Science and Data Analytics.
