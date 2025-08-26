
# 🩺 Diabetes Prediction – Data Analysis & Machine Learning

## 📌 Project Overview
This project analyzes the **Pima Indians Diabetes Dataset**, which contains medical data of women aged 21+ from the Pima Indian population in Arizona.  
The goal is to explore the data, clean it, visualize key patterns, and build **machine learning models** to predict the likelihood of diabetes.  

---

## 🔍 Steps Taken
1. **Data Cleaning** handled invalid zero values in features such as Glucose, BloodPressure, BMI, etc. by replacing them with median values.  
2. **Exploratory Data Analysis (EDA)** created visualizations:  
   - Distribution of Glucose and BMI  
   - Age distribution and its relation to diabetes  
   - Correlation Heatmap  
3. **Train/Test Split** dataset split into 70% training and 30% testing.  
4. **Modeling** compared **Decision Tree** and **SVM** classifiers.  
5. **Evaluation** measured Accuracy, Precision, Recall, F1-score, Confusion Matrix, and ROC Curve.  

---

## 📊 Model Performance Results

| Model          | Accuracy | Precision | Recall | F1 |
|----------------|----------|-----------|--------|----|
| Decision Tree  | 0.69     | 0.56      | 0.53   | 0.55 |
| SVM            | 0.72     | 0.64      | 0.47   | 0.54 |

---


## 🚀 Why This Project is Important
Diabetes is a growing global health concern. Predictive models can assist healthcare professionals in early detection and risk assessment.  
This project demonstrates the ability to:  
- Perform **data cleaning and preprocessing**  
- Conduct **EDA with visualizations**  
- Apply and compare **machine learning models**  
- Communicate results clearly with visual and written documentation  

---

## 🧭 Next Steps
- Try additional models such as **Logistic Regression** and **Random Forest**.  
- Perform **Hyperparameter Tuning** to optimize model performance.  
- Use **Cross Validation** for more robust evaluation.  
- Expand the analysis with larger and more diverse datasets.  

---

## 📦 Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn)  
- **Visualization**: Matplotlib, Seaborn  
- **Environment**: Google Colab / Jupyter Notebook
