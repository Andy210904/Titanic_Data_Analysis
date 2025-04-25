# Titanic Survival Prediction

## Task Objective

The goal of this project is to build a machine learning classification model that predicts whether a passenger survived the Titanic disaster, based on various features such as age, gender, ticket class, fare, and more.

##  Dataset

The dataset includes the following features:

- PassengerId  
- Pclass  
- Name  
- Sex  
- Age  
- SibSp  
- Parch  
- Ticket  
- Fare  
- Cabin  
- Embarked  
- Survived (target variable)

## Features of the Project

- Handled missing values (e.g., Age, Cabin, Embarked).
- Categorical variables encoded using one-hot or label encoding.
- Numerical features normalized where needed.
- Multiple models tested: Logistic Regression, Random Forest, SVM, etc.
- Evaluated using accuracy, precision, recall, F1-score.

## How to Run

1. **Clone the repository**
   git clone https://github.com/your-username/titanic-survival-prediction.git
   cd titanic-survival-prediction

2. **Install dependencies**
It’s recommended to use a virtual environment or Conda. Then run:
pip install -r requirements.txt

3. **Launch Jupyter Notebook**
jupyter notebook

4. **Saving the dataset**
Save the dataset in the same location where the .ipynb file is or if using collab then upload it in the files section

5. **Open and run the notebook**
Open titanic_model_training.ipynb
Run all the cells sequentially to view preprocessing, training, evaluation, and visualization steps.
