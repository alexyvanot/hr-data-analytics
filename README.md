# 📊 HR Data Analytics – Contract Type Prediction  
Machine Learning Project – DataCrafting & Data Mining

### Got to the Jupyter Notebook for full analysis:  
### [ProjetFinal_DataCrafting_Mining.ipynb](./ProjetFinal_DataCrafting_Mining.ipynb)

> This project focuses on analyzing a synthetic HR dataset in order to:
> - clean and preprocess employee information
> - detect anomalies and missing values
> - build a predictive model to determine the type of employment contract  
>   *(Internship, Apprenticeship, Fixed-term, Permanent)*
> - This project is in the context of an academic module on DataCrafting & Data Mining
> - It is annotated in French as per course requirements

---

## Data Processing Pipeline

1. Data Cleaning
- Removal of duplicates
- Correction of inconsistent ages and abnormal salaries
- Missing value handling (imputation or removal)
- Standardization of categorical fields (gender, education, contract type…)

2. Feature Engineering
- Encoding of categorical variables
- Normalization of numerical features
- Creation of a new feature: `Anciennete` (Employee seniority)

3. Machine Learning
- Supervised classification with `RandomForestClassifier`
- Hyperparameter optimization using `GridSearchCV`
- Evaluation through a classification report and confusion matrix

---

## Model Results

The model shows partial ability to distinguish permanent and fixed-term contracts,
but struggles to differentiate internships and apprenticeships due to the absence
of specific HR indicators.

**Achieved Accuracy**: **~22–45%** depending on the dataset split

---

## Tech Stack

- Python 3
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  

---

## Author

Project developed by **alexyanot**  
As part of the *DataCrafting & Data Mining* academic module

---
