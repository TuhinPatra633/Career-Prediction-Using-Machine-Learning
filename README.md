# Career Prediction Using Machine Learning
<img src="Data/Picture1.png" alt="Banner" width="500"/>

## Overview

This repository contains all the files related to the career prediction using machine learning, which aims to provide accurate career recommendations tailored to individual strengths, interests, and market demands using machine learning algorithms.

## Repository Structure

The repository is organized as follows:

### 1. Data
- **CareerMapping.csv**: Dataset used for the initial model.
- **CareerMapping1.csv**: Dataset used for the revised model.

### 2. First Model Files
Contains all files related to the initial machine learning model.

### 3. Revised Model Files
Contains all files related to the revised machine learning model.

### 4. Data Visualization
- **Data_visualization.ipynb**: Jupyter notebook for data visualization.

### 5. Presentation
- **Career Prediction.pptx**: PowerPoint presentation detailing the work.
- **[View the presentation on Google Slides](https://docs.google.com/presentation/d/e/2PACX-1vQszHHy_2wXoQUY7iq1ETN6pMMfIcNLbI5DYBkBRIj6LK-xiFMAQwTUDtXyVmtCAw/pub?start=false&loop=false&delayms=3000)**

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

## Data Preprocessing
Data preprocessing ensures the dataset is accurate and consistent. The dataset contains 9179 samples and 28 columns. The data source link is: [CareerPrediction.csv](https://data.mendeley.com/datasets/5z68cvxssn/1)

## Model Training

### Initial Model Results
- **KNN**: Train accuracy - 98%, Test accuracy - 97% 
- **Naïve Bayes**: Train accuracy - 100%, Test accuracy - 99.8%
- **Decision Tree**: Train accuracy - 100%, Test accuracy - 100% 
- **SVM**: Train accuracy - 99%, Test accuracy - 98% 
- **Random Forest**: Train accuracy - 100%, Test accuracy - 100% 

### Revised Model Results
- **KNN**: Train accuracy - 65%, Test accuracy - 55% 
- **Naïve Bayes**: Train accuracy - 51.1%, Test accuracy - 50.16%
- **SVM**: Train accuracy - 55%, Test accuracy - 52% 
- **Random Forest**: Train accuracy - 97%, Test accuracy - 89% 

## Conclusion
The revised model was trained on a dataset with reduced columns to improve its effectiveness for predicting suitable career paths for students, particularly in rural areas. The models were evaluated based on their training and test accuracies, with the Random Forest model performing the best in the revised dataset.

## Web Application
We have built an web application of this project using the best performing model. This Web application predict students career by asking some skill rating. 
[Visit The Website](https://huggingface.co/spaces/PankajSadhukhan/career-prediction)

## Contact
For any questions or further information, please contact:
- Tuhin Patra
- Pankaj Sadukhan

Thank you for your interest in the project!
