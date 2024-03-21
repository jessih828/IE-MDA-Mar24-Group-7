# Obesity Muti-Class Classification Using PySpark

## Overview
This project demonstrates the use of Apache Spark for classifying obesity levels in individuals based on various features. The analysis is implemented in a Jupyter Notebook and covers data processing, model training, and evaluation using PySpark's MLlib.

## Dataset
The dataset used in this analysis consists of various attributes related to personal health and habits, aimed at classifying obesity levels. Example attributes include age, weight, height, and eating habits.

## Analysis Steps
1. **Initialization**: The notebook starts with setting up the environment and importing necessary libraries.
2. **Spark Session Creation**: A Spark session is created for the analysis.
3. **Data Loading and Preprocessing**: The dataset is loaded, and initial data preprocessing is performed.
4. **Feature Engineering**: Transformation of features and preparation for modeling.
5. **Model Training**: Training a Random Forest Classifier using PySpark MLlib. The model achieves an accuracy of 0.97.
6. **Model Evaluation**: Evaluating the model's performance using cross-validation and various metrics.
7. **Data Testing**: Input data for obesity testing.

## Concluding Remarks
This project demonstrates the power and scalability of Apache Spark for handling and analyzing large datasets in the domain of health.