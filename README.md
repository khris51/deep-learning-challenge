## deep-learning-challenge
# Overview
This project aims to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup, using features in the provided dataset.

# Description
Alphabet Soup’s business team provided a CSV containing data on more than 34,000 organizations that have received funding over the years.


## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)

- [Features](#features)
- [Tests](#tests)
- [Contact](#contact)
- [Summary](#summary)


# Installation
To run this project, you need the following Python libraries:

sklearn.model_selection for train-test splitting
sklearn.preprocessing for standard scaling
pandas for data manipulation
tensorflow for building the neural network
Results
Data Processing

# variable(s) 
The target variable is IS_SUCCESSFUL, which indicates whether an applicant was successful if funded by Alphabet Soup.
 # Model features 

The features for the model include:
APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE
ORGANIZATION
STATUS
INCOME_AMT
SPECIAL_CONSIDERATIONS
ASK_AMT (amount requested)

# Variables that should be removed 
EIN (Employer Identification Number, as it's a unique identifier)

# Neural Network Configuration:
Layers and Neurons:
First layer: 80 neurons
Second layer: 30 neurons
Output layer: 1 neuron
Activation Functions:
Hidden layers: ReLU (Rectified Linear Unit)
Output layer: Sigmoid (since this is a binary classification problem)
Performance:

# The target model performance

 was achieved with the configuration mentioned above.
Steps taken to improve model performance included hyperparameter tuning, experimenting with different numbers of neurons and layers, and adjusting learning rates.
![app_image](mockup.png)
![app_image](mockup2.png)
## Usage
This project can be used to predict the success of funding applicants for Alphabet Soup, providing valuable insights for decision-making in funding allocations.

## Credits
Project by Khristopher Prince

## Features
Binary Classification: Predicts the success of applicants.
Neural Network Model: Utilizes TensorFlow for deep learning.
Data Processing: Involves cleaning, transforming, and scaling data for optimal model performance.
## Summary
The project successfully develops a binary classifier to predict the success of applicants using historical funding data from Alphabet Soup. The model's performance meets the target requirements, and it can be a useful tool for the foundation's funding decisions.

## Contact
For questions or concerns, please reach out to:

GitHub: Khris51
Email: khris51@yahoo.com
