# Customer Churn Prediction

An end-to-end Machine Learning project to predict customer churn using customer demographics, service subscriptions, contract details, and billing information.

## 🎯 Project Objective

The goal is to identify customers who are likely to leave a telecom service provider. The project focuses on exploring customer data, developing and evaluating machine learning models, and building a usable application around the final model.

## 📊 Dataset

- **Dataset:** IBM Telco Customer Churn
- **Records:** 7,043 customers
- **Features:** 20 input columns, including customer information, services, and billing details
- **Target:** `Churn` (`Yes` / `No`)

## 🛠️ Tech Stack

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook
- FastAPI
- Streamlit
- Pytest

*Technologies will be used as the project progresses.*

## 📁 Project Structure

```text
customer-churn-prediction/
├── data/
│   ├── raw/
│   └── processed/
├── notebook/
├── src/
├── artifacts/
├── api/
├── app/
├── test/
├── reports/
├── README.md
└── .gitignore
```

## 🚧 Project Status

**In Progress**

Current work:

- [x] Project structure setup
- [x] Dataset downloaded
- [x] Initial data exploration
- [x] Identified and investigated blank values in `TotalCharges`
- [ ] Exploratory Data Analysis (EDA)
- [ ] Data preprocessing and feature engineering
- [ ] Model training and comparison
- [ ] Model evaluation and threshold selection
- [ ] Reusable ML pipeline
- [ ] FastAPI backend
- [ ] Streamlit interface
- [ ] Testing and deployment

## 🚀 Planned Features

- Analyze patterns associated with customer churn
- Compare multiple machine learning algorithms
- Evaluate models using suitable classification metrics
- Build a reusable prediction pipeline
- Expose predictions through a FastAPI backend
- Develop an interactive Streamlit application
- Add tests and deployment instructions

## ⚙️ Setup

The installation and usage instructions will be added after the project pipeline and application are developed.

## 📌 Learning Goals

This project is being developed step by step to gain practical experience in data analysis, machine learning, model evaluation, software engineering, API development, and deployment.

## 📄 License

A license will be added if and when appropriate.
