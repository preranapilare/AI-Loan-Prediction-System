# AI Loan Prediction System

## 📌 Project Overview

The **AI Loan Prediction System** is a machine learning-based web application developed using **Python and Django**. The system predicts whether a loan application is likely to be approved based on applicant information such as income, loan amount, credit score, and employment status.

The project combines **Machine Learning, Data Analysis, and Web Development** to provide an interactive platform for loan prediction.

---

## 🎯 Objectives

* Predict loan approval using machine learning.
* Provide an easy-to-use web interface for applicants.
* Allow users to enter financial and employment information.
* Display loan prediction results instantly.
* Provide additional features such as prediction history and EMI calculation.
* Provide an employee/admin interface for managing loan-related information.

---

## ✨ Features

* 🔐 User Registration and Login
* 🏦 AI-based Loan Approval Prediction
* 📊 Machine Learning Prediction
* 📋 Prediction History
* 🧮 EMI Calculator
* 📁 CSV/Data Upload
* 👨‍💼 Employee Dashboard
* 📈 Data Visualization
* 💾 Database Integration
* 🌐 Django Web Application

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Web Framework

* Django

### Machine Learning

* Scikit-learn
* Pandas
* NumPy

### Database

* SQLite

### Frontend

* HTML
* CSS
* Bootstrap

### Development Tools

* VS Code
* Jupyter Notebook
* Git
* GitHub

---

## 🤖 Machine Learning

The system uses machine learning algorithms to predict loan approval based on applicant information.

### Input Features

The prediction can use information such as:

* Applicant Income
* Loan Amount
* Credit Score
* Employment Status

### Machine Learning Algorithms

The project can use supervised machine learning algorithms such as:

* Logistic Regression
* Random Forest
* XGBoost

The trained machine learning model is integrated into the Django web application to generate predictions.

---

## 🏗️ Project Structure

```text
AI_LOAN_PROJECT/
│
├── accounts/
├── core/
├── predictor/
├── templates/
├── media/
│
├── screenshots/
│   ├── login.png
│   ├── register.png
│   ├── loan_prediction.png
│   ├── prediction_result.png
│   ├── prediction_history.png
│   ├── employee_dashboard.png
│   ├── emi_calculator.png
│   └── csv_upload.png
│
├── loan_data.csv
├── loan_model.pkl
├── manage.py
├── train_model.py
├── requirements.txt
├── .gitignore
└── README.md
```

> The exact folders and files may vary depending on the final project version.

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/AI-Loan-Prediction-System.git
```

### 2. Open the Project Folder

```bash
cd AI-Loan-Prediction-System
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

#### Windows

```powershell
venv\Scripts\activate
```

#### Linux/macOS

```bash
source venv/bin/activate
```

### 5. Install Required Packages

```bash
pip install -r requirements.txt
```

---

## 🗄️ Database Setup

Run Django migrations:

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```

---

## 🚀 Running the Project

Start the Django development server:

```bash
python manage.py runserver
```

Open the following address in your browser:

```text
http://127.0.0.1:8000/
```

The AI Loan Prediction System will then be available locally.

---

## 🧠 Model Training

If the project requires retraining the machine learning model, run:

```bash
python train_model.py
```

This generates/updates the trained model used by the Django application.

---

## 📊 Example Prediction

Example applicant information:

```text
Income: 50000
Loan Amount: 200000
Credit Score: 750
Employment Status: Employed
```

The system processes the information using the trained machine learning model and displays the corresponding loan prediction.

---



---

## 🔄 Application Workflow

```text
User
  ↓
Registration / Login
  ↓
Enter Loan Information
  ↓
Data Processing
  ↓
Machine Learning Model
  ↓
Loan Prediction
  ↓
Display Result
  ↓
Save Prediction History
```

---

## 🔒 Security

Sensitive information such as passwords, API keys, secret keys, and database credentials should not be committed to the GitHub repository.

Use environment variables for sensitive configuration when deploying the application.

---

## 🚀 Future Enhancements

* Deploy the application to a cloud platform.
* Add advanced machine learning models.
* Improve prediction accuracy.
* Add more financial features.
* Add interactive dashboards.
* Add loan risk classification.
* Add automated model retraining.
* Add REST API support.
* Improve UI/UX.
* Add cloud database integration.

---

## 👩‍💻 Author

**Prerana Pilare**

B.Tech Computer Science and Engineering

### Skills Demonstrated

* Python
* Machine Learning
* Data Analysis
* Django
* SQL
* Pandas
* NumPy
* Scikit-learn
* Git & GitHub

---

## ⭐ Project Highlights

This project demonstrates the practical implementation of:

**Machine Learning + Python + Data Analysis + Django + Database + Web Application**

It provides an end-to-end example of integrating a machine learning model into a web-based application.
