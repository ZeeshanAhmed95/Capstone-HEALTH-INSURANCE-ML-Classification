# Health Insurance Cross-Sell Prediction

This project aims to predict whether a customer would be interested in purchasing vehicle insurance based on their demographics, insurance history, and vehicle information. The project uses machine learning classification techniques to achieve this goal.

## Table of Contents

1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Dataset](#dataset)
4. [Data Preprocessing](#data-preprocessing)
5. [Feature Engineering](#feature-engineering)
6. [Model Selection](#model-selection)
7. [Model Evaluation](#model-evaluation)
8. [Results](#results)
9. [Installation](#installation)
10. [Usage](#usage)
11. [Contributing](#contributing)
12. [License](#license)

## Introduction

The Health Insurance Cross-Sell Prediction project is designed to help insurance companies identify potential customers for vehicle insurance. By analyzing customer data, the model can predict whether a customer is likely to be interested in purchasing vehicle insurance, allowing the company to target their marketing efforts more effectively.

## Problem Statement

Insurance companies often struggle to identify potential customers for their vehicle insurance products. This project aims to build a machine learning model that can predict whether a customer is likely to be interested in purchasing vehicle insurance based on their demographics, insurance history, and vehicle information.

## Dataset

The dataset used in this project contains information about customers, including demographics, insurance history, and vehicle information. The dataset can be found in the `data` folder of the repository. The dataset contains the following features:

- id: Unique customer identifier
- Gender: Customer's gender (Male/Female)
- Age: Customer's age
- Driving_License: Whether the customer has a driving license (0: No, 1: Yes)
- Region_Code: Unique code for the region of the customer
- Previously_Insured: Whether the customer already has vehicle insurance (0: No, 1: Yes)
- Vehicle_Age: Age of the customer's vehicle
- Vehicle_Damage: Whether the customer's vehicle has been damaged in the past (0: No, 1: Yes)
- Annual_Premium: The amount the customer needs to pay as a premium in the year
- Policy_Sales_Channel: Anonymized code for the channel of outreaching to the customer
- Vintage: Number of days the customer has been associated with the company
- Response: Whether the customer is interested in vehicle insurance (0: No, 1: Yes)

## Data Preprocessing

The data preprocessing step involves cleaning the dataset, handling missing values, and converting categorical variables into numerical format. This step is crucial for preparing the data for machine learning algorithms.

## Feature Engineering

Feature engineering is the process of creating new features or modifying existing features to improve the performance of machine learning models. In this project, several new features are created, and existing features are transformed to better represent the underlying patterns in the data.

## Model Selection

Various machine learning classification models are trained and compared to select the best model for the task. The models considered include:

- Logistic Regression
- Decision Trees
- Random Forest
- XGBoost

## Model Evaluation

The performance of the selected model is evaluated using various metrics, such as accuracy, precision, recall, F1-score, and the area under the ROC curve (AUC-ROC). These metrics help to assess the model's ability to correctly predict customer interest in vehicle insurance.

## Results

The project provides a detailed analysis of the model's performance and insights into the most important features for predicting customer interest in vehicle insurance. The results section in the notebook offers visualizations and explanations to help understand the model's performance and the factors that influence customer interest in vehicle insurance.

## Installation

To set up the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required Python libraries:
   - NumPy
   - Pandas
   - Matplotlib
   - Scikit-learn
   - XGBoost
3. Open the Jupyter Notebook `Zeeshan_Classification_Capstone_of_FINAL_HEALTH_INSURANCE_CROSS_SELL_PREDICTION.ipynb` in your preferred Jupyter environment.

## Usage

To run the project, simply open the Jupyter Notebook and execute the cells in order. The notebook contains detailed explanations and visualizations to help you understand the data preprocessing, feature engineering, model selection, and evaluation steps.

## Contributing

If you'd like to contribute to this project, please feel free to submit a pull request or open an issue to discuss your ideas.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
