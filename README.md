Heart Disease Prediction

A machine learning classification project that predicts whether a person is likely to have heart disease based on clinical and demographic features. The project includes data preprocessing, exploratory data analysis, feature scaling, training multiple machine learning models, model evaluation, and deployment using Streamlit.

📁 Project Structure
heart-disease-prediction/
│
├── app.py                  # Streamlit application
├── heart.csv               # Heart disease dataset
├── Heartdisease.ipynb      # Jupyter Notebook for analysis and model training
│
├── KNN.pkl                 # Trained KNN model
├── scaler.pkl              # Saved StandardScaler
├── columns.pkl             # Saved feature/column information
│
└── .vscode/                # VS Code configuration
🔄 Project Workflow

Data Collection → Data Preprocessing → Exploratory Data Analysis → Feature Engineering → Feature Scaling → Model Training → Model Evaluation → Model Saving → Streamlit Deployment → Prediction

🤖 Machine Learning Models

Multiple classification algorithms were trained and compared:

Logistic Regression — Linear classification algorithm used as a baseline for binary heart disease prediction.
K-Nearest Neighbors (KNN) — Classifies observations based on their nearest neighbors in the feature space.
Gaussian Naive Bayes — Probabilistic classifier based on Bayes' theorem.
Decision Tree Classifier — Uses decision rules based on feature values for classification.
Support Vector Machine (SVM – RBF Kernel) — Uses an RBF kernel to handle non-linear classification boundaries.

The KNN model was saved and integrated into the Streamlit application for prediction.

🧹 Data Preprocessing

The dataset was prepared using:

Missing-value checking
Duplicate-value checking
Exploratory data analysis
Categorical feature encoding
Feature analysis and selection
Train-test splitting
Feature standardization using StandardScaler
📊 Model Evaluation

The trained models were evaluated using:

Accuracy
Precision
Recall
F1-score
Confusion Matrix
Classification Report

The performance of the different models was compared using the test dataset.

🚀 Deployment

The trained KNN model was saved using Joblib along with the preprocessing objects:

KNN.pkl — trained KNN model
scaler.pkl — feature scaler
columns.pkl — model input feature information

These files are loaded by the Streamlit application (app.py) to process user inputs and generate predictions.

🖥️ Application

The Streamlit application provides an interactive interface where users can enter the required patient features and receive a machine learning-based heart disease prediction.

🛠️ Tech Stack

• Python • Pandas • NumPy • Matplotlib • Seaborn • Scikit-learn • Logistic Regression • KNN • Gaussian Naive Bayes • Decision Tree • SVM (RBF Kernel) • StandardScaler • Streamlit • Joblib • Jupyter Notebook 

✨ Key Features
Multiple machine learning classification models
Data preprocessing and feature scaling
Exploratory data analysis and visualization
Model performance comparison
Saved KNN model for prediction
Saved preprocessing objects
Streamlit-based prediction interface
End-to-end machine learning workflow
