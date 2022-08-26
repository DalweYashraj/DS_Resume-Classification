# DS_Resume-Classification

# Business Objective -
Business objective- The document classification solution should significantly
reduce the manual human effort in the HRM. It should achieve a higher level of
accuracy and automation with minimal human intervention

# Sample Data Set Details - Resumes and financial documents

# Introduction

	Resume Classification/Screening  ( NLP & Machine Learning) Choosing the right people for the job is the biggest responsibility of every business since choosing the right set of people can accelerate business growth exponentially. We have imported few libraries for resume classification/screening and they are namely as : Pandas, NumPy, Matplotlib, Word cloud & different classifier to fetch resumes information & to plot corresponding visualization.

# Data Source 

We have resumes in  different extensions (.doc,.docx,.pdf) and all those are imported on Google Drive and later they are inter-connected with Google Collab.

We have mainly created two coulumns and they are namely as "Category" and "Resumes".

There are total 4 categories:
1.React JS Developer
2.PeopleSoft Developer
3.WorkDay Developer
4.SQL Developer Lightning Insight Resumes

--> Data Analysis,Data Exploration,Data Preprocessing

# Tokenization: 
It is the process of breaking text up into smaller chunks as per our requirements

# Lemmatization : 
 It refers to the use of vocabulary & morphological analysis of words ,aiming to return the base or dictionary form of the word --> known as 'lemma'

# Data Visualization :
Mainly of "Category" column 
-Bar Chart 
-Pie Chart 
-Wordcloud
-Word - Frequency from “Category” Column

# Label Encoder:

Assign labels to "Category" column (0,1,2,3)

# Implementation of Model

Splitting Data into Train (0.70) & Test (0.30) 

-Random Forest Classifier
-SVM Classifier
-Multinomial NB Classifier
-Logistic Regression Classifier
-Adaboost Classifier
-Gradient Boosting Classifier
-Gradient Boosting Classifier
-XTreme Gradient Boosting Classifier
-Light Gradient Boosting Classifier

# Conclusion

From the final table we can conclude that among the calculated classifiers  Random Forest Classifier gave the favourable results i.e Precision & Recall is 1.0 and that too F1-score is also 1.0. which is harmonic mean of precision and recall.

# Model Deployment on Web Server

For model deployment ,we have implemented data on streamlit. 

1.Create .py file for streamlit containing classification  Drag and drop files to see wordcloud and most freq. words
2.Open the command prompt
3.Run  pip install streamlit
            pip install pdfplumber
            pip install xgboost==1.5.0
            streamlit run filename.py
4.New window will open having deployment part









