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

## 🧠 Challenges & Solutions
One of the main challenges in this project was dealing with medical data that is slightly imbalanced. Initially, the baseline linear model struggled to correctly identify diabetic patients (Class 1). To solve this, I implemented feature scaling using `StandardScaler` and switched to an **RBF kernel**, which significantly improved the model's *Recall* for positive cases and bumped the overall accuracy to 79%.

## 🔮 Future Work
As a next step to improve this project, I plan to:
* Experiment with ensemble methods like **Random Forest** or **XGBoost** to see if they can yield higher accuracy.
* Perform more advanced hyperparameter tuning using `GridSearchCV`.

## 🤝 Let's Connect!
I am always open to feedback and suggestions. Feel free to reach out to me on www.linkedin.com/in/ahmedeldesou2y

 to discuss this project, share advice, or explore potential collaborations!
