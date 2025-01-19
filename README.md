# Portuguese "Vinho Verde" Red & White Wine Analysis
Created by Christopher Wong: 8-4-22 

Last updated: 1-19-25
## Overview
This project focuses on analyzing Portuguese "Vinho Verde" red and white wine datasets, aiming to clean, explore, and model the data to predict wine quality.

Libraries used: `pandas`, `seaborn`, `scikit-learn`, `matplotlib.pyplot`.

---
## Project Goal
The main objectives of the project are:
- To predict wine quality ratings based on physicochemical attributes.
- To explore the relationship between key factors such as alcohol content, pH levels, and quality.
- To evaluate the effectiveness of the KNN algorithm for wine quality classification.
- To identify areas for improvement in wine quality prediction through advanced techniques.

---
## Key Steps

### 1. **Dataset preprocessing**
- Red and white wine datasets were obtained from the UCI Machine Learning Repository.
- The datasets were merged into a single dataset for unified analysis.
- Checked data types and ensured no missing values were present.

### 2. **Feature Engineering**
- Created a custom quality rating scale with three levels:
  - **Low (0)**: Quality levels 3–4
  - **Medium (1)**: Quality levels 5–6
  - **High (2)**: Quality levels 7–9
  
### 3. **Data Analysis**
- Visualized attribute correlations using a heatmap.
- Analyzed the frequency distribution of wine quality ratings.
- Visualized relationships between:
  - Wine quality and alcohol content using box plots.
  - Alcohol content, pH, and custom quality ratings using scatter plots.
- Generated insights into the interactions between attributes.

### 5. **Modeling**
- Split the dataset into training (80%) and testing (20%) sets.
- Used the **K-Nearest Neighbors (KNN)** algorithm to predict wine quality levels based on attributes like alcohol content, pH, and residual sugar.

### 6. **Model Evaluation**
- Evaluated model performance using the following metrics:
  - **Accuracy**: 75%
  - **Precision**, **Recall**, and **F1-Score** for each quality category.
- Analyzed the confusion matrix and classification report:
  - The model performed well in predicting the **Medium (1)** category.
  - Performance was weaker for the **High (2)** and **Low (0)** categories.


---

