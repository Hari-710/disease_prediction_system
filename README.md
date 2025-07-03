# 🩺 Disease Prediction System

This project is a machine learning-based web application that predicts the likelihood of **Heart Disease** and **Diabetes**.  
It uses trained models and a clean **Streamlit** interface to make predictions based on user inputs.

---

## 🚀 Features

- 🔍 Heart Disease Prediction
- 🔬 Diabetes Prediction
- 🧠 Trained ML models using **Google Colab**
- 🌐 Frontend built with **Streamlit**
- 📦 Uses `.pkl` model files for prediction
- ⚡ Fast, interactive, and lightweight UI

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Google Colab (for model training)
- Spyder (for Streamlit development)


## 📁 Folder Structure

disease-prediction-system/
│
├── models/
│   ├── heart_model.pkl
│   └── diabetes_model.pkl
│
├── streamlit_app/
│   └── app.py
│
├── notebooks/
│   ├── heart_logistic_regression.py
│   └── diabetics.py
│
├── data/
│   └── sample_data.csv (optional)
│
├── requirements.txt
├── README.md
└── .gitignore


## How to Run Locally

### Clone the Repository

git clone https://github.com/Hari-710/disease-prediction-system.git
cd disease-prediction-system

### Install Dependencies
pip install -r requirements.txt

### Command to run streamlit App
streamlit run streamlit_app/app.py
