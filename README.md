# Wine Quality Prediction

Repository structure:


Data: Contains winequality_red.csv, winequality_white.csv and selected_features.csv data(this dataset should be use for the model development)


Doc: Contains documentation including document with graphics used for report, summary of literature and final versions of report in .docx and .pdf format


Images: Contains images generated for the report


Scripts: contains scripts, including:


Exploratory data analysis: Exploratory analysis for Wine quality prediction.ipynb


Model Development: Model Development for wine quality prediction.ipynb


Exploratory analysis Scripts to produce specific data: selected_features.csv


Instructions to use code:

Machine learning script can be re-run by executing all of the script files referenced above.

Paths for data input are set up to mirror the structure in this repo. As a result, to run the files, it may be easiest to clone the repository and run the scripts within the existing folder structure.

Project title: Wine Quality Prediction

Datasets sources: UC Irvine Machine Learning Repository -  http://archive.ics.uci.edu/ml/index.php

Data intial sorce: The datasets was created by Paulo Cortez (Univ. Minho), Antonio Cerdeira, Fernando Almeida, Telmo Matos and Jose Reis (CVRVV) @ 2009

Datasets: red and white wine.
  
Data descrption: The inputs include objective tests (e.g. PH values) and the output is based on sensory data (median of at least 3 evaluations made by wine experts). Each expert graded the wine quality between 0 (very bad) and 10 (very excellent). Several data mining methods were applied to model these datasets under a regression approach. The support vector machine model achieved the best results. Several metrics were computed: MAD, confusion matrix for a fixed error tolerance (T), etc. Also, we plot the relative importances of the input variables (as measured by a sensitivity analysis procedure).

Number of Instances: red wine - 1599; white wine - 4898. 
Number of Attributes: 11 + output attribute

Attribute information:

   Input variables (based on physicochemical tests):
   
   1 - fixed acidity
   
   2 - volatile acidity
   
   3 - citric acid
   
   4 - residual sugar
   
   5 - chlorides
   
   6 - free sulfur dioxide
   
   7 - total sulfur dioxide
   
   8 - density
   
   9 - pH
   
   10 - sulphates

  11 - alcohol

  Output variable (based on sensory data):
  
   12 - quality (score between 0 and 10)

PYTHON LIBRARIES:

To ensure all the libraries and functions in my code work, you need to install the following Python packages:
numpy, pandas, matplotlib, scipy, plotly, seaborn, scikit-learn, imbalanced-learn and imbalanced-learn.

