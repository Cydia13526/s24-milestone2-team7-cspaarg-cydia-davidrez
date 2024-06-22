#####s24-milestone2-team7-cspaarg-cydia-davidrez

#####Casey Spaargaren(cspaarg@umich.edu), School of Information, University of Michigan
#####Cydia Tsang (cydia@umich.edu), School of Information, University of Michigan
#####David Rezkalla(davidrez@umich.edu), School of Information, University of Michigan

#####1. Set Up Steps
###### 1. pip install -r requirements.txt (For python 2)/ python3 -m notebook (For python3)
###### 2. jupyter notebook
###### 3. Inside jupyter notebook, click project.ipynb

#####2. Strcuture of the Code:
######  Prerequisite
######     1.Library Download & Import
######     2.Hugging Face Login
######  A Data Import
######     Federal Reserve's meeting minutes from 1993 to 2024
######  B. Data Cleaning & Manipulation
######     1.Data Cleaning
######     2.Data Manipulation on Meeting Minutes
######     3.Data Manipulation on Federal Funds Rate
######     4. Data Merge Between MeetingMinutes & Federa Funds Rate
######  C. Basic NLP Analysis
######     1. Sentiment analysis
######     2. Key phrase extraction
######  D. Supervising Learning
######     1. Base Model - Linear Regression
######     2. Actual Model - Linear Regression, Support Vector Machine, Decision Tree Regressor and XGBoost Regressor
######     3. Actual Model With Temporal Features
######     4. Actual Model With Sentiment Analysis
######  E. Unsupervising Learning
######     1. KMeans Clustering
######     2. LDA Topic grouping
