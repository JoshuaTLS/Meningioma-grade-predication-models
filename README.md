# Meningioma-grade-predication-models

In this project, our aim is to build classification models to predict grade of meningioma in patients with brain tumor from radiomic features extracted from MRI scan

## Introduction

- In this project, we aim to build machine learning classification models to predict the grade of meningioma (brain tumor) in patients using extracted features from MRI radiomics.
- According to World Health Organization, meningioma is classified into grades I, II, or III, with grade I being benign, grade II atypical, and grade III anaplastic.
- The radiomics features are extracted from pre-operative MRI scans (MRIs were collected from The Cancer Imaging Archive (TCIA), a publicly available dataset at https://www.cancerimagingarchive.net/collection/meningioma-seg-class/ under the restricted license agreement).
- Early and complete resection of the high grade meningioma lesions is necessary due to their aggressive behaviour and high recurrence rate.
- Radiomics combined with machine learning, has shown promise in the development of predictive models for meningioma grade.


## Outline of the python codes

- Preliminary Data Analysis
- Data Standardization
- Feature Selection
- Model Training and Evaluation
- Model Improvement - Hyperparameter Tuning
- Re-evaluation of tuned models
- Comparing Models performance

## Conclusion
- In this project, three classifiers were developed to predict the grade of meningioma in patients with brain tumor.
- The three classification models are: Decision tree, Kneighbors classifier and Gradient Boosting
- Gradient boosting is the best classifier followed by decision tree. Kneighbors acheived the least accuaracy and other performance metrics of the three classifiers
