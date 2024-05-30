# Machine Learning Homework for "Foundations of AI" Course

## Overview
This repository contains the implementation of various machine learning models as part of the Machine Learning Homework for the "Foundations of AI" course in the Bachelor's degree in Computer Engineering, taught by Prof. Silvestri. The goal of this homework is to apply different machine learning techniques to predict and classify obesity levels and the weight of individuals based on available attributes.

## Implemented Models
1. **Linear Regression**
   - **Purpose:** To predict the weight of individuals based on the available attributes.
   - **Details:** This model uses a linear approach to model the relationship between the input features and the target variable (weight).

2. **Decision Trees for Binary Classification**
   - **Purpose:** To classify individuals into two categories of obesity levels (NObesity attribute) based on the available attributes.
   - **Details:** This model uses a tree-like structure to make decisions and classify the input data into binary categories.

3. **Logistic Regression**
   - **Purpose:** To classify individuals into two categories of obesity levels (NObesity attribute).
   - **Details:** This model uses a logistic function to model the probability of the binary outcome and classify the input data accordingly.

4. **K-Nearest Neighbors (KNN)**
   - **Purpose:** To classify individuals into categories of obesity levels (NObesity attribute).
   - **Details:** This model classifies the input data based on the majority class among the k-nearest neighbors in the feature space.

5. **Neural Network**
   - **Purpose:** 
     - **Regression:** To predict the weight of individuals based on available attributes. 
     - **Binary Classification:** To classify individuals into two categories of obesity levels (NObesity attribute).
   - **Details:** This model is designed to be flexible, allowing for a variable number of layers and neurons per layer. Both the architecture (number of layers and neurons) and the traditional hyperparameters (learning rate, batch size, etc.) can be tuned.


## Getting Started
1. **Clone the repository:**
2. **Install requirements and run it**
   ```sh
   cd fondamenti_AI_Homework
   pip install -r requirements.txt
   jupyter notebook
   ```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Special thanks to [Prof. Silvestri](https://sites.google.com/diag.uniroma1.it/fabriziosilvestri/home) for the guidance and support throughout the course.
