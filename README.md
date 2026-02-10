📊 Telecom Customer Churn Prediction

 🚀 Project Overview

This project focuses on predicting telecom customer churn using Machine Learning. Customer churn refers to customers who stop using a company’s services. By predicting churn in advance, businesses can take preventive actions to improve customer retention.

This project demonstrates an end-to-end machine learning workflow including data preprocessing, handling class imbalance, model training, evaluation, and feature importance analysis.

 🎯 Business Problem

A telecom company wants to identify customers who are likely to leave their service. Losing customers increases business costs because acquiring new customers is more expensive than retaining existing ones.

The goal is to build a predictive model that helps the company detect potential churners early.

 📁 Dataset

* Source: Kaggle Telecom Customer Churn Dataset
* The dataset contains customer demographic details, subscription information, usage patterns, and churn status.
  
 Key Features:

* Customer tenure
* Monthly charges
* Contract type
* Payment method
* Internet services
* Total charges
* Churn (Target Variable)

 🛠️ Technologies Used

* Python
* Google Colab / Jupyter Notebook
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)

 🔄 Project Workflow

 1️⃣ Data Preprocessing

* Loaded dataset using Pandas
* Handled missing values
* Encoded categorical variables
* Feature scaling applied

 2️⃣ Handling Class Imbalance

* Used SMOTE (Synthetic Minority Oversampling Technique)

 3️⃣ Model Building

* Random Forest Classifier used

 4️⃣ Model Evaluation

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
  
 5️⃣ Feature Importance

* Identified key factors influencing customer churn



 📈 Results

* Built an effective churn prediction model using Random Forest
* Improved performance using SMOTE
* Identified important churn-driving features

 ▶️ How to Run This Project

1. Clone this repository:

git clone <your-repository-link>

2. Open the notebook in Google Colab or Jupyter Notebook.

3. Install required libraries if needed:

pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

4. Run all cells step by step.

 📂 Repository Structure

├── Telecom_Customer_Churn.ipynb
├── dataset.csv
├── README.md

 🙋‍♀️ Author

Mounika Ajja

Machine Learning beginner project demonstrating an end-to-end ML pipeline.


⭐ If you like this project, feel free to star the repository!
