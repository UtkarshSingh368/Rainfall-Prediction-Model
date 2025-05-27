# Rainfall-Prediction-Model
This project aims to build a classification model that predicts whether it will rain tomorrow based on current weather data. It uses the Random Forest Classifier from Scikit-learn and a weather dataset collected from various Australian locations.

📁 Dataset
Source: weatherAUS.csv

Target Variable: RainTomorrow (Yes/No)

Features: Temperature, humidity, wind speed, pressure, etc.

🔧 Technologies Used
Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Google Colab

🧠 Methodology
Load and clean the dataset

Handle missing values (drop or impute)

Encode categorical variables using Label Encoding

Split the data into training and testing sets

Train a Random Forest Classifier

Make predictions and evaluate the model using accuracy, classification report, and confusion matrix

📊 Model Evaluation
Accuracy Score

Classification Report

Confusion Matrix

💾 How to Run
Clone the repository

Upload weatherAUS.csv in Google Colab or run locally

Install dependencies (pip install -r requirements.txt if needed)

Run the Jupyter/Colab notebook step-by-step

📈 Results
The Random Forest model performed well in predicting rainfall, providing reliable accuracy and detailed classification metrics for evaluation.

📌 Future Improvements
Hyperparameter tuning

Feature engineering

Try other algorithms (e.g., XGBoost, SVM)

Visual dashboard for predictions
