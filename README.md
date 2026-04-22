# Social Media Addiction vs Productivity – EDA & Machine Learning

## Overview

This project explores how social media usage patterns affect productivity and addiction levels across a dataset of 6000 individuals.

The objective is to identify key behavioral drivers of addiction severity using statistical analysis and machine learning, and to build a classification model that predicts addiction levels from user behavior.

The workflow combines exploratory data analysis (EDA), hypothesis testing, and a Random Forest classifier to understand relationships between usage habits and productivity outcomes.

---

## Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- SciPy (statistical testing)  
- Jupyter Notebook  

---

## Key Areas of Analysis

- Distribution of social media usage and productivity scores  
- Relationship between usage time, sleep, and productivity  
- Behavioral patterns across addiction levels  
- Kruskal-Wallis statistical testing across features  
- Correlation analysis of behavioral variables  
- Feature importance using Random Forest classifier  
- Prediction of addiction severity (classification task)  

---

## Key Takeaways

| Finding | Implication |
|--------|-------------|
| Social media hours is the only feature with a statistically significant Kruskal-Wallis result | Strongest behavioral driver of addiction severity |
| Age shows no significant difference across addiction levels | Not a useful predictor in this dataset |
| Sleep hours and notification count show no significant group differences | Weaker behavioral signals than expected |
| Social media hours has the highest correlation with addiction level | Consistent across statistical and correlation analysis |
| Social media hours is the top feature in model importance | All methods (stats + ML) agree on this key driver |

---

## Important Note

This dataset appears to be highly clean and well-structured, with unusually strong separation between behavioral features.

This may indicate synthetic or curated data rather than real-world observational data.

As a result, conclusions should be interpreted as pattern-based insights rather than causal real-world conclusions.

---

## Machine Learning Model

- **Model:** Random Forest Classifier  
- **Task:** Predict addiction severity level  
- **Approach:** Train-test split with feature-based classification  
- **Evaluation:** Accuracy + feature importance analysis  

---

## Project Notebook

https://www.kaggle.com/code/amrkabbary/social-media-addiction-vs-productivity-eda-ml?scriptVersionId=313641046
