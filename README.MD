# Fetal Health Classification

## Project Overview

This project focuses on developing a machine learning model to predict fetal health based on features extracted from Cardiotocogram (CTG) exams. The dataset contains 2126 records, and the goal is to classify fetal health into three classes: Normal, Suspect, and Pathological.

## Target Variable

The target variable in this dataset is the fetal health classification, which has three distinct classes:

- **1 - Normal:** Represents cases where fetal health is within the normal range.
- **2 - Suspect:** Indicates cases with a suspicion of potential health issues.
- **3 - Pathological:** Identifies cases with clear signs of fetal health pathology.

The goal of this project is to develop a machine learning model that accurately classifies fetal health based on the features extracted from Cardiotocogram exams.


## Notebook

- `fetal_health.ipynb`: Jupyter Notebook for the entire project, including data exploration, preprocessing, model training, evaluation, and visualization.

## Directory Structure

- `notebook`: Contains the Jupyter Notebook for the project.
- `data/raw`: Raw dataset (fetal_health.csv).

## Data Description

The CTG dataset comprises features such as fetal heart rate (FHR), fetal movements, uterine contractions, etc. The objective is to predict fetal health, contributing to efforts in reducing child and maternal mortality.

## Results and Visualization

- **Accuracy:** Achieved an accuracy of 96% on the test set.
- **Confusion Matrix:** Visualized using a heatmap for detailed classification performance.

## Conclusion

The developed machine learning model, particularly an XGBoost classifier with optimized hyperparameters, demonstrated effectiveness in predicting fetal health, contributing to the overall goal of reducing child and maternal mortality.

## Future Work

- Explore additional feature engineering possibilities.
- Investigate ensemble methods for further improvement.

Feel free to explore the `fetal_health.ipynb` notebook for detailed implementation and analysis.
