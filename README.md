# 🩸 Diabetes Prediction using SVM

## 📌 Project Overview
This project aims to build a machine learning model to predict whether a patient has diabetes based on diagnostic measurements. The model uses a **Support Vector Machine (SVM)** classifier and is trained on the famous Pima Indians Diabetes Database.

## 📊 Dataset
* **Source:** National Institute of Diabetes and Digestive and Kidney Diseases (via Kaggle).
* **Features:** 8 medical attributes (e.g., Glucose level, BMI, Age, Insulin).
* **Target:** Outcome (0 = Healthy, 1 = Diabetic).

## 🛠️ Tools & Technologies Used
* **Python**
* **Pandas & NumPy:** Data manipulation and analysis.
* **Scikit-Learn:** Machine learning model (SVM) and data preprocessing (StandardScaler).
* **Matplotlib & Seaborn:** Data visualization and Confusion Matrix.

## 🚀 Model Tuning & Results
* **Data Preprocessing:** Applied `StandardScaler` to normalize the data, which significantly improved the SVM performance.
* **Kernel Choice:** Switched from a linear kernel to an **RBF (Radial Basis Function)** kernel to better capture complex relationships in the medical data.
* **Accuracy:** The final model achieved an accuracy of **79%**.

## 📈 Confusion Matrix
The project includes a visual representation of the model's performance using a Confusion Matrix, demonstrating its strong ability to identify true negatives and its improved recall for true positives.
