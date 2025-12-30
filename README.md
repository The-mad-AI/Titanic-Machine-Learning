Titanic: Machine Learning from Disaster 🚢
PythonPandasKaggle

This project aims to analyze the Titanic dataset and predict which passengers survived the tragedy using Machine Learning algorithms.

📋 Overview
The sinking of the Titanic is one of the most infamous shipwrecks in history. In this project, I applied data analysis and machine learning techniques to predict survival rates based on passenger features like class, age, and gender.

🔍 Methodology
Data Cleaning: Handled missing values in Age, Cabin, and Fare using median and mode imputation.
Exploratory Data Analysis (EDA): Visualized survival rates using Seaborn and Matplotlib to identify key factors.
Feature Engineering:
Created Title feature from names.
Binned Age and Fare into categorical groups.
Extracted CabinDeck and created IsAlone feature.
Modeling & Evaluation:
Trained KNN, Decision Tree, Random Forest, and Logistic Regression models.
Used 10-Fold Cross-Validation to ensure robust results.
🏆 Results
Best Model: Logistic Regression (due to high stability).
Kaggle Public Score: 0.78468
🛠️ Technologies Used
Python
Pandas & NumPy
Matplotlib & Seaborn
Scikit-Learn
🚀 How to Run
Clone the repository:
git clone https://github.com/The-mad-AI/Titanic-Machine-Learning.git
Install dependencies:
bash

pip install -r requirements.txt
Open the Jupyter Notebook and run the cells.
📈 Future Improvements
Hyperparameter tuning using GridSearchCV.
Ensembling models (XGBoost, LightGBM) to improve accuracy.
Developed with ❤️ by [Seyed_Qasem_Hosseini]


