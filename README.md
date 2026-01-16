# ANN

# 📊 Customer Churn Prediction using ANN

## 📌 Project Description
This project is focused on predicting **customer churn** using an **Artificial Neural Network (ANN)** trained on a churn dataset. The objective is to determine whether a customer is likely to **leave (churn)** or **stay** based on their personal and account-related information.

The project consists of **two main parts**:
1. **Model Training**
2. **Model Prediction using a Streamlit Web Application**

---

## 🧠 Part 1: Model Training
- A customer churn dataset is used for training.
- Data preprocessing is performed using a **ColumnTransformer** to handle categorical and numerical features.
- An **Artificial Neural Network (ANN)** is built and trained using **TensorFlow / Keras**.
- The trained model is saved as `model.h5`.
- The preprocessing pipeline is saved as `preprocessor.pkl` to ensure consistency during prediction.

---

## 🔮 Part 2: Model Prediction (Streamlit App)
- A **Streamlit-based web application** is developed for model prediction.
- Users can input customer details such as:
  - Credit Score
  - Geography
  - Gender
  - Age
  - Tenure
  - Balance
  - Number of Products
  - Credit Card Status
  - Active Membership
  - Estimated Salary
- The input data is preprocessed using the saved preprocessing pipeline.
- The trained ANN model predicts the **probability of customer churn**.
- The app displays:
  - Churn probability
  - Final prediction: **Customer will Leave or Stay**

---

## 🚀 Features
- Interactive user interface using Streamlit
- Real-time churn prediction
- Consistent preprocessing between training and prediction
- Probability-based classification output

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Streamlit
- Pandas
- Scikit-learn
- Pickle

---

## 📁 Project Structure


👨‍💻 Author

Name: Manidipa Mandal
Role: Data Science / Machine Learning Enthusiast
GitHub: https://github.com/Manidipa7894
