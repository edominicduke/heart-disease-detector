# Heart Disease Detector

## Goal
The ultimate goal of this project is to develop a tool that can be used by doctors to use test results to determine whether a patient has a heart disease. This goal has been ultimately achieved through this project: a web application that leverages the inferencing capabilities of a custom-made binary classification MLP that has been trained on a dataset based on 4 databases: Cleveland, Hungary, Switzerland, and Long Beach V.

## Project Objectives
With the goal in mind, the objectives of this project are to develop a binary classification MLP that demonstrate strong ability to classify a given patient as likely to have a heart disease or unlikely to have a heart disease. The MLP's classification ability will be assessed through the following 4 metrics: accuracy, precision, recall, and AUC. These metrics have been chosen to ensure the correctness of its predictions and to moreover ensure its ability to distinguish patients with heart disease from patients without heart disease.

## Motivation
The fact of the matter is that millions of people worldwide are suffering from heart diseases. After all, cardiovascular diseases take approximately 17.9 million lives every year according to the World Health Organization. Therefore, this project was built with the intention of addressing the issue of heart disease detection. The way it ultimately does is by serving as a tool that can be used by doctors to use test results to determine whether a patient has a heart disease,
which can assist with reducing the rate of misdiagnosis.

## What it Does
This web application is designed to inference whether a patient is likely
to have a heart disease or not. The workflow is as follows. The web application takes in health metrics from the user. Then, once the "Yes" option is selected under the "Predict" question, the app uses a custom-made binary classification MLP to inference whether the patient is likely to have a heart disease or not.

## Quick Start
To run the project, follow these steps:

**1) Navigate to the GitHub repository**
- URL: https://github.com/edominicduke/heart-disease-detector.git

**2) Clone the GitHub repository**
- Command: git clone https://github.com/edominicduke/heart-disease-detector.git

**3) Change into the appropriate directory**
- Command: cd heart-disease-detector

**4) Run the web application**
- Command: streamlit run src/app.py

## Video Links
- Demo Video
- Technical Walkthrough

## Evaluation
The custom-made binary classification MLP used to inference whether the given patient is likely to have a heart disease or not achieved the following metrics on the test
data after training (as can also be found in the output of notebooks/run_and_train_heart_disease_detection_model.ipynb):
- **Test Accuracy:** 0.9610389471054077

- **Test Precision:** 0.9784075617790222

- **Test Recall:** 0.9487179517745972

- **Test AUC:** 0.9736841917037964

**Conclusion:** These high results collectively indicate that the
MLP is a strong model for heart disease detection (in the context of the data/heart.csv dataset used for training): not just in terms of correctness of predictions, but also
in terms of distinguishing heart-disease patients from non-heart-disease patients.