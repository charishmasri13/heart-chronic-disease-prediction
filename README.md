# 🫀 Heart Chronic Disease Prediction using Artificial Neural Networks

This project uses an Artificial Neural Network (ANN) to predict the likelihood of chronic heart disease in individuals. The goal is to build a model that can assist in early detection using common health indicators and improve decision-making in medical diagnostics.

## 📌 Project Overview

Chronic heart disease is one of the major causes of mortality worldwide. Early diagnosis through predictive models can significantly improve patient outcomes. This project leverages machine learning—specifically an ANN—to analyze patient data and predict whether someone is likely to develop heart disease. The model is trained using features such as:

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol level
- Fasting blood sugar
- Resting electrocardiographic results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression
- Slope of ST segment
- Number of major vessels
- Thalassemia

## 📁 Files Included

- **`heart-ann.ipynb`**  
  Builds and trains an ANN model for heart disease prediction using a structured dataset. Includes data preprocessing, model training, and evaluation.

- **`heart-model-testing.ipynb`**  
  Loads the trained ANN model and performs predictions on new or test data to assess model performance and generalizability.

## 🚀 How to Run

### ✅ Requirements

Ensure you have Python and the following libraries installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
