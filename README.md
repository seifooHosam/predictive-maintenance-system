# 🛠️ Predictive Maintenance System

An end-to-end Machine Learning project for predicting whether a CNC machine is likely to experience a failure based on sensor readings.

## 🚀 Live Demo

[Try the Live Demo](https://predictive-maintenance-system-for-i-alpha.vercel.app/)

## 📌 Project Overview

This project builds a Predictive Maintenance System that analyzes machine sensor readings and predicts whether a machine is likely to experience a failure.

The machine learning workflow includes:

- Data loading
- Data cleaning
- Exploratory Data Analysis (EDA)
- Feature selection
- Model training
- Model validation
- Model comparison
- Final model evaluation
- Model saving and reloading
- Prediction and inference

## 🤖 Machine Learning

Three classification models were evaluated:

- Logistic Regression
- Linear SVM
- Random Forest

The models use a common preprocessing pipeline including:

- Missing-value imputation
- Feature scaling
- Categorical encoding

The best model is selected based on the validation F1-score.

## 📊 Features

The project uses machine sensor readings such as:

- Hydraulic Pressure
- Coolant Pressure
- Air System Pressure
- Coolant Temperature
- Hydraulic Oil Temperature
- Spindle Bearing Temperature
- Spindle Vibration
- Tool Vibration
- Spindle Speed
- Voltage
- Torque
- Cutting Force

Feature selection is performed using Random Forest feature importance, and the top six most influential features are selected for the final models.

## 📁 Project Structure

```text
predictive-maintenance-system/
│
├── Model/
│   ├── Machine_Downtime_Predictive_Maintenance_(4).ipynb
│   ├── machine_downtime_pipeline.pkl
│   └── machine_downtime_metadata.json
│
├── docs/
│   ├── Machine_Downtime_Prediction_1.pptx
│   └── Links.txt
│
├── README.md
└── .gitignore

## 🧰 Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Gradio
- Jupyter Notebook

## 💾 Saved Model

The trained machine learning pipeline is stored in:

`Model/machine_downtime_pipeline.pkl`

Model metadata is stored in:

`Model/machine_downtime_metadata.json`

## 🔮 Prediction Output

The system provides:

- Machine failure prediction
- Failure probability
- Prediction confidence
- Manual review indication

## 📚 Documentation

Additional project documentation and presentation files are available in the `docs/` directory.

## 👨‍💻 Project

**Predictive Maintenance System**

Machine Learning project focused on machine failure detection using sensor data.