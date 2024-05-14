# Heart Disease Prediction

## Introduction
This project aims to predict whether a person is suffering from heart disease using machine learning techniques. The dataset used for this project is obtained from Kaggle ([link](https://www.kaggle.com/ronitf/heart-disease-uci)).

## Requirements
- Python 3.x
- Libraries: numpy, pandas, matplotlib, scikit-learn

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/heart-disease-prediction.git

Install the required libraries
pip install -r requirements.txt
## Usage
1.Run the heart_disease_prediction.ipynb notebook using Jupyter or any other compatible environment.
2.Follow the instructions in the notebook to execute each cell and observe the results.
3.The notebook contains detailed explanations and code comments to guide you through the project.
## Contents
heart_disease_prediction.ipynb: Jupyter notebook containing the machine learning project code.
dataset.csv: Dataset file containing the heart disease data.
## Methodology
1.Importing Libraries: Necessary libraries including numpy, pandas, matplotlib, and scikit-learn are imported.

2.Data Import: The dataset is loaded using pandas' read_csv() method.

3.Data Exploration: Various exploratory data analysis techniques are employed to understand the dataset.

4.Data Preprocessing: Data is preprocessed by handling missing values, encoding categorical variables, and scaling features.

5.Model Building: Several machine learning algorithms including K Neighbors Classifier, Support Vector Classifier, Decision Tree.

6.Classifier, and Random Forest Classifier are applied to build predictive models.

7.Model Evaluation: The models are evaluated using appropriate metrics and their performance is analyzed.

## conclusion
In this project, we utilized machine learning techniques to predict whether a person is suffering from heart disease. After thorough data analysis and preprocessing, we applied four different machine learning algorithms: K Neighbors Classifier, Support Vector Classifier, Decision Tree Classifier, and Random Forest Classifier.

The highest accuracy achieved was 87% using the K Neighbors Classifier with 8 nearest neighbors. Additionally, the Random Forest Classifier also performed well, achieving an accuracy of 84% with 100 or 500 estimators.

Overall, the project demonstrated the effectiveness of machine learning in diagnosing heart disease based on patient data. Further improvements and fine-tuning of the models could potentially enhance the accuracy even more. This project serves as a valuable step towards developing predictive tools for healthcare professionals to assist in diagnosing heart-related conditions.
