\# 🛠️ Predictive Maintenance System



An end-to-end Machine Learning project for predicting whether a CNC machine reading indicates an upcoming machine failure or no machine failure.



\## 🚀 Live Demo



https://predictive-maintenance-system-for-i-alpha.vercel.app/



\## 📌 Project Overview



This project builds a predictive maintenance system using machine sensor readings to classify whether a machine is likely to experience a failure.



The machine learning workflow includes:



\- Data loading

\- Data cleaning

\- Exploratory Data Analysis (EDA)

\- Feature selection

\- Model training

\- Model validation

\- Model comparison

\- Final model evaluation

\- Model saving and reloading

\- Prediction / inference



\## 🤖 Machine Learning



Three classification models were evaluated:



\- Logistic Regression

\- Linear SVM

\- Random Forest



The models use a common preprocessing pipeline including:



\- Missing-value imputation

\- Feature scaling

\- Categorical encoding



The best model is selected based on the validation F1-score.



\## 📊 Features



The project uses machine sensor readings such as:



\- Hydraulic Pressure

\- Coolant Pressure

\- Air System Pressure

\- Coolant Temperature

\- Hydraulic Oil Temperature

\- Spindle Bearing Temperature

\- Spindle Vibration

\- Tool Vibration

\- Spindle Speed

\- Voltage

\- Torque

\- Cutting Force



Feature selection is performed using Random Forest feature importance, and the top six most influential features are selected for the final models.



\## 📁 Project Structure



```text

predictive-maintenance-system/

│

├── Model/

│   ├── Machine\_Downtime\_Predictive\_Maintenance\_(4).ipynb

│   ├── machine\_downtime\_pipeline.pkl

│   └── machine\_downtime\_metadata.json

│

├── docs/

│   ├── Machine\_Downtime\_Prediction\_1.pptx

│   └── Links.txt

│

├── README.md

└── .gitignore

