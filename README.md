# Single Layer Perceptron Classification for Salary Prediction

This project demonstrates a simple implementation of a **Single Layer Perceptron** model for classifying salary levels based on years of experience. The model classifies salary into three categories (`Low`, `Medium`, `High`) using **scikit-learn's Perceptron** classifier, and visualizes decision regions for the classification.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Project Overview

This project aims to classify salary categories based on years of experience using a **single-layer perceptron model**. It includes:
1. **Data preprocessing**: Cleaning and encoding categorical variables.
2. **Model training and evaluation**: Training a Perceptron classifier, evaluating its performance on training and testing datasets.
3. **Visualization**: Plotting the decision boundaries to understand the model’s classification regions.

## Dataset

The dataset (`salary_classification_data.csv`) consists of three main columns after preprocessing:
- `Years_of_Experience`: Numeric feature.
- `Salary`: Numeric feature.
- `Salary_Category`: Target variable, with three categories: Low, Medium, and High.

### Sample Data

| Years_of_Experience | Salary | Salary_Category |
|---------------------|--------|-----------------|
| 29                  | 96076  | High           |
| 1                   | 27140  | Low            |
| 5                   | 47757  | Low            |
| 16                  | 61882  | High           |

## Installation

To run this project, clone the repository and install the required libraries.

```bash
git clone https://github.com/thisissagarthapa/salary-perceptron-classification.git
cd salary-perceptron-classification
pip install -r requirements.txt
