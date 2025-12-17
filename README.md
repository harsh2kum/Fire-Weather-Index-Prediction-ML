# 🔥 Fire Weather Index (FWI) Prediction | Machine Learning Project

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-green)
![Flask](https://img.shields.io/badge/Flask-Web%20App-black)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

An **end-to-end Machine Learning project** built using the **Algerian Forest Fires dataset** to predict the **Fire Weather Index (FWI)**.  
This project demonstrates the complete ML lifecycle — from **EDA and feature engineering** to **model deployment using Flask**.

---

## 📌 Project Overview

Forest fires are strongly influenced by weather conditions such as temperature, humidity, wind speed, and rainfall.  
The **Fire Weather Index (FWI)** is an important indicator used to estimate fire risk intensity.

In this project, I:
- Analyzed the dataset using Exploratory Data Analysis (EDA)
- Performed feature engineering and scaling
- Trained a regression model using **Ridge Regression**
- Deployed the trained model as a **Flask web application**

---

## 📊 Dataset Information

- **Dataset Name:** Algerian Forest Fires Dataset  
- **Source:** UCI Machine Learning Repository  
- **Regions Covered:** Bejaia & Sidi Bel-Abbes (Algeria)  
- **Target Variable:** Fire Weather Index (FWI)

### Key Features
- Temperature  
- Relative Humidity (RH)  
- Wind Speed (Ws)  
- Rain  
- FFMC  
- DMC  
- ISI  
- Classes  
- Region  

---

## 🧠 Machine Learning Pipeline

1. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Correlation study
   - Fire vs non-fire patterns

2. **Feature Engineering**
   - Data cleaning
   - Encoding categorical features
   - Feature scaling using `StandardScaler`

3. **Model Training**
   - Algorithm: **Linear Regression with Ridge Regularization**
   - Helps prevent overfitting

4. **Model Evaluation**
   - R² Score  
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)

5. **Deployment**
   - Model and scaler saved using `pickle`
   - Flask-based web application for real-time predictions

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn  
- **Machine Learning:** Ridge Regression  
- **Web Framework:** Flask  
- **Frontend:** HTML  
- **Version Control:** Git & GitHub  

---

---

## 🌐 Web Application

The web application allows users to:
- Enter weather and fire-related parameters
- Predict the **Fire Weather Index (FWI)** in real time

> Example output:  
**The FWI Prediction is 0.78**

---

## 🚀 How to Run the Project Locally

```bash
1️⃣ Clone the Repository
git clone https://github.com/your-username/Fire-Weather-Index-Prediction.git
cd Fire-Weather-Index-Prediction

2️⃣ Create Virtual Environment
python -m venv venv
venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run Flask App
python application.py

5️⃣ Open Browser
http://127.0.0.1:5000/
```
