# 🚗 Car_price_prediction_system

A Machine Learning-powered web application that predicts the selling price of used cars based on key vehicle attributes such as company, model, manufacturing year, fuel type, and kilometers driven.

## 📌 Overview

This project uses a Linear Regression model trained on a cleaned used-car dataset to estimate the market price of a car. The model is deployed through a Flask web application that allows users to enter vehicle details and receive an instant price prediction.

## ✨ Features

- Predict used car prices in real time
- Simple and interactive user interface
- Dynamic selection of car companies and models
- Supports multiple fuel types
- Flask-based web deployment
- Machine Learning model integration using Scikit-Learn

## 🛠️ Technologies Used

- Python
- Flask
- Scikit-Learn
- Pandas
- NumPy
- HTML
- CSS
- Bootstrap

## 📊 Input Features

The prediction model uses the following inputs:

- Car Company
- Car Model
- Manufacturing Year
- Fuel Type
- Kilometers Driven

## 🧠 Machine Learning Pipeline

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Encoding
5. Model Training using Linear Regression
6. Model Evaluation
7. Deployment using Flask

## 📂 Project Structure

```text
Car-Price-Predictor/
│
├── static/
├── templates/
│   └── index.html
│
├── app.py
├── LinearRegressionModel.pkl
├── cleaned car dataset.csv
├── requirements.txt
└── README.md
```

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Car-Price-Predictor.git
cd Car-Price-Predictor
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

## 📈 Model Information

- Algorithm: Linear Regression
- Problem Type: Regression
- Target Variable: Car Price

## 🚀 Future Enhancements

- Improve prediction accuracy using Random Forest and XGBoost
- Add more vehicle features
- Deploy on Render or AWS
- Build REST API support
- Add visual analytics dashboard

## 👨‍💻 Author

**Abhinav**

B.Tech in Artificial Intelligence
