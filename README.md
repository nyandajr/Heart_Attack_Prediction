# Heart Attack Prediction

This project aims to predict the likelihood of a heart attack based on patient data using machine learning techniques. It includes data analysis, model development, and a Streamlit web application for interactive predictions.

## Overview

A heart attack, also known as a myocardial infarction, occurs when a part of the heart muscle doesn't receive enough blood flow. Timely diagnosis and treatment are crucial for minimizing damage and improving patient outcomes. This project explores various factors such as age, sex, blood pressure, cholesterol levels, and other medical indicators to predict the risk of a heart attack.

## Contents

1. [Introduction](#introduction)
2. [Objective](#objective)
3. [Data Description](#data-description)
4. [Methodology](#methodology)
5. [Results](#results)
6. [Streamlit App](#streamlit-app)
7. [Repository Structure](#repository-structure)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

Heart attacks are a leading cause of death worldwide, and early prediction can significantly improve patient outcomes. This project aims to develop a predictive model using machine learning algorithms to assess the risk of a heart attack based on various patient attributes.

## Objective

The primary objectives of this project are:
- Perform exploratory data analysis (EDA) to gain insights into the dataset.
- Develop and train machine learning models to predict the likelihood of a heart attack.
- Create an interactive web application using Streamlit for users to input data and receive predictions.
- Evaluate model performance and fine-tune for optimal results.

## Data Description

The dataset used in this project contains various patient attributes such as age, sex, chest pain type, blood pressure, cholesterol levels, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, etc. The target variable indicates the likelihood of a heart attack (0 for less chance, 1 for more chance).

## Methodology

The methodology involves:
- Data preprocessing: Handling missing values, encoding categorical variables, and scaling numeric features.
- Model development: Training machine learning models (logistic regression) on the preprocessed data.
- Streamlit app development: Creating an interactive web application for users to input data and receive predictions.
- Evaluation: Assessing model performance using metrics such as accuracy, precision, recall, and ROC curves.

## Results

The logistic regression model achieved an accuracy of 90% on the test data. 
