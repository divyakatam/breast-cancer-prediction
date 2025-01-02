# breast-cancer-prediction
This project focuses on predicting breast cancer using machine learning techniques. The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset, which is imported directly from the sklearn.datasets module. This dataset contains 30 features computed from digitized images of breast mass fine needle aspirates (FNAs). The goal is to classify tumors as malignant or benign based on these features.

Features:
--> Implemented using three machine learning models:
       Logistic Regression
       Random Forest Classifier
       Decision Tree Classifier
--> Utilized k-fold cross-validation to evaluate model performance and ensure robustness.
-->Saved and reused trained models using Pickle.
-->Results of model evaluation for each fold are stored in a structured CSV file.

Technologies Used:
Python: Core programming language for data processing and modeling.

Libraries:
-->sklearn for dataset loading, model training, and evaluation.
-->pandas for data manipulation.
-->numpy for numerical computations.
-->pickle for model persistence.

Google Colab: Development environment for running the code.
GitHub: Repository for version control and sharing the project.

Purpose:
This project is a hands-on implementation to demonstrate the use of machine learning in medical diagnostics. It also serves as an educational project for learning about:
   Model training and evaluation.
   Cross-validation techniques.
   Working with real-world datasets.
