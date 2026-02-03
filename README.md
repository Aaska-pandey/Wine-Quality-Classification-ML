# 🍷 Wine Quality Prediction Using Machine Learning

![Platform](https://img.shields.io/badge/Platform-Web%20App-blue.svg)
![Language](https://img.shields.io/badge/Language-Python-green.svg)
![Category](https://img.shields.io/badge/Category-Machine%20Learning-purple.svg)
![Framework](https://img.shields.io/badge/Framework-Streamlit-red.svg)
![Model](https://img.shields.io/badge/Model-Random%20Forest-orange.svg)

**ML-Based Wine Quality Classification with Interactive Web Dashboard**

---

## 🖼️ Demo Preview

![Wine Quality Prediction App Demo](assets/app_ui.png)

🔗 **Live Demo:**  
👉 https://wine-quality-prediction-0jpm.onrender.com

---

## 📌 Overview

This project is a **Wine Quality Prediction System** built using **Machine Learning and Streamlit**.  
It allows users to predict whether a red wine is of **Good** or **Bad** quality based on its chemical properties.

The application uses a **Random Forest Classifier** trained on the **Wine Quality Dataset** and provides an interactive **web dashboard** for real-time predictions.

This project was developed as part of an **AI/ML learning and portfolio development program**.

---

## ✨ Features

🍷 Predicts wine quality (Good / Bad)  
🌐 Interactive Streamlit web dashboard  
📊 Displays model accuracy  
🎚 Easy-to-use slider-based inputs  
⚡ Real-time prediction results  
🛠 Beginner-friendly & expandable ML project  

---

## 🧠 Machine Learning Details

- **Algorithm:** Random Forest Classifier  
- **Problem Type:** Binary Classification  
- **Target Variable:** Wine Quality  
- **Class Mapping:**
  - Good Quality → Quality > 5  
  - Bad Quality → Quality ≤ 5  
- **Train-Test Split:** 80% Training | 20% Testing  
- **Evaluation Metric:** Accuracy Score  

---

## 🧪 Input Parameters

The model uses the following wine chemical properties:

- Fixed Acidity  
- Volatile Acidity  
- Citric Acid  
- Residual Sugar  
- Chlorides  
- Free Sulfur Dioxide  
- Total Sulfur Dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  

---

## 📊 Output

🍾 **Good Quality Wine**  
❌ **Bad Quality Wine**  

Model accuracy is shown directly on the web interface.

---

## 🛠 Tech Stack

- **Language:** Python 3.12.2  
- **Framework:** Streamlit  
- **ML Library:** Scikit-learn  
- **Data Processing:** Pandas, NumPy  

---

## 📁 Project Structure

wine-quality-prediction/
│── README.md
│── app.py
│── requirements.txt
│── runtime.txt
│── Wine Quality Classification.ipynb
│── assets/
│ └── app_ui.png


---

🔗 Live Application:
👉 https://wine-quality-prediction-0jpm.onrender.com

🧠 How It Works
Dataset is loaded and preprocessed

Wine quality is converted into binary classes

Random Forest model is trained

User inputs values via sliders

Model predicts wine quality

Result is displayed instantly

🔮 Future Enhancements
Multi-class wine quality prediction

Model comparison (Logistic, XGBoost, SVM)

Feature importance visualization

Cloud database integration

User authentication

🏅 Why This Project Is Valuable
This project demonstrates skills in:

✔ Machine Learning fundamentals
✔ Data preprocessing & feature engineering
✔ Model training and evaluation
✔ Streamlit web app development
✔ End-to-end ML deployment
