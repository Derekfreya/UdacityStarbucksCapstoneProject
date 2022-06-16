# UdacityStarbucksCapstoneProject
Udacity Program - Starbuck Capstone Project

# Installations and Dependencies

This project used Jupyter Notebook and written in Python. The libraries used are as follows:

pandas
numpy
math
json
seaborn
matplotlib.pyplot
sklearn.preprocessing.MultiLabelBinarizer
sklearn.ensemble.RandomForestClassifier
sklearn.model_selection.train_test_split, GridSearchCV, cross_val_score
sklearn.metrics 
sklearn.preprocessing.MinMaxScaler
sklearn.preprocessing.StandardScaler
sklearn.pipeline.Pipeline
sklearn.linear_model.LogisticRegression
sklearn.neighbors.KNeighborsClassifier 
sklearn.svm.SVC

# Project Motivation

This project is included in my Data Scientist nanodegree of Udacity. We are required to pick one of the capstone project to justify our knowledge gained within data science. I picked this Starbucks Project.
This project created some dummy customer data of Starbucks, along with their actions data to different type of offers. It is very interesting to see how customer will act to different type of offers. So I have built a classification model to predict whether a customer will be positive, negative or neutral feedback to a given offer.

# Files - Project Structure

1.data
1.1 portfolio.json (describes offer provided by Starbucks)
1.2 profile.json (dummy customer data including gender, age, income etc.)
1.3 transcript.json (including customer's action on each offer, like offer viewed, offer received, offer completed, transaction and its amount, time etc)
1.4 transcript_offer_id (after offer id mapped to related transactions)
1.5 transcript_preprocessed (preprocessed transcript_offer_id)

2.Capstone_Project_Report.pdf (A blog describe the whole project, including overview, methodology, results, conclusion)

3.Starbucks_Capstone_notebook.ipynb (Project python script)

4.README.md

# Results and Summary

The final accuracy and F1 score of this classification model are reaching at 0.67 with 0.0 standard deviation, which means the model now should be stable enough to predict whether a customer will give positive, negative or neutral feedback on an offer.
From the analysis we know that female, regular customers are the most active group to give positive feedbacks on an offer. As they are the most active customers, so they usually make more transaction than those less active ones even if when they have no offers available, which is reflected in the feature no_offer_amount.
From the offer type perspective of view, discount offers are more attractive than BOGO. This perhaps due to not everyone need extra copy of coffee drink, but everyone can get the discount benefit. As informational offer do not have financial benefit, so they are the least attractive.

# Acknoledgement

Starbucks and Udacity owns this project.


