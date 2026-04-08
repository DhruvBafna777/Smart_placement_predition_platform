# 🎓 Smart Placement Prediction System

An end-to-end Machine Learning web application that predicts the likelihood of a student getting placed based on their academic metrics and soft skills. 

## 📌 Project Overview
This project features a comprehensive pipeline, from Data Exploratory Analysis (EDA) and model training to deploying a fully functional interactive web interface. It evaluates multiple factors including CGPA, coding skills, internships, and communication skills to provide a realistic placement prediction, making it a valuable tool for students to assess their employability.

## 🚀 Features
* **Interactive Web Interface:** Built with Streamlit for a seamless, user-friendly experience.
* **Comprehensive Feature Analysis:** Evaluates 10+ distinct data points, including branch, backlogs, aptitude scores, and soft skills.
* **End-to-End ML Pipeline:** Includes a detailed Jupyter Notebook (`placement-prediction.ipynb`) documenting data processing, model selection, and training.
* **Real-time Predictions:** Instantly outputs results based on the serialized pre-trained model.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Processing & ML:** Pandas, Scikit-Learn, Joblib
* **Frontend UI:** Streamlit
* **Development Environment:** Jupyter Notebook

## 📂 Project Structure
```text
├── app.py                           # Main Streamlit web application script
├── placement-prediction.ipynb       # Jupyter Notebook for EDA and model training
├── placement_prediction_model.pkl   # Serialized ML model (generated via notebook)
└── README.md                        # Project documentation
|__ requirements.txt
