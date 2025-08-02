# Flight Delay Prediction

This project aims to predict flight arrival delays for domestic flights in the United States using machine learning techniques, primarily Random Forest classification. The dataset consists of real-world flight data.

---

## Overview

The dataset contains various features describing flights, such as departure delay, distance, taxi times, scheduled departure time, and more. The goal is to build a model that can accurately predict whether a flight will be delayed or not.

---

## Steps Covered

### Data Cleaning

- Handling missing values by imputing medians for numerical columns and "None" for categorical columns.  
- Dropping columns with excessive missing data.  

### Feature Engineering

- Encoding categorical variables where necessary.  
- Aligning training and test datasets to have consistent features.  

### Modeling

- Training a Random Forest classifier on the training data.  
- Evaluating model performance using accuracy, precision, recall, and F1-score on a validation set.  
- Analyzing feature importance to understand key factors affecting delays.  

---

## Key Observations

- Departure delay (DepDelay) was identified as the most important feature affecting arrival delays.  
- The model achieved an accuracy of approximately 87%.  
- Other significant features included flight distance, taxi out time, and scheduled departure time.  

---

## How to Use

Download or clone this repository. You can open the notebooks in Google Colab or Jupyter Notebook to run the analysis step by step.

---

## Files
  
- `FlightDelayPrediction.ipynb`: Jupyter Notebook with full code and explanations.  

---
## Dataset

The dataset used in this project is too large to be hosted here.  
You can download it directly from Kaggle:  
[Flight Delay Dataset on Kaggle](https://www.kaggle.com/datasets/your-dataset-link)

## Author

Created by EsraGunes. Feel free to reuse or adapt this work.
