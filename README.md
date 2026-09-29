<div align="center">
💳 Credit Score Classification
Machine Learning Based Credit Score Prediction
<p> <b>Predicting customer credit scores using financial, banking, and credit-related information.</b> </p> <br> <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Machine%20Learning-Classification-orange?style=for-the-badge" alt="Machine Learning"> <img src="https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit Learn"> <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"> <img src="https://img.shields.io/badge/License-CC0-green?style=for-the-badge" alt="License"> </div>
📌 About The Project

Credit scoring plays an important role in the financial industry. It helps financial institutions understand a customer's credit profile and make informed decisions.

This project focuses on developing a Machine Learning classification system that predicts a customer's credit score based on their financial, banking, and credit-related information.

The model classifies customers into three categories:

<div align="center">
🟢 Good	🟡 Standard	🔴 Poor
Good Credit Profile	Standard Credit Profile	Poor Credit Profile
</div>

The project covers the complete Machine Learning workflow, from data preprocessing and exploratory analysis to model training, evaluation, and prediction.

🎯 Problem Statement

A global finance company has collected a large amount of customer banking and credit-related information.

The objective is to build an intelligent system that can automatically classify customers into different credit score brackets, reducing the manual effort required for credit assessment.

Task

Given a person's credit-related information, build a Machine Learning model that can classify their credit score.

🚀 Project Objectives
<table> <tr> <th>#</th> <th>Objective</th> </tr> <tr> <td align="center">01</td> <td>Analyze customer financial and credit-related information.</td> </tr> <tr> <td align="center">02</td> <td>Clean and preprocess the raw dataset.</td> </tr> <tr> <td align="center">03</td> <td>Perform Exploratory Data Analysis (EDA).</td> </tr> <tr> <td align="center">04</td> <td>Perform feature engineering and selection.</td> </tr> <tr> <td align="center">05</td> <td>Train Machine Learning classification models.</td> </tr> <tr> <td align="center">06</td> <td>Evaluate model performance using suitable metrics.</td> </tr> <tr> <td align="center">07</td> <td>Predict the credit score category of customers.</td> </tr> </table>
📊 Dataset

The dataset contains customer-level information related to personal details, banking activities, income, loans, credit history, and payment behaviour.

📁 Dataset Files
data/
├── train.csv
└── test.csv


The dataset contains 55 columns.

🔑 Important Features
<table> <tr> <th>Feature</th> <th>Description</th> </tr> <tr> <td><code>ID</code></td> <td>Unique identification of an entry.</td> </tr> <tr> <td><code>Customer_ID</code></td> <td>Unique identification of a customer.</td> </tr> <tr> <td><code>Month</code></td> <td>Month associated with the customer's record.</td> </tr> <tr> <td><code>Name</code></td> <td>Name of the customer.</td> </tr> <tr> <td><code>Age</code></td> <td>Age of the customer.</td> </tr> <tr> <td><code>Occupation</code></td> <td>Occupation of the customer.</td> </tr> <tr> <td><code>Annual_Income</code></td> <td>Annual income of the customer.</td> </tr> <tr> <td><code>Monthly_Inhand_Salary</code></td> <td>Monthly base salary of the customer.</td> </tr> <tr> <td><code>Num_Bank_Accounts</code></td> <td>Number of bank accounts held by the customer.</td> </tr> <tr> <td><code>Credit_Score</code></td> <td>Target variable representing the customer's credit score.</td> </tr> </table>
🎯 Target Variable

The target variable is:

<div align="center">
Credit_Score
<table> <tr> <th>Category</th> <th>Description</th> </tr> <tr> <td>🟢 <b>Good</b></td> <td>Good credit profile</td> </tr> <tr> <td>🟡 <b>Standard</b></td> <td>Standard credit profile</td> </tr> <tr> <td>🔴 <b>Poor</b></td> <td>Poor credit profile</td> </tr> </table> </div>
🧹 Data Preprocessing

The dataset contains several real-world data quality issues. Therefore, data preprocessing is an important part of this project.

The preprocessing steps include:

<ul> <li>Handling missing values</li> <li>Removing duplicate records</li> <li>Cleaning inconsistent values</li> <li>Correcting incorrect data types</li> <li>Handling invalid entries</li> <li>Detecting and handling outliers</li> <li>Encoding categorical variables</li> <li>Feature scaling where required</li> <li>Feature selection</li> </ul>
🔍 Exploratory Data Analysis

Exploratory Data Analysis is performed to understand the patterns, distributions, and relationships within the dataset.

Analysis Includes
<table> <tr> <td align="center">📊<br><b>Credit Score Distribution</b></td> <td align="center">💰<br><b>Income Analysis</b></td> <td align="center">👤<br><b>Age Analysis</b></td> </tr> <tr> <td align="center">💼<br><b>Occupation Analysis</b></td> <td align="center">💳<br><b>Credit Card Analysis</b></td> <td align="center">🏦<br><b>Bank Account Analysis</b></td> </tr> <tr> <td align="center">💸<br><b>Loan Analysis</b></td> <td align="center">📉<br><b>Outstanding Debt</b></td> <td align="center">💰<br><b>Payment Behaviour</b></td> </tr> <tr> <td align="center">⏰<br><b>Delayed Payments</b></td> <td align="center">📈<br><b>Correlation Analysis</b></td> <td align="center">📦<br><b>Feature Distribution</b></td> </tr> </table>
🤖 Machine Learning

This project is a Multi-Class Classification problem.

The model predicts one of the following credit score categories:

<div align="center">

Good    Standard    Poor

</div>
🔬 Algorithms

The project can use and compare different classification algorithms:

<table> <tr> <th>Algorithm</th> <th>Type</th> </tr> <tr> <td>Logistic Regression</td> <td>Linear Classification</td> </tr> <tr> <td>Decision Tree</td> <td>Tree-Based Learning</td> </tr> <tr> <td>Random Forest</td> <td>Ensemble Learning</td> </tr> <tr> <td>XGBoost</td> <td>Gradient Boosting</td> </tr> <tr> <td>Support Vector Machine</td> <td>Kernel-Based Classification</td> </tr> </table>
📈 Model Evaluation

The trained models can be evaluated using the following classification metrics:

<table> <tr> <th>Metric</th> <th>Purpose</th> </tr> <tr> <td><b>Accuracy</b></td> <td>Measures the overall percentage of correct predictions.</td> </tr> <tr> <td><b>Precision</b></td> <td>Measures the correctness of positive predictions.</td> </tr> <tr> <td><b>Recall</b></td> <td>Measures how effectively the model identifies each class.</td> </tr> <tr> <td><b>F1-Score</b></td> <td>Provides a balance between precision and recall.</td> </tr> <tr> <td><b>Confusion Matrix</b></td> <td>Shows detailed classification performance across classes.</td> </tr> </table>
🔄 Project Workflow
<div align="center"> <table> <tr> <td align="center"> <h3>1️⃣ Dataset</h3> 📂<br> <b>Data Collection</b> </td> </tr> <tr> <td align="center">⬇️</td> </tr> <tr> <td align="center"> <h3>2️⃣ Data Cleaning</h3> 🧹<br> <b>Missing Values & Inconsistent Data</b> </td> </tr> <tr> <td align="center">⬇️</td> </tr> <tr> <td align="center"> <h3>3️⃣ Exploratory Data Analysis</h3> 🔍<br> <b>Understanding Patterns & Relationships</b> </td> </tr> <tr> <td align="center">⬇️</td> </tr> <tr> <td align="center"> <h3>4️⃣ Feature Engineering</h3> ⚙️<br> <b>Feature Selection & Transformation</b> </td> </tr> <tr> <td align="center">⬇️</td> </tr> <tr> <td align="center"> <h3>5️⃣ Encoding & Scaling</h3> 🔢<br> <b>Data Transformation</b> </td> </tr> <tr> <td align="center">⬇️</td> </tr> <tr> <td align="center"> <h3>6️⃣ Model Training</h3> 🤖<br> <b>Machine Learning Models</b> </td> </tr> <tr> <td align="center">⬇️</td> </tr> <tr> <td align="center"> <h3>7️⃣ Model Evaluation</h3> 📊<br> <b>Performance Analysis</b> </td> </tr> <tr> <td align="center">⬇️</td> </tr> <tr> <td align="center"> <h3>8️⃣ Credit Prediction</h3> 🎯<br> <b>Good • Standard • Poor</b> </td> </tr> </table> </div>
🛠️ Technologies & Tools
<div align="center"> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"> <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" alt="Matplotlib"> <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square" alt="Seaborn"> <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="Scikit Learn"> <img src="https://img.shields.io/badge/XGBoost-EC0000?style=flat-square" alt="XGBoost"> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"> </div>
📁 Project Structure
Credit-Score-Classification/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── credit_score_classification.ipynb
│
├── models/
│   └── model files
│
├── requirements.txt
├── README.md
└── .gitignore

📚 Dataset Source
<div align="center"> <h3>Credit Score Classification</h3> <a href="https://www.kaggle.com/datasets/parisrohan/credit-score-classification"> <img src="https://img.shields.io/badge/Kaggle-Dataset-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle Dataset"> </a>

<br><br>

<b>License:</b> CC0: Public Domain

</div>
💡 Key Learning Outcomes

Through this project, we gain practical experience in:

<table> <tr> <td>🧹 Real-world Data Cleaning</td> <td>🔍 Exploratory Data Analysis</td> </tr> <tr> <td>⚙️ Feature Engineering</td> <td>🔢 Data Transformation</td> </tr> <tr> <td>🤖 Machine Learning Classification</td> <td>📊 Model Evaluation</td> </tr> <tr> <td>💰 Financial Data Analysis</td> <td>🎯 Credit Score Prediction</td> </tr> </table>
🔮 Future Improvements
<ul> <li>Hyperparameter tuning</li> <li>Cross-validation</li> <li>Advanced feature selection</li> <li>Ensemble learning</li> <li>SHAP-based model explainability</li> <li>Model deployment using Flask</li> <li>Interactive dashboard using Streamlit</li> <li>Real-time credit score prediction</li> </ul>
👨‍💻 Authors
<div align="center"> <table> <tr> <td align="center"> <b>Diganta Mandal</b> </td> <td align="center"> <b>Pritish Manna</b> </td> <td align="center"> <b>Arshad Arman</b> </td> <td align="center"> <b>Partha Sarothi Roy</b> </td> </tr> </table> </div>
<div align="center"> <h3>⭐ If you found this project useful, consider giving it a star!</h3> <br> <p> <b>Credit Score Classification</b> <br> Machine Learning • Finance • Data Science </p> </div>
