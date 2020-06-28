# "Pants of fire" indicating system

Author: Marcin Kamyk

This is a Final project for "Kodołamacz" Data Science Bootcamp, organized by Sages Sp. z o.o.

## Abstract

The essential goal of the project was to prepare a model that will filter out, and indicate politicians statements than tan be considered completely false based solely on the words used in them, and a dedicated machine learning techniques acquired during the training.

## Data

The data comes from the POLITIFACT portal, that gathers official political statements, assigns them rating and enables further analysis. 
The project contains three key jupyter notebooks:
1.	Source data
2.	Dataanalysis & processing
3.	Binary classification

## Model technical specification & methods sylabus: 

Project considers use natural language processing and is based on binary classification.
Models use: vectorization TF-IDF, logistic regression classifier, naive Bayes classifier, decision tree classifier, random forest classifier and class GridSearchCV.

## Final results:

Model has delivered accuracy that falls into a  60 - 90% range, at the same time the lowf1-score and ROC curve plots for the wanted class („Pants of fire”) showed that when finally tested, models achieved less than satisfactory predictions. 
