# DocAssist-Building-Intelligent-Medical-Decision-Support-System
## Introduction
This project aims to develop an intelligent medical decision support system leveraging machine learning and data analysis techniques. 
The system analyzes patient data to assist doctors in making informed treatment decisions tailored to individual patients.

## Problem Statement
The healthcare industry faces the challenge of efficiently analyzing vast amounts of patient data to determine the most effective treatment options.
Traditional methods often rely on manual analysis, which can be time-consuming and prone to errors.
Therefore, there is a need for an intelligent system that can automate this process and provide personalized treatment recommendations based on various patient factors.

## Project Overview

1. Exploratory Data Analysis (EDA)
Load dataset from Amazon S3.
Perform initial exploration of the data.

3. Data Preprocessing
Handle missing values.
Perform feature engineering.
Encode categorical variables using one-hot encoding.

4. Data Visualization
Plot histograms to visualize the distribution of numerical features.
Generate a correlation matrix to examine relationships between variables.
Calculate skewness and kurtosis of features to understand their distribution characteristics.

5. Model Training and Evaluation
Split the dataset into training, testing, and validation sets.
Train machine learning models using Amazon SageMaker.
Evaluate model performance using classification metrics such as accuracy, precision, recall, and F1 score.

## Technologies Used
Amazon web services (Amazon SageMaker)

## Getting Started

## To run the code in this project, follow these steps:

1. Clone the repository: git clone <repository-url>
2. Install the necessary dependencies: pip install -r requirements.txt
3. Set up an AWS account and configure Amazon SageMaker.
4. Update the S3 bucket and file paths in the code to point to your dataset.
5. Execute the Jupyter Notebooks or Python scripts to preprocess the data, train the models, and evaluate their performance.

## Conclusion
In conclusion, this project demonstrates the end-to-end process of building a machine learning model using Amazon SageMaker,
from data preprocessing and exploratory analysis to model training, evaluation, and deployment.

For more detailed information, refer to the Jupyter Notebook in this repository.

### Requirements
1. Python 3
2. Amazon SageMaker
3. pandas
4. numpy
5. boto3
6. sagemaker
7. scikit-learn
8. matplotlib
9. seaborn
