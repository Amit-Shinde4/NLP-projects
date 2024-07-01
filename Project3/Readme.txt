# Diabetes Prediction and Analysis

This repository contains Python scripts and Jupyter notebooks for analyzing and visualizing diabetes-related data.

## Files

1. **ANOVA_Diabetes.ipynb**
   - Description: Python script for loading and analyzing diabetes dataset.
   - Libraries used: Pandas, NumPy, Matplotlib, Seaborn, Plotly
   - Features: Loads a diabetes dataset from a remote URL, performs ANOVA analysis on High Blood Pressure (HighBP) based on diabetes status.

2. **Correlation_Diabetes.ipynb**
   - Description: Jupyter notebook for exploring correlations among diabetes-related variables.
   - Features: Loads the diabetes dataset, calculates and visualizes correlation matrix using Seaborn heatmap.

3. **Data_Analysis_Diabetes.ipynb**
   - Description: Python notebook for visualizing diabetes-related data from the Behavioral Risk Factor Surveillance System (BRFSS) 2015 dataset.
   - Libraries used: Pandas, Matplotlib, Seaborn
   - Features: Loads the diabetes dataset from a remote URL, explores and visualizes various aspects such as distribution of BMI, prevalence of high blood pressure (HighBP), smoking habits, and cholesterol levels. Includes histograms, bar plots, and correlation plots to understand relationships between different health indicators and diabetes status.


4. **Data_Visualization_Diabetes.ipynb**
   - Description: Notebook exploring the performance of classifiers on the diabetes dataset.
   - Libraries used: Pandas, Matplotlib, Seaborn
   - Features: Loads the diabetes dataset, implements machine learning classifiers to predict diabetes status based on health indicators. Evaluates classifier performance metrics such as accuracy, precision, recall, and ROC curves. Visualizes results using various plots like scatter plots, line plots, histograms, correlation matrices, bar plots, pie charts, and more to understand relationships and predictive power of different health indicators.


5. **LogisticR_Diabetes.ipynb**
   -Description: This notebook explores the performance of classifiers on the diabetes dataset.

   -Libraries used: Pandas, Matplotlib, Seaborn, Scikit-learn

   -Features:Prepares the dataset by selecting relevant features and the target variable for classification.Implements machine learning classifiers such as Logistic Regression and evaluates their performance using metrics like accuracy, precision, recall, and ROC curves.



6. **Performance_of_Classifier.ipynb**
   - Description: Jupyter notebook for evaluating performance metrics of the diabetes classifier.
   -Libraries used:Pandas, Matplotlib, Seaborn, Scikit-learn
   -Features: Loads diabetes dataset, cleans NaN values, trains Logistic Regression and Random Forest classifiers, evaluates with accuracy, precision, recall, F1 score, ROC AUC score, compares model performance for diabetes prediction.

## Usage

To run the scripts and notebooks, ensure you have Python installed along with the required libraries specified in `requirements.txt`. You can install the dependencies using pip:

```bash
pip install -r requirements.txt
