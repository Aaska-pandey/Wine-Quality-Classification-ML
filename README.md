🍷 Wine Quality Prediction Web App

🔗 Live Demo:
👉 https://wine-quality-prediction-0jpm.onrender.com


📌 Project Overview

The Wine Quality Prediction App is a Machine Learning–powered web application that predicts whether a red wine is of Good or Bad quality based on its chemical composition.

The application is built using Python, Streamlit, and Scikit-learn, providing an interactive interface where users can input wine properties and instantly get predictions.

🚀 Key Features

Interactive and responsive Streamlit UI

Real-time wine quality prediction

Random Forest Classifier for high accuracy

Displays model accuracy on test data

Easy-to-use sliders for all input features

Beginner-friendly and production-ready ML project

🧠 Machine Learning Model

Algorithm: Random Forest Classifier

Problem Type: Binary Classification

Classes:

Good Quality → Wine quality > 5

Bad Quality → Wine quality ≤ 5

Train-Test Split: 80% training, 20% testing

Evaluation Metric: Accuracy Score

🧪 Input Features

The prediction is based on the following chemical properties of wine:

Fixed Acidity

Volatile Acidity

Citric Acid

Residual Sugar

Chlorides

Free Sulfur Dioxide

Total Sulfur Dioxide

Density

pH

Sulphates

Alcohol

📊 Output

🍾 Good Quality Wine

❌ Bad Quality Wine

Model accuracy displayed on the app interface

🛠️ Tech Stack

Programming Language: Python 3.12.2

Framework: Streamlit

ML Library: Scikit-learn

Data Handling: Pandas, NumPy

📁 Project Structure
├── app.py                          # Streamlit application
├── requirements.txt                # Project dependencies
├── runtime.txt                     # Python version
├── Wine Quality Classification.ipynb
├── assets/
│   └── app_ui.png                  # App screenshot
└── README.md

▶️ Run Locally
pip install -r requirements.txt
github
streamlit run app.py

🌐 Deployment

The application is deployed using Streamlit Cloud and can also be deployed on:

Render

Heroku
