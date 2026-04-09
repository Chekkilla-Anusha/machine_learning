🚢 Titanic Survival Prediction using Decision Tree
📌 Project Overview

This project aims to predict whether a passenger survived the Titanic disaster using machine learning techniques. The model is built using the Decision Tree Classifier, based on passenger data such as age, gender, class, and other features.

📂 Dataset

The dataset used in this project is the famous Titanic dataset from Kaggle.

Features include:
PassengerId
Pclass (Ticket class)
Name
Sex
Age
SibSp (Number of siblings/spouses aboard)
Parch (Number of parents/children aboard)
Ticket
Fare
Cabin
Embarked
⚙️ Technologies Used
Python 🐍
Pandas
NumPy
Matplotlib / Seaborn
Scikit-learn
🔍 Project Workflow
Data Loading
Import dataset using Pandas
Data Preprocessing
Handle missing values
Convert categorical variables (e.g., Sex, Embarked) into numeric
Feature selection
Exploratory Data Analysis (EDA)
Visualize survival rates
Analyze relationships between features
Model Building
Train Decision Tree Classifier
Split data into training and testing sets
Model Evaluation
Accuracy score
Confusion matrix
Classification report
🌳 Model Used
Decision Tree Classifier
Easy to interpret
Handles both numerical and categorical data
📊 Results
Achieved good accuracy on test data
Key factors influencing survival:
Gender
Passenger class
Age
▶️ How to Run the Project
Clone the repository:
git clone https://github.com/your-username/titanic-survival-prediction.git
Install required libraries:
pip install -r requirements.txt
Run the notebook:
jupyter notebook DT_Titanic_Survival_Prediction.ipynb
📁 Project Structure
├── DT_Titanic_Survival_Prediction.ipynb
├── Titanic.csv
├── README.md
├── requirements.txt
💡 Future Improvements
Try other models (Random Forest, Logistic Regression)
Hyperparameter tuning
Deploy model using Flask/Streamlit
🙌 Acknowledgements
Kaggle for providing the dataset
Scikit-learn documentation