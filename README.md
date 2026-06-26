# 💳 Credit Card Fraud Detection using Machine Learning

## 📖 About the Project

As online transactions continue to grow, detecting fraudulent credit card transactions has become an important machine learning problem. One of the biggest challenges is that fraud cases are extremely rare compared to normal transactions, making the dataset highly imbalanced.

In this project, I built a machine learning model to identify fraudulent credit card transactions using different classification algorithms. I explored the dataset, handled the class imbalance using **SMOTE**, trained multiple models, and compared their performance using appropriate evaluation metrics.

This project helped me understand the complete workflow of a real-world machine learning project—from data preprocessing to model evaluation.

---

## 🎯 Objectives

- Explore and understand the credit card transaction dataset.
- Analyze the imbalance between fraudulent and genuine transactions.
- Apply SMOTE to balance the training dataset.
- Train and compare multiple machine learning models.
- Evaluate each model using metrics suitable for imbalanced datasets.
- Identify the best-performing model for fraud detection.

---

## 📂 Dataset

This project uses the **Credit Card Fraud Detection** dataset from Kaggle.

### Dataset Summary

- **Total Transactions:** 284,807
- **Legitimate Transactions:** 284,315
- **Fraudulent Transactions:** 492

The dataset is highly imbalanced:

- Genuine Transactions → **99.83%**
- Fraudulent Transactions → **0.17%**

This imbalance makes fraud detection a challenging classification problem and highlights the importance of using techniques like SMOTE.

---

## 🛠️ Technologies Used

- Python
- VS Code
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost
- Joblib

---

## 📁 Project Structure

```text
Credit_Card_Fraud_Detection/
│
├── dataset/
├── notebook/
├── image/
├── models/
├── report/
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🔄 Project Workflow

✔ Load and explore the dataset

✔ Perform data cleaning and remove duplicate records

✔ Analyze class distribution

✔ Scale the features

✔ Split the dataset into training and testing sets

✔ Handle class imbalance using SMOTE

✔ Train three machine learning models

- Logistic Regression
- Random Forest
- XGBoost

✔ Evaluate each model using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score

✔ Compare model performance

✔ Save the trained models

---

## 🤖 Models Used

| Model | Purpose |
|--------|---------|
| Logistic Regression | Baseline classification model |
| Random Forest | Ensemble learning model |
| XGBoost | Gradient boosting model for improved performance |

---

## 📊 Results

	Model	            Accuracy     Precision	    Recall	     F1 Score
1	Random Forest	    0.999418	 0.887500      0.747368	     0.811429
2	XGBoost	            0.994713     0.219178	   0.842105	     0.347826
0	Logistic Regression	0.973672     0.053035      0.873684	     0.100000


> **Best Performing Model:** Random Forest was selected as the best-performing model because it achieved the highest F1 Score (0.8114), the highest Precision (0.8875), and the highest Accuracy (99.94%)

---

## 📷 Visualizations

### Class Distribution

![Class Distribution](image/class_distribution.png)

### ROC Curve

![ROC Curve](image/roc_curve.png)

### Logistic Regression Confusion Matrix

![Logistic Regression](image/confusion_matrix_lr.png)

### Random Forest Confusion Matrix

![Random Forest](image/confusion_matrix_rf.png)

### XGBoost Confusion Matrix

![XGBoost](image/confusion_matrix_xgb.png)

---

## 💡 What I Learned

Working on this project helped me gain practical experience with:

- Handling highly imbalanced datasets
- Using SMOTE for oversampling
- Training and evaluating multiple machine learning models
- Choosing evaluation metrics beyond accuracy
- Comparing model performance
- Saving trained models for future use

This project strengthened my understanding of the complete machine learning workflow and improved my confidence in building end-to-end ML projects.

---

## 🚀 Future Improvements

Some improvements I would like to explore in the future include:

- Hyperparameter tuning using GridSearchCV
- Cross-validation for better model evaluation
- Building an interactive Streamlit web application
- Real-time fraud prediction
- Model deployment using cloud services

---

## ▶️ How to Run the Project

### Clone the repository

```bash
git clone <repository-link>
```

### Navigate to the project folder

```bash
cd Credit_Card_Fraud_Detection
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the notebook

Open `Credit_Card_Fraud_Detection.ipynb` using Jupyter Notebook or VS Code and execute the cells in order.

---

## 👩‍💻 About Me

Hi! I'm **Shreya Gupta**, a B.Tech Computer Science Engineering student with a strong interest in **Data Analytics, Data Science, and Machine Learning**.

I'm continuously learning by building hands-on projects and exploring how data can be used to solve real-world problems.

I'm always open to learning, collaborating, and improving my skills.

---

⭐ If you found this project interesting, consider giving it a star!