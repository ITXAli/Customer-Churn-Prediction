# 📊 Customer Churn Prediction - End-to-End ML Pipeline

This project focuses on building a **production-ready machine learning pipeline** to predict customer churn using the **Telco Churn Dataset**.

It includes data preprocessing, model training, hyperparameter tuning, pipeline serialization, and deployment via Gradio.

---

## 🔍 Problem Statement

Telecommunication companies face high customer churn. The goal is to build an automated ML pipeline that can predict whether a customer is likely to churn based on their service usage and demographic features.

---

## 📁 Project Highlights

✅ Built using **Scikit-learn Pipeline API** and **imbalanced-learn**  
✅ Combined preprocessing, resampling, and model training into one reusable pipeline  
✅ Handled class imbalance with **SMOTE**  
✅ Used **GridSearchCV** for hyperparameter tuning  
✅ Deployed a **Gradio app** for real-time predictions  
✅ Exported the complete pipeline using `joblib` for future inference

---

## 🧠 Tech Stack

- Python
- Scikit-learn
- imbalanced-learn
- Pandas, NumPy
- Matplotlib, Seaborn (for EDA)
- Gradio (for deployment)
- Joblib (for saving pipeline)

---

## 🏗️ Pipeline Steps

1. **Data Preprocessing**  
   - Missing value imputation (numeric + categorical)
   - Scaling numeric features
   - Encoding categorical features

2. **Handling Class Imbalance**  
   - Used **SMOTE** to generate synthetic samples of the minority class

3. **Model Training**  
   - Logistic Regression  
   - Random Forest  
   - Hyperparameter tuning via **GridSearchCV**

4. **Exporting Pipeline**  
   - Used `joblib.dump()` to save the pipeline  
   - Loaded back using `joblib.load()` during deployment

5. **Deployment**  
   - Built an interactive UI with **Gradio**  
   - Accepts inputs and returns churn prediction with probability

---

## 📊 Results

- **Accuracy**: ~82%  
- **F1-score (Churn class)**: ~0.65  
- Model performance was improved using preprocessing and class balancing.

---

## 🚀 How to Run

1. Clone the repository or open notebook on Kaggle
2. Run the notebook end-to-end
3. Make sure the `.pkl` file is saved using `joblib.dump()`
4. Run the Gradio cell to launch the app

---

## 📂 Dataset

- Dataset: [Telco Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)

---

## 📌 Credits

This project was completed during my internship to strengthen my practical skills in **machine learning pipelines and deployment**.

---

## 🏷️ Tags

`Machine Learning` `Churn Prediction` `SMOTE` `Pipeline` `Gradio` `Python` `ML Deployment`


