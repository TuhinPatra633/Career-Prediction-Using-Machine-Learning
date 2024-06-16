# Career Prediction Project

## Overview

This repository contains all the files related to the career prediction project, which aims to provide accurate career recommendations tailored to individual strengths, interests, and market demands using machine learning algorithms.

## Project Structure

The repository is organized as follows:

### 1. Data
- **CareerMapping.csv**: Dataset used for the initial model.
- **CareerMapping1.csv**: Dataset used for the revised model.

### 2. First Model Files
Contains all files related to the initial machine learning model.

### 3. Revised Model Files
Contains all files related to the revised machine learning model.

### 4. Data Visualization
- **Data Visualization.ipynb**: Jupyter notebook for data visualization.

### 5. Presentation
- **career prediction.pptx**: PowerPoint presentation detailing the project work.

## Project Description

This project aims to leverage machine learning to offer personalized career guidance to students, especially those in rural areas who lack access to traditional counseling services. By analyzing data points such as academic performance, skills, and interests, the ML model provides tailored career recommendations.

## Motivation

### Children's Potential Power
Every child in India is a valuable asset with the potential to significantly contribute to the country's growth across various sectors.

### Awareness of Study Fields
Students in rural areas often lack awareness of emerging study fields and career opportunities, making it challenging for them to align their skills and interests with industry demands.

### Importance of Proper Guidance
Proper counseling is crucial in helping students determine the most suitable career paths, which is essential for national development.

## Machine Learning Methods Used
- KNN
- Naïve Bayes
- Decision Tree
- Support Vector Machine (SVM)
- Random Forest

## Timeline

| Task              | Duration         |
|-------------------|------------------|
| Literature Survey | 23/02 - 04/03    |
| Data Gathering    | 05/03 - 13/03    |
| Data Preprocessing| 14/03 - 22/03    |
| Training & Testing| 23/03 - 12/04    |
| Parameter Tuning  | 13/04 - 23/04    |
| Make Prediction   | 24/04 - 01/05    |

## Work Division

| Task                | Assigned to         |
|---------------------|---------------------|
| Literature Survey   | Pankaj & Tuhin      |
| Data Gathering      | Tuhin               |
| Data Preprocessing  | Pankaj              |
| Training & Testing  | Pankaj & Tuhin      |
| Parameter Tuning    | Tuhin               |
| Make Prediction     | Pankaj & Tuhin      |

## Literature Survey

### References
- **Career Prediction System by V Madhan Mohan Reddy**
  - Published on: International Journal of Scientific Research in Science and Technology
  - Methods: XGBoost, Decision Tree

- **Prediction Of Undergraduate Students’ Career Using Various Machine Learning And Ensemble Learning Algorithms**
  - Published on: Webology
  - Methods: Gradient Boosting (62%), Voting Classifier (82.75%)

- **Career Prediction Classifiers based on Academic Performance and Skills using Machine Learning by Akanksha Pandey & L.S. Maurya**
  - Published on: SSRG International Journal of Computer Science and Engineering
  - Methods: KNN (63%), Stochastic Gradient Descent (62%)

## Data Preprocessing
Data preprocessing ensures the dataset is accurate and consistent. The dataset contains 9179 samples and 28 columns. The data source link is: [CareerPrediction.csv](https://data.mendeley.com/datasets/5z68cvxssn/1)

## Model Training

### Initial Model Results
- **KNN**: Train accuracy - 98%, Test accuracy - 97% (K=95)
- **Naïve Bayes**: Train accuracy - 100%, Test accuracy - 99.8%
- **Decision Tree**: Train accuracy - 100%, Test accuracy - 100% (Max depth=15)
- **SVM**: Train accuracy - 99%, Test accuracy - 98% (RBF kernel, C=1.0)
- **Random Forest**: Train accuracy - 100%, Test accuracy - 100% (n_estimators=100, max_depth=None, min_samples_split=2, min_samples_leaf=1)

### Revised Model Results
- **KNN**: Train accuracy - 65%, Test accuracy - 55% (K=10)
- **Naïve Bayes**: Train accuracy - 51.1%, Test accuracy - 50.16%
- **SVM**: Train accuracy - 55%, Test accuracy - 52% (Linear kernel, C=7.0)
- **Random Forest**: Train accuracy - 97%, Test accuracy - 89% (n_estimators=200, max_features=14, min_samples_split=8, min_samples_leaf=7)

## Conclusion
The revised model was trained on a dataset with reduced columns to improve its effectiveness for predicting suitable career paths for students, particularly in rural areas. The models were evaluated based on their training and test accuracies, with the Random Forest model performing the best in the revised dataset.

## Contact
For any questions or further information, please contact:
- Tuhin Patra
- Pankaj Sadhukhan

Thank you for your interest in our project!
