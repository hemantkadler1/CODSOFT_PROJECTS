#CODSOFT DATA SCIENCE INTERNSHIP
TASK1:TITANIC SURVIVAL PREDICTION

Project Overview:
This repository contains a machine learning project aimed at predicting the survival of passengers aboard the Titanic based on various features such as age, gender, passenger class, and more. The Titanic dataset is a classic beginner-friendly dataset, widely used for understanding data preprocessing, feature engineering, and classification algorithms in data science.

Dataset:
The dataset used in this project comes from the Kaggle Titanic - Machine Learning from Disaster competition. It includes information on 891 passengers, with the following key features:

PassengerId: Unique identifier for each passenger
Survived: Target variable indicating survival (0 = No, 1 = Yes)
Pclass: Ticket class (1 = First, 2 = Second, 3 = Third)
Name: Name of the passenger
Sex: Gender
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Ticket: Ticket number
Fare: Ticket fare
Cabin: Cabin number (mostly missing)
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
Project Workflow
Data Exploration:

Analyzed the data to understand the distribution of different features.
Visualized survival rates across gender, passenger class, and age using seaborn and matplotlib.
Data Preprocessing:

Handled missing values in columns like Age and Embarked.
Dropped the Cabin column due to a high percentage of missing data.
Encoded categorical variables (Sex and Embarked) for model input.
Exploratory Data Analysis (EDA):

Examined the survival rate based on gender, showing females had a higher survival chance.
Analyzed survival by passenger class, indicating first-class passengers had a better survival rate.
Visualized the age distribution, noting that younger passengers had higher survival rates.
Feature Engineering:

Created new features, such as FamilySize (SibSp + Parch + 1).
Further analysis of family size and its impact on survival rates.
Model Building:

Used a Random Forest Classifier for predicting survival.
Evaluated the model with accuracy score, confusion matrix, and classification report.
Results
The model achieved a satisfactory accuracy in predicting the survival of passengers.
Gender and passenger class were found to be the most significant predictors of survival.
Technologies Used
Python: Core language for data analysis and model building
Pandas & NumPy: Data manipulation
Matplotlib & Seaborn: Data visualization
Scikit-learn: Machine learning model development

How to Run the Project:
Clone the repository:
git clone https://github.com/yourusername/Titanic-Survival-Prediction.git
Navigate to the project directory:
cd Titanic-Survival-Prediction
Install the required libraries:
pip install -r requirements.txt
Run the Jupyter Notebook or Python script:
jupyter notebook Titanic_Survival_Prediction.ipynb
Conclusion
The Titanic Survival Prediction project offers valuable insights into feature analysis and model building for classification problems. It serves as an excellent learning experience for beginners in data science and machine learning, showcasing the importance of data preprocessing, exploratory analysis, and model evaluation.

Contributing
Feel free to fork this repository, make improvements, and submit a pull request. Your contributions are welcome!


