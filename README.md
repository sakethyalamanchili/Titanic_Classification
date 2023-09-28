# Titanic Survival Prediction

![Titanic Image](https://github.com/sakethyalamanchili/Titanic_Classification/assets/129929887/e41402d6-f517-427a-9749-af54c33671ba) <!-- You can replace this with an image related to the Titanic or your project -->

## Overview

This project is a data analysis and prediction model for the Titanic dataset. It aims to predict whether a passenger on the Titanic would have survived or not based on various features such as passenger class, gender, age, and more. The project uses machine learning techniques, specifically logistic regression, for prediction.

## Data Source

The dataset used for this project is the famous Titanic dataset, which contains information about passengers who were aboard the RMS Titanic during its maiden voyage, including whether they survived or not.

- **Dataset Source**: [Kaggle Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic](https://www.kaggle.com/competitions/titanic/data?select=train.csv))

## Project Structure

The project is organized as follows:

- **Dependencies**: In this section of the code, we import all the necessary libraries and frameworks, including pandas, numpy, matplotlib, seaborn, and scikit-learn.

- **Data Collection and Processing**: Here, we load the Titanic dataset, perform data cleaning, handle missing values, and prepare the data for analysis.

- **Data Analysis**: This section provides insights into the dataset, including statistical measures, counts of survivors, gender distribution, passenger class distribution, and more.

- **Data Visualization**: The data is visualized using Seaborn to create count plots for various features like survival status, gender, passenger class, and more.

- **Encoding Categorical Columns**: Categorical columns like 'Sex' and 'Embarked' are encoded to convert them into numerical format for machine learning model training.

- **Model Training**: The machine learning model (Logistic Regression) is trained using the preprocessed data.

- **Model Evaluation**: The accuracy of the model is evaluated on both the training and testing datasets.

## Results

The logistic regression model achieved an accuracy of approximately 80.76% on the training data and 78.21% on the testing data.

## Acknowledgments

- Kaggle for providing the Titanic dataset for analysis and prediction.
- Siddhardhan's YouTube channel, [Link to the Channel](https://www.youtube.com/watch?v=Lgp14y9-U74), for valuable guidance and tutorials during the project.

