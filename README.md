## SIADS Milestone II - Forecasting Federal Funds Rate Movements through Natural Language Processing of FOMC Minutes

### Description:
###### This project leverages machine learning and natural language processing (NLP) techniques to analyze and model the relationship between the Federal Reserve's meeting minutes and the Federal Funds Rate from 1993 to 2024.

##### Casey Spaargaren(cspaarg@umich.edu), School of Information, University of Michigan
##### Cydia Tsang (cydia@umich.edu), School of Information, University of Michigan
##### David Rezkalla(davidrez@umich.edu), School of Information, University of Michigan


### Table of Contents:
#####  Prerequisite
######     1. Library Download & Import: Steps to download and import necessary libraries.
######     2. Hugging Face Login: Instructions for logging into Hugging Face.
#####  A Data Import
######     Federal Reserve's Meeting Minutes: Importing data from 1993 to 2024.
#####  B. Data Cleaning & Manipulation
######     1. Data Cleaning: Preparing the meeting minutes for analysis.
######     2. Data Manipulation on Meeting Minutes: Transforming the text data.
######     3. Data Manipulation on Federal Funds Rate: Processing the rate data.
######     4. Data Merge: Combining the meeting minutes with the Federal Funds Rate data.
#####  C. Basic NLP Analysis
######     1. Sentiment Analysis: Analyzing the sentiment of the meeting minutes.
######     2. Key phrase extraction
#####  D. Supervising Learning
######     1. Base Model - Linear Regression
######     2. Actual Model - Linear Regression, Support Vector Machine, Decision Tree Regressor and XGBoost Regressor
######     3. Actual Model With Temporal Features
######     4. Actual Model With Sentiment Analysis
#####  E. Unsupervising Learning
######     1. KMeans Clustering
######     2. LDA Topic grouping


### Prerequisites:
###### Python 3.8+
###### Other prerequisites


### Installation:
###### 1. git clone https://github.com/Cydia13526/s24-milestone2-team7-cspaarg-cydia-davidrez.git
###### 2. pip install -r requirements.txt (For python 2)/ python3 -m notebook (For python3)
###### 3. jupyter notebook
###### 4. Inside jupyter notebook, click project.ipynb
