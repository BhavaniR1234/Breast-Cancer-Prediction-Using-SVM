# Breast-Cancer-Prediction-Using-SVM
Breast Cancer Prediction System using SVM and the WDBC dataset. Includes data preprocessing, model training, evaluation, and a web-based UI for real-time benign/malignant predictions with confidence scores. Lightweight, accurate, and easy to deploy.
This project implements a Breast Cancer Prediction System that uses machine learning to classify tumors as benign or malignant based on the Wisconsin Diagnostic Breast Cancer (WDBC) dataset. The model is built using a Support Vector Machine (SVM) classifier, which is known for its high accuracy and ability to handle nonlinear medical data. The dataset undergoes preprocessing steps such as normalization, feature scaling, and correlation analysis to ensure reliable model performance.

After training and evaluating the SVM model, the system is integrated with a web-based user interface where users can input tumor features and get real-time predictions. The interface displays the classification result along with a confidence score, making the output more transparent and user-friendly. The project is lightweight, easy to deploy, and demonstrates a full end-to-end machine learning workflow—from dataset processing to UI-based prediction.

Breast Cancer Prediction System

This project implements a machine learning model to classify breast tumors as benign or malignant using the Wisconsin Diagnostic Breast Cancer (WDBC) dataset. The system uses a Support Vector Machine (SVM) classifier and includes a simple web interface that allows users to enter tumor feature values and receive real-time predictions along with confidence scores. The goal of this project is to build a lightweight, interpretable, and easy-to-use diagnostic support tool.

Features

SVM-based tumor classification

Real-time predictions from a web interface

Confidence score for every prediction

Preprocessing pipeline including normalization and feature analysis

Lightweight application that runs on basic hardware

Easy to deploy and extend

Tech Stack

Machine Learning: Python, NumPy, Pandas, Scikit-learn
Frontend: HTML, CSS, JavaScript
Backend (optional): Flask or Django
Development Tools: Jupyter Notebook, VS Code / PyCharm

Project Structure
breast-cancer-prediction/
│
├── model/
│   ├── breast_cancer_prediction.ipynb
│   └── trained_model.pkl (optional)
│
├── ui/
│   ├── index.html
│   ├── styles.css (optional)
│   └── script.js (optional)
│
├── dataset/
│   └── data.csv
│
└── README.md

How to Run

Install required libraries:

pip install numpy pandas scikit-learn flask


Open and run the Jupyter Notebook to view or train the model:

jupyter notebook breast_cancer_prediction.ipynb


If using Flask for backend:

python app.py


Access the interface in your browser at:

http://localhost:5000


If using a purely front-end UI, simply open:

ui/index.html

Dataset Information

The system uses the Wisconsin Diagnostic Breast Cancer (WDBC) dataset containing 569 samples and 30 numerical features.
Each sample is labeled as either benign (0) or malignant (1).
Dataset source: UCI Machine Learning Repository.

Model Workflow

Load and inspect the dataset

Apply preprocessing and normalization

Train SVM classifier with RBF kernel

Evaluate using accuracy, precision, recall, and F1-score

Connect model to UI for real-time predictions

Future Enhancements

Deploy the system on cloud platforms

Add model explainability using SHAP

Provide downloadable prediction reports

Integrate additional ML models for comparison

Author

Seri
Machine Learning Enthusiast

