# Titanic Survival Prediction 🚢

## Project Overview

This project predicts whether a passenger survived the Titanic disaster using machine learning.
The model analyzes passenger features like age, gender, ticket fare, and passenger class to predict survival.

## Dataset

The dataset used is the Titanic dataset from Kaggle.
It contains information about passengers such as:

* Passenger Class (Pclass)
* Sex
* Age
* Fare
* Number of Siblings/Spouses
* Number of Parents/Children
* Embarked Port

Target variable:

* **Survived** (0 = No, 1 = Yes)

## Data Preprocessing

The following steps were performed:

* Filled missing values in **Age** using mean
* Filled missing values in **Embarked** using mode
* Converted categorical variables to numerical values
* Split data into training and testing sets

## Machine Learning Models

Models used in this project:

* Decision Tree Classifier
* Random Forest Classifier

## Results

Random Forest performed better with higher prediction accuracy.

## Project Files

* `titanic_analysis.ipynb` → Jupyter notebook containing the full code
* `titanic_portfolio.pdf` → Project report
* `train.csv` → Dataset

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Conclusion

This project demonstrates the full machine learning workflow including data preprocessing, model training, and evaluation.
