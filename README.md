# Telecom Customer Churn Prediction

This repository contains a machine learning project designed to predict whether a telecom customer will churn (leave the service) based on various factors like tenure, contract type, and monthly charges.

## 📌 Project Overview
The goal of this project is to help telecom companies identify high-risk customers and take proactive measures to retain them. By analyzing customer behavior and service usage, we build a predictive model that classifies customers into 'Churn' or 'No Churn' categories.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Deployment/UI:** Gradio (for real-time prediction interface)

## 📊 Workflow
1.  **Data Preprocessing:** Handling missing values (specifically in TotalCharges), encoding categorical variables, and feature scaling.
2.  **Exploratory Data Analysis (EDA):** Visualizing churn patterns across different demographics and contract types.
3.  **Model Building:** Training multiple classifiers (Logistic Regression, Random Forest, etc.) to find the most accurate model.
4.  **Interface:** Created a Gradio web interface where users can input customer details and get instant churn risk results.

## 🚀 Key Insights
* Customers with **Month-to-month** contracts have a higher churn rate compared to long-term contracts.
* **Tenure** is a significant factor; new customers are more likely to leave.
* High **Monthly Charges** often correlate with higher churn risk.

## 📂 Project Structure
* `Telecom_Customer_Churn_Predictor.ipynb`: The main Jupyter Notebook with analysis and modeling.
* `requirements.txt`: List of required Python packages.
* `WA_Fn-UseC_-Telco-Customer-Churn.csv`: The dataset used for training.

## ⚙️ How to Run
1. Clone the repo: `git clone <your-repo-link>`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook to launch the Gradio interface.
