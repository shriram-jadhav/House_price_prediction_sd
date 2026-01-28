# 🏠 House Price Prediction App (Linear Regression)

A simple Streamlit web application that predicts house prices based on house size using Simple Linear Regression.  
The app also visualizes the relationship between house size and price using an interactive Plotly graph.

---

## 📌 Project Overview

This project demonstrates:
- Generating synthetic housing data  
- Training a Linear Regression model using scikit-learn  
- Building an interactive UI with Streamlit  
- Visualizing data and predictions using Plotly  

Users can enter a house size (in square feet) and instantly get an estimated house price.

---

## 🧠 Machine Learning Concept Used

- **Model:** Linear Regression  
- **Input Feature:** House Size (sq ft)  
- **Target Variable:** House Price  
- **Data Type:** Synthetic data with noise  

The model learns a linear relationship:  
`price ≈ size × factor + noise`

---

## 🛠️ Tech Stack

- Python 3  
- Streamlit  
- NumPy  
- Pandas  
- Scikit-learn  
- Plotly  

---

---

## 🚀 How to Run the Project

1. **Clone the repository**
```bash
git clone https://github.com/your-username/House-Price-Prediction-App.git
cd House-Price-Prediction-App

pip install -r requirements.txt

streamlit run app.py

