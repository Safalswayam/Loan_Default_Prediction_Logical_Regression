# Loan_Default_Prediction_Logical_Regression
🏦 Loan Default Prediction using Machine Learning
📌 Overview
This project predicts whether a borrower will default on a loan using real-world financial and demographic data from the LendingClub loan dataset (2007–2018). It demonstrates how logistic regression and basic data preprocessing techniques can be applied for binary classification tasks in the finance domain.

🎯 Objective
To develop a machine learning model that classifies loan applications as:

Default (1): The borrower fails to repay the loan.

No Default (0): The borrower successfully repays the loan.

📁 Dataset
Source: LendingClub

File Used: accepted_2007_to_2018Q4.xlsx

Target Column: loan_status → Converted to binary (loan_default)

Features Used:

loan_amnt

term

int_rate

emp_length

home_ownership

annual_inc

purpose

dti

🛠️ Technologies Used
Python

Pandas & NumPy

Scikit-learn

Logistic Regression

Jupyter Notebook

⚙️ Workflow
Data Cleaning: Handle missing values, filter relevant loan statuses.

Feature Engineering: Encode categorical variables, extract numeric values from text.

Train/Test Split: 80% training, 20% testing.

Modeling: Logistic Regression to predict loan defaults.

Evaluation: Accuracy, Confusion Matrix, Classification Report.

📊 Model Performance
Metrics like precision, recall, F1-score, and accuracy are calculated to evaluate the model. Logistic Regression provides an interpretable and fast baseline.

🧪 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Safalswayame/Loan_Default_Prediction_Logical_Regression.git
cd Loan_Default_Prediction_Logical_Regression
Place the dataset (accepted_2007_to_2018Q4.xlsx) in the project folder.

Open and run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook LendingClub_Loan_Default_Prediction.ipynb
📌 Future Improvements
Try advanced models: Random Forest, XGBoost

Hyperparameter tuning

Use NLP on text columns (e.g., title, description)

Integrate into a web dashboard

🧑‍💻 Author
Safal Swayam
Aspiring Data Analyst & AI Enthusiast
