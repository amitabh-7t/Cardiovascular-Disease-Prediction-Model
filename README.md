

# 🫀 **Cardiovascular Disease Prediction Model** 🧑‍⚕️

This project repository includes code and resources to create a machine learning model capable of predicting cardiovascular disease risk. Using patient data from clinical, lifestyle, and demographic sources, the model provides insights into high-risk individuals, supporting preventive healthcare decisions.

---

## 📋 **Table of Contents**
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Data and Preprocessing](#data-and-preprocessing)
- [Model Selection and Performance](#model-selection-and-performance)
- [Code Structure](#code-structure)
- [Getting Started](#getting-started)
- [Results](#results)
- [Future Work](#future-work)

---

## 📝 **Project Overview**

The purpose of this project is to develop a machine learning model for predicting cardiovascular disease. Early detection is essential for effective intervention, and machine learning provides a powerful tool for risk assessment based on a range of patient characteristics.

This project uses various classification algorithms, and after extensive testing, it aims to achieve a high level of accuracy (target: >90%).

---

## ⚙️ **Technologies Used**
- **Python** 🐍
- **Jupyter Notebooks** 📒
- **Scikit-Learn** 📊
- **Pandas** and **NumPy** 🧬
- **Imbalanced-Learn (SMOTE)** 📈

---

## 📊 **Data and Preprocessing**

The dataset includes patient demographic information, lifestyle habits, medical history, and clinical test results (e.g., cholesterol, blood pressure). Before modeling, data is preprocessed and features are scaled. Steps include:
- **Data Scaling**: Standardizing numeric features for consistent contribution to the model.
- **One-Hot Encoding**: Encoding categorical variables to make them suitable for machine learning.
- **Handling Class Imbalance**: Using **SMOTE** to balance data for improved model performance.

---

## 🤖 **Model Selection and Performance**

Several machine learning algorithms were tested, including:

| Model                    | Accuracy |
|--------------------------|----------|
| Logistic Regression      | 72%      |
| Logistic Regression (w/ balanced class weight) | 78% |
| Random Forest Classifier | 72%     |
| Random Forest Classifier (w/ class weights) | 77% |
| KNN model|74%|
|Decision Tree|75%|

**Best model accuracy goal**: >90%

Each model's performance is assessed based on accuracy, precision, recall, F1-score, and ROC-AUC to ensure robust classification. The final model choice is based on both accuracy and the ability to detect positive cases reliably.

---

## 📂 **Code Structure**

- **Data Preprocessing**: Scaling, encoding, and balancing techniques.
- **Model Training**: Code to train models like logistic regression and random forests, with tuning for regularization and class weights.
- **Evaluation**: Scripts to evaluate model accuracy, ROC-AUC, confusion matrices, and classification reports.
- **Threshold Adjustment**: Code to adjust classification threshold for optimizing sensitivity and specificity.

---

## 🚀 **Getting Started**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/amitabh-7t/Cardiovascular-Disease-Prediction-Model
   ```

2. **Install Requirements**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Model Notebook**
   Open and execute `MODEL.ipynb` to see model training, evaluation, and results.

---

## 📈 **Results**

The final model provides high accuracy for predicting cardiovascular disease, supporting healthcare professionals in risk assessment.

- **Default Threshold Accuracy**: 78%
- **Adjusted Threshold Performance**: TBD%

---

## 🔮 **Future Work**

- **Hyperparameter Tuning**: Further optimize models with GridSearch or Bayesian optimization.
- **New Features**: Add risk factors or advanced clinical indicators.
- **Deploy Model**: Package model for API or web app deployment for practical use in healthcare environments.

---

Feel free to contribute to this project by opening issues or submitting pull requests. For any inquiries, please contact : ENG23AM0215@dsu.edu.in .

Happy Predicting! 🎉
