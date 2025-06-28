# 🌼 Flower Species Predictor

This is a simple machine learning web app that predicts the species of a flower based on its **sepal length**, **sepal width**, **petal length**, and **petal width**. It uses a `RandomForestClassifier` model and is deployed with a user-friendly **Streamlit** interface.

## 🔍 Overview

- 📊 **Model**: RandomForestClassifier (Scikit-learn)
- 🌸 **Dataset**: Iris Dataset (built-in in scikit-learn)
- 🖥️ **Frontend**: Streamlit
- ⚙️ **Features Used**:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width

## 🧠 How It Works

1. The model is trained on the famous **Iris dataset**.
2. User inputs values for sepal/petal measurements.
3. The trained model predicts the **species of the flower**.
4. The prediction is shown instantly on the Streamlit web app.