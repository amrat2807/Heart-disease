# Heart Disease Prediction Using Machine Learning

## Overview

This project focuses on predicting the likelihood of heart disease using machine learning techniques. The dataset used includes various medical features that are known to impact heart health. Our goal is to build a model that can accurately predict the presence or absence of heart disease based on these features.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Heart disease remains one of the leading causes of death worldwide. Early detection and prediction can significantly improve outcomes. This project aims to leverage machine learning algorithms to predict heart disease based on historical patient data.

## Dataset

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets) and contains the following attributes:

- **Age**: Age of the patient
- **Sex**: Gender of the patient (0 = female, 1 = male)
- **Chest Pain Type**: Type of chest pain experienced
- **Resting Blood Pressure**: Blood pressure at rest
- **Cholesterol**: Serum cholesterol level
- **Fasting Blood Sugar**: Fasting blood sugar level (1 = greater than 120 mg/dl, 0 = less than 120 mg/dl)
- **Resting Electrocardiographic Results**: Electrocardiogram results
- **Maximum Heart Rate Achieved**: Maximum heart rate achieved
- **Exercise Induced Angina**: Presence of exercise induced angina (1 = yes, 0 = no)
- **Oldpeak**: Depression induced by exercise relative to rest
- **Slope of Peak Exercise ST Segment**: Slope of the peak exercise ST segment
- **Number of Major Vessels**: Number of major vessels colored by fluoroscopy
- **Thalassemia**: Thalassemia (1 = normal, 2 = fixed defect, 3 = reversible defect)

## Features

- **Data Preprocessing**: Cleaning and normalization of data
- **Exploratory Data Analysis (EDA)**: Statistical and visual analysis of the data
- **Feature Selection**: Identifying relevant features for model training
- **Model Training**: Training various machine learning models
- **Evaluation**: Assessing model performance using metrics like accuracy, precision, recall, and F1 score

## Installation

To run this project locally, you will need Python 3.x and several libraries. You can install the necessary libraries using pip:

```bash
pip install -r requirements.txt
