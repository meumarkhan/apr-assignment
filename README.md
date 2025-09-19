Assignment-1: Logistic Regression for Diabetes Prediction
This repository contains the code for an academic assignment focused on implementing a machine learning algorithm. The project uses a Logistic Regression model to predict the onset of diabetes based on diagnostic medical measurements.

Overview
The primary goal of this project is to build and evaluate a binary classification model. We utilize the Pima Indians Diabetes Database, a standard dataset for this type of problem. The entire workflow—from data loading and exploratory analysis to model training and evaluation—is implemented in a single Python script designed for ease of use in Google Colab.

Dataset
Name: Pima Indians Diabetes Database

Source: National Institute of Diabetes and Digestive and Kidney Diseases. The version used in this script is hosted on John Brownlee's public GitHub repository.

Description: The dataset consists of 768 observations of female patients of Pima Indian heritage, aged 21 and older. It includes 8 medical predictor variables and one target variable, Outcome.

Features:

Pregnancies: Number of times pregnant

Glucose: Plasma glucose concentration

BloodPressure: Diastolic blood pressure (mm Hg)

SkinThickness: Triceps skin fold thickness (mm)

Insulin: 2-Hour serum insulin (mu U/ml)

BMI: Body mass index

DiabetesPedigreeFunction: A function scoring the likelihood of diabetes based on family history.

Age: Age in years

Target Variable (Outcome): A binary value indicating diagnosis of diabetes (1) or not (0).

Requirements
The script uses the following Python libraries:

pandas

numpy

scikit-learn

matplotlib

seaborn

These libraries are pre-installed in Google Colab environments.

How to Run the Code
The code is designed to be executed in a Google Colab notebook for simplicity and reproducibility.

Open Google Colab: Navigate to colab.research.google.com.

Create a New Notebook: Select File > New notebook.

Copy the Code: Open the main.py file from this repository and copy its entire content.

Paste and Run: Paste the code into a cell in your new Colab notebook and run it by pressing Shift + Enter or clicking the play icon.

The script will automatically download the dataset, preprocess the data, train the logistic regression model, and then print the performance metrics and display a confusion matrix plot as its output.

Files in this Repository
main.py: A Python script containing the complete workflow for the diabetes prediction task.

README.md: This file, providing an overview and instructions for the project.
