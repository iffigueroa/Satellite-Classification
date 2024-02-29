# Satellite Use Classification

## Project Overview
The code in this repo aims to classify satellites based on their purpose or use using various machine learning methods, including both supervised and unsupervised techniques. The project leverages a dataset compiled by the Union of Concerned Scientists (UCS) from several sources, containing information about satellites that are currently active and in orbit. The dataset provides features such as satellite characteristics and orbital parameters, which will be used to develop accurate classification models.

## About the Dataset

The dataset we'll be using for this project was compiled by the Union of Concerned Scientists (UCS) from several sources. The dataset contains information about satellites that are currently active and in orbit. The most recent version of the dataset can be found at this link: https://www.ucsusa.org/resources/satellite-database
For this project the 5-1-2023 version of the database was used. 

## Jupyter Notebooks
The project includes Jupyter notebooks for data cleaning and modeling. These notebooks can be run locally after installing Jupyter or using Google Colab, each notebook should have a link to open in Colab. 

1. **Data Cleaning Notebook**: This notebook preprocesses the dataset, handling missing values, encoding categorical variables, and performing feature scaling to prepare the data for modeling. Please run this first, as it produces a clean dataset for model building.
2. **Supervised Learning Notebook**: This notebook explores the use of KNN (K-Nearest Neighbors) and Decision Trees for satellite classification.
3. **Unsupervised Learning Notebook**: This notebook investigates the use of KMEANS and DBSCAN clustering algorithms for satellite classification.


