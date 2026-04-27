# Heart Disease Prediction

This project focuses on building a predictive model to determine the likelihood of heart disease in patients based on various medical attributes. Using machine learning algorithms, the project covers data preprocessing, feature scaling, and performance evaluation to ensure accurate diagnostic predictions.

---

### ## Table of Contents
* [Overview](#overview)
* [Dataset](#dataset)
* [Technologies Used](#technologies-used)
* [Project Workflow](#project-workflow)
* [Installation and Usage](#installation-and-usage)
* [Results](#results)

---

### ## Overview
The primary objective of this project is to assist in the early detection of heart disease. By analyzing clinical parameters, the model identifies patterns that distinguish healthy individuals from those at risk, utilizing classification algorithms like **Logistic Regression** and **Random Forest**.

---

### ## Dataset
The model is trained on medical data containing clinical features such as:
* **Patient Metrics:** Age, sex, and chest pain type.
* **Clinical Readings:** Resting blood pressure, cholesterol levels, and fasting blood sugar.
* **Health Indicators:** Maximum heart rate achieved and exercise-induced angina.

---

### ## Technologies Used
The following libraries are used for data analysis and model building:
* **Pandas & NumPy:** For data cleaning and structured manipulation.
* **Matplotlib & Seaborn:** For exploratory data analysis (EDA) and visualizing medical trends.
* **Scikit-learn:** For data scaling (`StandardScaler`), encoding, and implementing machine learning classifiers.

---

### ## Project Workflow
1. **Data Preprocessing:** Handling missing values and encoding categorical medical data.
2. **Feature Scaling:** Normalizing clinical features using `StandardScaler` for better model convergence.
3. **Exploratory Data Analysis:** Visualizing correlations between health factors and heart disease.
4. **Model Implementation:** Training multiple classifiers including **Logistic Regression** and **Random Forest**.
5. **Model Evaluation:** Comparing model performance using accuracy scores and classification metrics.

