# 🏦 Loan Prediction using Machine Learning

## 📌 Project Overview

**Loan Prediction** is a Machine Learning web application built with **Python and Streamlit** that predicts whether a loan application is likely to be **Approved or Rejected** based on applicant and financial information.

The project uses a **Random Forest Classifier** to learn patterns from historical loan application data and provides an interactive Streamlit interface where users can enter applicant details and receive a prediction in real time.

## 🎯 Objectives

* Predict loan approval based on applicant information.
* Perform data cleaning and preprocessing.
* Analyze important factors affecting loan approval.
* Train and evaluate a machine learning classification model.
* Build an interactive web application using Streamlit.
* Provide real-time loan eligibility predictions.

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations
* **Scikit-learn** – Machine Learning
* **Streamlit** – Web application
* **Matplotlib / Seaborn** – Data visualization
* **Jupyter Notebook** – Model development
* **Pickle** – Model serialization

## 🤖 Machine Learning Model

The project uses a **Random Forest Classifier** for loan prediction.

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction performance and reduce overfitting.

### Machine Learning Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Preprocessing
   ↓
Feature Engineering
   ↓
Train-Test Split
   ↓
Random Forest Classifier
   ↓
Model Evaluation
   ↓
Save Trained Model
   ↓
Streamlit Application
   ↓
Loan Prediction
```

## 📊 Dataset

The dataset contains information about loan applicants, including:

* Gender
* Married Status
* Dependents
* Education
* Self-Employed Status
* Applicant Income
* Co-Applicant Income
* Loan Amount
* Loan Term
* Credit History
* Property Area

The target variable represents the loan approval status.

## 🔍 Data Preprocessing

The following preprocessing techniques were performed:

* Handling missing values
* Removing or treating inconsistent data
* Encoding categorical variables
* Feature selection
* Feature transformation
* Splitting data into training and testing sets

## 📈 Model Evaluation

The Random Forest model can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help measure the performance of the classification model.

## 🌐 Streamlit Application

The Streamlit application provides an interactive interface where users can enter loan applicant details.

### Prediction Workflow

```text
User enters applicant details
          ↓
Streamlit receives input
          ↓
Input preprocessing
          ↓
Trained Random Forest Model
          ↓
Prediction
          ↓
Loan Approved / Loan Rejected
```

## 📂 Project Structure

```text
Loan_Prediction/
│
├── app.py
├── model.pkl
├── requirements.txt
├── README.md
│
├── Loan_Prediction.ipynb
│
└── dataset/
    └── loan_data.csv
```

> The exact structure may vary depending on the files included in the repository.

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Ruthu543/Loan-Prediction.git
```

### 2. Navigate to the project directory

```bash
cd Loan-Prediction
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Streamlit Application

Run the following command:

```bash
streamlit run app.py
```

Streamlit will provide a local URL similar to:

```text
http://localhost:8501
```

Open the URL in your browser to use the application.

## 💡 Key Features

* Machine Learning-based loan prediction
* Random Forest classification
* Data preprocessing and feature engineering
* Interactive Streamlit interface
* Real-time prediction
* Easy-to-use applicant input form
* Model-based loan approval prediction

## 🚀 Future Improvements

* Deploy the application using Streamlit Community Cloud.
* Add prediction probability/confidence scores.
* Compare Random Forest with Logistic Regression, XGBoost, and other models.
* Perform hyperparameter tuning.
* Add interactive data visualizations.
* Add a database to store prediction history.
* Improve UI/UX of the Streamlit application.

## 👩‍💻 Author

**Ruthu Madhavi Kola**

GitHub:
https://github.com/Ruthu543

## 📜 License

This project is created for educational and portfolio purposes.

