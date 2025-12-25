# 🍷 Wine Quality Prediction Using Machine Learning

## 📌 Project Overview
This project aims to predict wine quality using machine learning techniques based on physicochemical properties such as acidity, alcohol content, pH, sulphates, and more. The model classifies wine into good or bad quality categories, helping understand how chemical attributes influence wine quality.

---

## 🎯 Objectives
- Predict wine quality using machine learning
- Perform data preprocessing and feature engineering
- Compare multiple classification models
- Evaluate models using standard ML metrics
- Enable prediction using wine names from the dataset

---

## 📁 Dataset
The dataset is provided in CSV format and contains physicochemical attributes of red and white wines along with quality scores.

### Key Features:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Wine type (red/white)

Target Variable:
- Wine quality (converted into binary class: Good / Bad)

---

## ⚙️ Technologies Used
- Programming Language: Python
- Libraries:
  - Pandas
  - NumPy
  - Scikit-learn
  - XGBoost
  - Matplotlib
  - Seaborn

---

## 🧠 Machine Learning Workflow
1. Load dataset from CSV file
2. Handle missing values using mean imputation
3. Encode categorical variables
4. Feature scaling using Min-Max Scaler
5. Convert wine quality into binary classification
6. Split data into training and testing sets
7. Train multiple ML models
8. Evaluate models using ROC-AUC, confusion matrix, and classification report
9. Predict wine quality using wine name input

---

## 🤖 Models Implemented
- Logistic Regression
- Support Vector Machine (SVM)
- XGBoost Classifier

Among these, XGBoost showed the best performance.

---

## 📊 Model Evaluation
- ROC-AUC Score
- Confusion Matrix
- Precision, Recall, and F1-score
- Classification Report

These metrics help assess model accuracy and reliability.

---

## 🍷 Wine Name Based Prediction
The project supports prediction using wine names directly from the dataset. The model retrieves wine features from the CSV file, predicts its quality, and checks whether the prediction matches the actual label.

---

## 🚀 How to Run the Project
1. Clone the repository
2. Install required libraries
3. Run the notebook or Python script
4. Train the model
5. Use the prediction function to test wine quality

---

## 📌 Future Improvements
- Deploy as a web application using Flask or Streamlit
- Predict exact wine quality scores instead of binary labels
- Use larger datasets for improved accuracy
- Add real-time user input interface

---

## 📝 Conclusion
This project demonstrates the application of machine learning in quality prediction using real-world data. By combining proper preprocessing, feature scaling, and advanced models, the system effectively predicts wine quality and provides meaningful insights.

---

## 👨‍💻 Author
Wine Quality Prediction Project  
Machine Learning Based Classification
