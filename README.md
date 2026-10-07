Breast Cancer Prediction using Machine Learning

📌 Project Overview

This project uses machine learning classification algorithms to predict breast cancer diagnosis from the Breast Cancer Wisconsin dataset.

The project includes data preprocessing, exploratory analysis, model training, model comparison, evaluation, and saving the final SVM model.

🎯 Objective

To build and evaluate machine learning classification models for predicting whether a breast tumor is Benign or Malignant.

📊 Dataset

Dataset: Breast Cancer Wisconsin Dataset

File: breast-cancer.csv

Samples: 569

Initial columns: 32

Target column: diagnosis

🤖 Algorithms Used

The following classification algorithms were evaluated:

Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Naive Bayes

🏆 Best Model

Support Vector Machine (SVM) achieved the best test-set performance.

Accuracy: 96.49%

F1-score: 0.96

Precision: 0.96

Recall: 0.96

📈 Model Comparison

Model

Accuracy

SVM

96.49%

Logistic Regression

95.91%

Random Forest

94.15%

Decision Tree

89.47%

KNN

~90.20%*

Naive Bayes

~89.97%*

Note: KNN and Naive Bayes values in the notebook are based on 10-fold cross-validation training results, while the other listed results are test-set results. Therefore, they should not be treated as a perfectly direct comparison.

🔄 Project Workflow

Load the dataset

Explore the data

Preprocess the data

Prepare features and target

Split data into training and testing sets

Train multiple classification models

Evaluate model performance

Compare the models

Select the best-performing SVM model

Save and reload the trained model

🛠️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

💾 Saved Model

The final SVM model is saved as:

svm_model_bc_detection.pkl

📁 Project Structure

breast-cancer-prediction-ml/
│
├── Breast_Cancer_Prediction_ML.ipynb
├── breast-cancer.csv
├── svm_model_bc_detection.pkl
└── README.md

▶️ How to Run

Clone or download this repository.

Make sure breast-cancer.csv is available in the expected project location.

Open Breast_Cancer_Prediction_ML.ipynb in Jupyter Notebook or Google Colab.

Run the notebook cells sequentially.

📌 Result

Among the evaluated models, SVM performed best with 96.49% test accuracy and an F1-score of 0.96.

👨‍💻 Author

Mozahidul Alam
CSE & AI Student
Khulna Khan Bahadur Ahsanullah University, Bangladesh
