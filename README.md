# Bioinformatics Pipeline
A pipeline for visualizing and analyzing bioinformatics data.

These notebooks are meant to be downloaded and used modified on your local machine.

## Step 1 Notebook
The Ingestion notebook is specific to data that comes from Qiita in QZA files, but this notebook serves as an example of how to apply bioinformatic specific R libraries to extract data into easily readable CSV files


## Step 2 Notebook
The Preprocessing notebook details how one can combine extracted bioinformatics data (from the first notebook) with metadata and other human-readable features that can be used for further analysis. It also details how one can combine all data into a single data frame that can be used for visualization and modeling. A user can utilize the second notebook as an example of how to clean data for future analysis, and would additionally be able to append new data as it comes in to fortify and validate results of previous analyses. 

## Step 3 Notebook

The Exploratory Data Analysis notebook provides a tutorial on a variety of visualizations to examine differences between samples and among varying demographics, as well as code that calculates the Shannon diversity index (also known as alpha diversity or within sample diversity) of each individual, thereby demonstrating how specific metrics can be added to a dataset if not already present. 

## Step 4 Notebook
The Modeling notebook provides examples and code for feature selection and classifications based machine learning models. It provides one example of a high bias, low variance model (LDA) and one example of a low bias, high variance model. The notebook is set up such that a user can easily modify the hyperparameters for the existing algorithms, but also so that any additional models from the scikit-learn library may be easily deployed. This notebook additionally provides metrics such as the confusion matrix and ROC curves that can be used to evaluate predictive algorithms. Lastly, and perhaps most importantly, this notebook provides a method of extracting feature importance from our predictive models for hypothesis generation. 
