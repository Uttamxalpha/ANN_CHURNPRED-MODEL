# ANN_CHURNPRED-MODEL
Built an ANN-based churn prediction model achieving accurate customer retention insights using TensorFlow and Scikit-learn.
📉 Customer Churn Prediction using ANN

This project implements an Artificial Neural Network (ANN) to predict customer churn (whether a customer will leave or stay).
The model is trained on structured customer data and framed as a binary classification problem.

🔗 Google Colab Notebook:
https://colab.research.google.com/drive/1MVdx6NE4MWetNN3fJiZDdAwj1fcIZNqY

🧠 Problem Statement

Customer churn negatively impacts business revenue.
The objective of this project is to identify customers likely to churn so that businesses can take early retention actions.

⚙️ Approach

Data loading and exploration

Data preprocessing

Handling categorical variables

Feature scaling using StandardScaler

Building an ANN using TensorFlow/Keras

Model training and validation

Model evaluation using accuracy and predictions

🏗️ Model Architecture

Input Layer: Customer features

Hidden Layers: Dense layers with ReLU activation

Output Layer: Sigmoid activation (binary classification)

Loss Function: Binary Cross-Entropy

Optimizer: Adam

🛠️ Tech Stack

Python

NumPy

Pandas

Scikit-learn

TensorFlow / Keras

Google Colab

📊 Results

The ANN successfully learns customer behavior patterns

Produces reliable churn predictions on unseen data

Demonstrates the effectiveness of neural networks on tabular data

🚀 How to Run
Option 1: Google Colab (Recommended)

Open the Colab link provided above

Run all cells sequentially

Option 2: Local Setup
pip install numpy pandas scikit-learn tensorflow


Run the notebook in Jupyter or VS Code.

📌 Use Cases

Telecom customer churn prediction

Banking and financial services

Subscription-based platforms

E-commerce customer retention

🔮 Future Improvements

Hyperparameter tuning

Handling class imbalance (SMOTE)

Model deployment using Flask / FastAPI

Performance metrics like ROC-AUC
