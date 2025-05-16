# 🫀 Heart Failure Prediction
[![Python](https://img.shields.io/badge/Python-3.7+-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?logo=streamlit&logoColor=white)](https://heart-vs.streamlit.app/)
[![Docker](https://img.shields.io/badge/Docker-Available-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)
[![XGBoost](https://img.shields.io/badge/XGBoost-Model-026F00?logo=xgboost&logoColor=white)](https://xgboost.readthedocs.io/)
[![Flask](https://img.shields.io/badge/Flask-API-000000?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)

> **Live Demo**: [Streamlit Cloud App](https://heart-vs.streamlit.app/) | **Repository**:

## 📊 Project Overview

Cardiovascular diseases remain the **#1 cause of death globally**, claiming an estimated 17.9 million lives each year. Early detection and management are critical for people at high risk.

This machine learning system predicts heart disease risk based on clinical parameters, helping healthcare professionals identify at-risk patients earlier and potentially save lives through timely intervention.

## ✨ Key Features

- **High-accuracy prediction**: XGBoost classifier with fine-tuned parameters
- **Multiple deployment options**: Web application, API, and containerized solution
- **Interactive interface**: User-friendly Streamlit dashboard for instant predictions
- **RESTful API**: Flask backend for seamless integration with other systems
- **Docker support**: Ready for deployment in any environment
- **Cloud-deployed**: Accessible anywhere via Streamlit Cloud

## 📈 Dataset & Analysis

The model is trained on the [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/) from Kaggle, containing key cardiovascular health indicators:

- Demographic details (age, sex)
- Clinical parameters (blood pressure, cholesterol levels)
- Symptoms (chest pain type, exercise-induced angina)
- Test results (resting ECG, max heart rate, ST depression)

Our extensive [exploratory data analysis](https://github.com/Romilagarwal/heart-failure-prediction/blob/main/notebook/part_1_preprocessing.ipynb) reveals critical patterns between these variables and heart disease risk.

## 🧠 Model Development

The project evaluates multiple classification algorithms:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

After rigorous comparison using confusion matrices and AUC scoring, **XGBoost** emerged as the top performer. 


## ⚠️ Disclaimer

This tool is designed for **screening purposes only** and should not replace professional medical advice. Always consult healthcare providers for proper diagnosis.

## 🤝 Contributing

Contributions to improve the model accuracy, user interface, or add new features are welcome. Please feel free to submit a pull request.


<p align="center">
  <i>Building healthier futures through machine learning and predictive analytics.</i>
</p>

