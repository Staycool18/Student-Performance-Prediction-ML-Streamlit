# 🎓 Student Performance Prediction – ML Streamlit App

![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)
![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![License](https://img.shields.io/github/license/Staycool18/Student-Performance-Prediction-ML-Streamlit)
![ML Project](https://img.shields.io/badge/Machine%20Learning-Project-brightgreen)

A **Machine Learning web app** built using **Streamlit** that predicts student academic performance based on several key factors. This app helps educators, institutions, and stakeholders understand the influence of socioeconomic and academic variables on student success.

---

## 📌 Table of Contents

- [🔍 Overview](#-overview)
- [🧠 Features](#-features)
- [📊 Dataset Info](#-dataset-info)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 How to Run Locally](#-how-to-run-locally)
- [🧪 Model Training](#-model-training)
- [🌐 Deployment](#-deployment)
- [📸 Screenshots](#-screenshots)
- [🙌 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🔍 Overview

This ML-based project predicts a student's **final performance** using multiple features such as:

- Gender  
- Parental education level  
- Test preparation course  
- Lunch type  
- Previous scores (math, reading, writing)

The model predicts the student's final score/classification, helping in early intervention or support strategies.

---

## 🧠 Features

- 📈 **ML Model**: Trained using supervised learning techniques.
- 🧪 **EDA**: Exploratory Data Analysis for feature understanding and visualization.
- 🧮 **Model Evaluation**: Includes accuracy, confusion matrix, and classification report.
- 🌐 **Web App Interface**: Interactive and user-friendly UI using Streamlit.
- 📥 **User Input Form**: Dynamic input panel to test predictions.
- 📊 **Real-time Predictions**: Get immediate output with visualization support.

---

## 📊 Dataset Info

- Source: [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance) or [Kaggle Educational Datasets]
- Format: CSV
- Key columns:
  - `gender`, `race/ethnicity`, `parental level of education`
  - `lunch`, `test preparation course`
  - `math score`, `reading score`, `writing score`
- Target: Predicted performance level or average score

---

## 🛠️ Tech Stack

| Technology         | Description                     |
|--------------------|---------------------------------|
| Python 🐍          | Backend ML logic                |
| Pandas & NumPy     | Data handling & computation     |
| Matplotlib, Seaborn| Visualization and EDA           |
| Scikit-learn       | Model training and evaluation   |
| Streamlit ⚡        | Web app interface               |
| Git & GitHub       | Version control                 |

---

## 🚀 How to Run Locally

1. **Clone the repository**

```bash
git clone https://github.com/Staycool18/Student-Performance-Prediction-ML-Streamlit.git
cd Student-Performance-Prediction-ML-Streamlit
