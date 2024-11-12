# Electricity Theft Detection Using Machine Learning

This project aims to detect electricity theft based on consumption patterns using machine learning models. The dataset is sourced from Smart Grid Corporation China, and various models have been tested to find the most accurate and efficient approach. The 1D CNN model provided the best results in terms of accuracy and performance.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models Tested](#models-tested)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

Electricity theft is a significant issue that leads to energy losses and affects utility companies' operations and profitability. This project leverages machine learning to detect patterns in electricity consumption that may indicate theft. Multiple models were tested to determine the most effective approach, with 1D CNN yielding the highest accuracy.

## Dataset

The dataset for this project is provided by **Smart Grid Corporation China**. It contains consumption data and features relevant to identifying irregular usage patterns that may signify theft.

## Models Tested

The following models were implemented and tested to compare their effectiveness:

- **Artificial Neural Network (ANN)**
- **1D Convolutional Neural Network (1D CNN)**
- **2D Convolutional Neural Network (2D CNN)**
- **Random Forest (RF)**
- **Decision Tree (DT)**
- **Support Vector Machine (SVM)**
- **XGBoost**

After testing and comparing each model, **1D CNN** was found to deliver the best results in terms of both accuracy and computational efficiency.

## Results

The 1D CNN model demonstrated the highest accuracy and efficiency among all tested models, making it the most suitable for this application. It effectively detects patterns in consumption data that are indicative of theft, providing utility companies with a valuable tool to mitigate losses and enhance security.

## Installation

### Requirements

- Python 3.x
- Jupyter Notebook or any preferred IDE
- run the codes cellwise

## Usage

1. **Load the Dataset**: Import the dataset from Smart Grid Corporation China into the working directory.
2. **Run Model Comparisons**: Execute the notebook or script to train and test each model on the dataset.
3. **Evaluate Results**: Compare the accuracy and performance of each model to verify the effectiveness of the 1D CNN model.




