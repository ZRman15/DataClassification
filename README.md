# Data Classification Coursework (6COM1044)

## Introduction
This repository contains all files, resources, experimental code, and the final report for the Machine Learning and Neural Computing: Data Classification coursework (module 6COM1044), academic year 2024/2025. The coursework involves using Principal Component Analysis (PCA) and Support Vector Machines (SVM) to classify diabetes based on specific health indicators.

## Coursework Objective
The primary aim is to explore the provided datasets, perform data analysis, and construct robust SVM models to classify diabetes or prediabetes.

## Coursework Structure

The coursework consists of four main tasks:

### Task 1 - Data Exploration
- Data loading and separation of features and labels
- Generating scatter plots for selected features
- Normalizing datasets using `StandardScaler`
- PCA analysis and visualisation of principal components

### Task 2 - SVM Classification (NoActivity Group)
- Splitting datasets into training and validation sets
- Normalizing datasets
- Hyperparameter tuning for SVM models
- Final evaluation using accuracy scores and confusion matrices

### Task 3 - SVM Classification (PhysActivity Group)
- Replicating Task 2's approach for the PhysActivity datasets

### Task 4 - Cross-model Evaluation
- Testing model performance across different datasets
- Detailed comparative analysis of models

## Repository Files
- `diabetes_NoActivity_training.csv`
- `diabetes_NoActivity_test.csv`
- `diabetes_PhysActivity_training.csv`
- `diabetes_PhysActivity_test.csv`
- `20070280.pdf` – Final experimental report detailing methodology and results
- `20070280.ipynb` – Jupyter Notebook containing all experimental code

## Dataset Overview
The datasets originate from the Diabetes Health Indicators dataset, balanced across two categories:
- **0** - No diabetes
- **1** - Prediabetes or Diabetes

Each dataset entry includes seven features:
- BMI
- General Health (GenHlth)
- Mental Health (MentHlth)
- Physical Health (PhysHlth)
- Age
- Education Level
- Income Level

## Technologies Used
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Usage Guidelines
- Clone this repository and execute the Jupyter Notebook (`20070280.ipynb`) to reproduce results.
- Ensure all listed Python libraries are installed.

## Author
Zohaib Rehman (Student ID: 20070280)

## Academic Integrity
This coursework was independently conducted and adheres to academic guidelines set by the University of Hertfordshire.

