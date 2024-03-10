Alzheimer's Disease Detection using Machine Learning on MRI Longitudinal Dataset
Utilizing a longitudinal MRI dataset, machine learning models can accurately detect Alzheimer's disease by analyzing structural and temporal changes in brain images, providing a non-invasive and efficient diagnostic approach for early detection and intervention.
Overview
This repository contains code and resources for a machine learning project aimed at detecting Alzheimer's Disease using longitudinal MRI data. The project focuses on developing models that can analyze changes in brain structures over time to identify patterns indicative of Alzheimer's Disease progression.
 Dataset
The dataset used in this project consists of longitudinal MRI scans of individuals with and without Alzheimer's Disease. Due to privacy and ethical considerations, the dataset used in this project is not included in this repository. However, instructions for obtaining the dataset and preprocessing steps are provided in the `data/` directory.
This project focuses on the application of machine learning algorithms for the detection of Alzheimer's Disease using MRI longitudinal dataset. Four different algorithms, namely Support Vector Machine (SVM), Random Forest, Decision Tree, and Logistic Regression, were employed to analyze the data and predict the presence of Alzheimer's Disease.
 Algorithms
 Support Vector Machine (SVM)
SVM is a supervised learning algorithm that can be used for classification or regression tasks. In this project, SVM is employed to classify MRI scans into Alzheimer's Disease or non-Alzheimer's Disease categories.
 Random Forest
Random Forest is an ensemble learning method that operates by constructing a multitude of decision trees at training time. The final decision is made based on the majority vote of the individual trees. Random Forest is utilized here for its ability to handle complex datasets and reduce overfitting.
Decision Tree
Decision Tree is a tree-like model where an internal node represents a feature, the branch represents a decision rule, and each leaf node represents the outcome. Decision Tree is employed for its simplicity and interpretability.
Logistic Regression
Logistic Regression is a statistical method used for binary classification problems. It models the probability that an instance belongs to a particular category. Logistic Regression is chosen in this project for its simplicity and effectiveness in binary classification tasks.
Project Structure
- `src/`: Contains the source code for data preprocessing, model development, and evaluation.
- `data/`: Placeholder for instructions on obtaining the dataset and preprocessing steps.
- `models/`: Saved model checkpoints and pre-trained models.
- `notebooks/`: Jupyter notebooks for data exploration, model training, and evaluation.
- `requirements.txt`: List of Python dependencies required for the project.

