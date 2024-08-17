# Admission Prediction Model 🎓

This repository contains a machine learning model designed to predict the likelihood of admission for students applying to graduate programs. The model is built using multiple regression algorithms to analyze key factors such as GRE score, TOEFL score, CGPA, and more.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Features](#features)
4. [Machine learning Models](#modeling)
5. [Results](#results)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [Acknowledgments](#acknowledgments)

## Introduction

Graduate admissions can be competitive, and having insights into your chances can be valuable. This project aims to predict the probability of admission based on various academic and personal attributes. The model helps applicants assess their competitiveness and make informed decisions during their application process.

## Dataset

The dataset used in this project includes 2,000 records and several attributes relevant to the admission process. The dataset can be found in the repository under the name `augmented_admission_predict_1000.csv`.

## Features

The dataset includes the following features:
- **GRE Score:** Standardized test score (out of 340)
- **TOEFL Score:** English proficiency test score (out of 120)
- **University Rating:** Rating of the university (out of 5)
- **SOP Strength:** Strength of the Statement of Purpose (out of 5)
- **LOR Strength:** Strength of the Letter of Recommendation (out of 5)
- **CGPA:** Undergraduate GPA (out of 10)
- **Research:** Whether the applicant has research experience (0 or 1)

## Modeling

The model explores various machine learning algorithms, with the following best accuracies on the data:

- **Linear Regression (MLR)** -> 0.826771
- **K Nearest Neighbor (KNN)** -> 0.948610
- **Support Vector Regression (SVR)** -> 0.756455
- **Decision Tree Regression (DTR)** -> 0.927126


## Results

Each model is evaluated based on Score metric and best performing algorithm with accuracy of nearly **95%** is **KNN Algorithm**.

## Usage
- Input Data: Enterstudent details such as GRE score, TOEFL Score, and other relevant data.
- Prediction: Click the "Predict" button to determine the likelihood of heart disease.

## Contributing
Contributions are welcome! To contribute:

- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes and test them thoroughly.
- Submit a pull request with a detailed description of your changes.

## Acknowledgments
The dataset used in this project is available on Kaggle. Thanks to all contributors who have provided insights and improvements.
