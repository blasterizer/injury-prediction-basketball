

<h1 align="center">Predicting and Categorizing Basketball Injuries Using Machine Learning</h1>
<p align="center">
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"/>
<img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/XGBoost-orange?style=for-the-badge&logo=xgboost&logoColor=white"/>
<img src="https://img.shields.io/badge/SMOTE-green?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252"/>
</p>

## Overview
This repository contains the code and analysis for a Machine Learning project conducted as part of the research at **Dublin City University**. The goal of the project was to predict injury locations and explore the key factors leading to injuries among NBA basketball players, leveraging machine learning techniques and advanced analytics.

## Project Description
The main objective of this project was to enhance injury prediction by developing machine learning models that can forecast injury types and locations in NBA players based on various player demographics, performance metrics, and injury history. Specifically, the project focused on:

- Predicting the likelihood of injuries in **upper extremities**, **lower extremities**, or **head-neck-trunk** areas.
- Identifying **key factors** influencing these injuries such as body fat percentage, minutes played, and previous injuries.
- Improving prediction for **minority classes** by addressing **class imbalance** using techniques like **SMOTE**.
- Providing insights to help teams optimize **training regimens**, **rest periods**, and **injury prevention strategies**.

## Technologies Used
- **Python**: Primary programming language.
- **Pandas and NumPy**: Data manipulation and analysis.
- **Scikit-learn**: Implementing machine learning models.
- **XGBoost**: Advanced gradient boosting for accurate predictions.
- **SMOTE-NC**: Synthetic Minority Over-sampling Technique for handling class imbalance.
- **Neural Networks**: For deep learning and complex pattern recognition.

### Machine Learning Models
- **Decision Tree**: Used as the baseline model for interpretability.
- **Random Forest**: An ensemble method to improve accuracy by handling feature importance.
- **XGBoost**: Best performing model, used for boosting weak classifiers.
- **Neural Networks**: Used to identify complex injury patterns based on player statistics.

## Data
The dataset used in this study included:
- NBA injury records from the **2010-2020 seasons**.
- Player performance metrics like **minutes played**, **field goals attempted**, and **rebound statistics**.
- **Physiological data** such as height, weight, and **Body Fat Percentage** (BFP).
- **Historical injury records** to improve predictions of recurrent injury types.

## Results
- **XGBoost** model achieved the highest accuracy of **86.1%** and an F1 score of **0.861** when using **SMOTE-NC** for balancing the classes.
- **Random Forest** also performed well, with an accuracy of **85.1%**, particularly useful for identifying key features related to injury risks.
- **Neural Networks** showed good performance but were less interpretable.
- The use of **previous injury records** significantly improved prediction performance.

### Key Injury Predictors:
- **Body Fat Percentage** and **Field Goals Attempted per Minute** emerged as the most significant factors in predicting injury locations.
- **Player position** also played a crucial role in determining the likelihood and type of injury.

## Conclusion
This research highlighted the effectiveness of machine learning models in predicting and classifying injuries among NBA players. The results showed that **previous injury records**, **game statistics**, and **physiological data** are vital for accurate injury predictions. Incorporating **class balancing techniques** like SMOTE-NC led to improved model performance.

### Future Work
- Expanding the dataset to include **WNBA** and **college basketball** players for more comprehensive injury patterns.
- Exploring **deep learning models** further to improve prediction accuracy for minority injury categories.
- Utilizing more **complex physiological data** to enhance the accuracy of injury prediction models.
