# churn_predition_project1

# 🧠 Churn Prediction Project

### 📋 Overview

The **Churn Prediction Project** is a simple Machine Learning project that helps businesses predict whether a customer will **leave (churn)** or **stay**. By analyzing customer details like monthly charges, contract type, and tenure, the model learns patterns that can warn a company before a customer leaves.

This project uses **Logistic Regression**, a basic and easy-to-understand algorithm that works great for **Yes/No (binary)** type predictions — in this case, predicting churn (1) or not churn (0).

---

### 🎯 Objective

To build a machine learning model that can **predict customer churn** based on their data and help businesses take early actions to retain them.

---

### 🧩 What This Project Does

1. **Collects and Prepares Data:**

   * Cleans the dataset.
   * Converts text data (like “Yes”, “No”, “Male”, “Female”) into numbers using **One Hot Encoding** or **DictVectorizer**.

2. **Feature Analysis:**

   * Finds which features are most important using **Feature Importance**, **Correlation Coefficient**, and **Mutual Information**.
   * Helps understand which customer details affect churn the most.

3. **Model Building:**

   * Implements **Logistic Regression** (and sometimes Linear Regression for comparison).
   * Trains the model to learn from customer data.

4. **Model Testing:**

   * Tests the model on **new customer data** to predict whether they will churn or not.
   * Produces a **probability score** — if it’s above 0.5, the model predicts the customer will churn.

5. **Model Interpretation:**

   * Explains which features increase or decrease the chance of churn.
   * For example, a high monthly charge might increase churn, while a long contract might reduce it.

---

### ⚙️ Technologies Used

* **Python** 🐍
* **NumPy** and **Pandas** for data handling
* **Matplotlib** for visualization
* **No external machine learning library (like scikit-learn)** — all models are implemented from scratch for better understanding

---

### 🚀 How It Works

1. Data → Input customer features (tenure, contract type, monthly charges, etc.)
2. Model → Logistic Regression calculates a probability using weights and bias.
3. Output → Probability of churn (e.g., 0.82 means 82% chance the customer will leave).


---

### 💡 What You’ll Learn

* How churn prediction works in real-world business cases.
* How to build and test **Logistic Regression** manually (without libraries).
* How to interpret model results and understand feature importance.
---

### 🏁 Conclusion

This project is a perfect **beginner-friendly introduction** to Machine Learning and data analysis. It helps you understand not only how models predict outcomes but also **why** they make those predictions.

With this knowledge, you can move on to more advanced projects like **Decision Trees, Random Forests, or Neural Networks** in the future.

---

