🩺 Diabetes Prediction Using Machine Learning and SMOTE

This project predicts whether a person is diabetic or non-diabetic using machine learning algorithms.
It uses the Pima Indians Diabetes Dataset and applies SMOTE (Synthetic Minority Oversampling Technique) to balance the data for better accuracy.

🧠 What This Project Does

Loads and preprocesses the diabetes dataset

Balances the dataset using SMOTE

Trains multiple machine learning models (Logistic Regression, Random Forest, KNN, SVM, XGBoost)

Evaluates models based on accuracy, recall, F1-score, and ROC-AUC

Saves the best-performing model

⚙️ Technologies Used

Python

Pandas, NumPy

Scikit-learn

Imbalanced-learn (SMOTE)

XGBoost

Matplotlib / Seaborn

📊 Dataset

Name: Pima Indians Diabetes Dataset

Source: Kaggle

Target Column: Outcome (0 = Non-Diabetic, 1 = Diabetic)

📈 Results

Best Model: Logistic Regression

ROC-AUC Score: 0.81

SMOTE helped improve recall and balance between diabetic and non-diabetic cases.

💡 Future Work

Create a web app for real-time predictions

Add hyperparameter tuning for better accuracy
