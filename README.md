Patient Condition NLP Project

Project Overview

This project applies Natural Language Processing (NLP) techniques to analyze patient conditions based on drug reviews. The dataset, drugsComTrain.tsv, contains patient reviews and ratings for different drugs used to treat various conditions. The goal is to build an NLP model that can predict patient conditions based on textual drug reviews.

Dataset

File: drugsComTrain.tsv

Description: This dataset contains drug reviews, ratings, and conditions. It is used to train NLP models to extract insights about patient conditions.

Columns:

Unnamed: 0 (Index)

drugName (Name of the drug)

condition (Condition treated by the drug)

review (Patient's textual review)

rating (Numerical rating of the drug)

date (Review date)

usefulCount (Number of people who found the review useful)

Notebook

File: patient_condition_nlp_project_tutorial.ipynb

Purpose: This Jupyter Notebook provides a step-by-step tutorial on processing and analyzing patient reviews. It includes:

Data loading and preprocessing

Text cleaning and NLP techniques

Exploratory Data Analysis (EDA)

Feature engineering and vectorization

Model training and evaluation (e.g., classification models for predicting conditions)

Installation

To run the project, install the required dependencies:

pip install pandas numpy scikit-learn nltk matplotlib seaborn

Usage

Open the Jupyter Notebook:

jupyter notebook patient_condition_nlp_project_tutorial.ipynb

Follow the steps in the notebook to preprocess data and train the model.

Modify and experiment with different NLP techniques and models.

Future Improvements

Implement deep learning models for better accuracy.

Use Named Entity Recognition (NER) for better condition extraction.

Expand dataset with more patient reviews.

Author

Ahmad Alsebai

License

This project is licensed under the MIT License.

