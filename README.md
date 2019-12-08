# CS6120_Final_Project
PLEASE SEE README.txt which is formatted properly.
This contains the final project for the course CS6120
CS6120: Final Project
We would like to thank Professor Lu Wang for encouraging us to take up this topic and present it as a final project.
In this project,we have explored the Paraphrase Identification
problem using Feature based classifiers and a Deep Learning Model called Siamese Manhattan LSTM.
We have used the Quora Question Pair dataset for the same.
The results are as gathered in the Final Project Report.

WORK SPLIT UP:
Preprocessing,EDA - Nanditha , Mayanka
Feature Extraction - Nanditha
Feature Importance - Mayanka
Feature Based Classifiers - Mayanka
Siamese Manhattan LSTM - Nanditha

1.SETUP:
The project requires the following software packages:
1.Python 3.x
2. The dependencies are included in the depend.txt file
To install the packages use :
pip install -r depend

2.STRUCTURE:
The project is divided into two parts:
a)Preprocessing,EDA,feature extraction and building feature based classifiers and performing evaluation
b)Preprocessing,building Siamese Manhattan Neural model and performing evaluation
The project contains three folders - Data,Code,model_dump.
1.Data- contains the data (question.csv)
2.Code- contains the following files
 There are two python files associated with each of the above mentioned tasks(a,b),namely:
1)eda_feature_based_classifier.py
->ABOUT: Deals with preprocessing,Exploratory Data Analysis,Feature Extraction(basic features,fuzzy features and word2vec features),
	Feature selection,Implementation of feature-based classifiers like Logistic Regression,Random Forest andEvaluation of the models.
->OUTPUT: EDA Results as mentioned in the report, Evaluation metrics for Logistic Regression on validation and test set and Evaluation metrics for Random Forest on validation and test set.
2)siam_lstm.py
->ABOUT: Deals with preprocessing,converting word sequences into embeddings,fitting a Siamese MaLSTM model on the data and evaluating it on the test set.
->OUTPUT: Generation of Embeddings matrix using GloVe,Construction of Siamese MaLSTM model and evaluation metrics for the model on Validation and test set.
3.model_dump: This file contains:
a)model.json - dump of the siamese MaLSTM model-> needs to be trained on the training data
b)logistic_model.sav - logistic regression model
c)random_forest_model.sav - random forest model
d)word_indx.json - contains the word and their indices.This is needed for getting the word embeddings for our neural model.
3.EXECUTION:
To see the result ,run each of the above mentioned file as:
python filename.py
4.DEPENDENCIES INSTALLATION:
pip install -r depend

5.CITATIONS:
1. TAs Guidance in debugging
2. stackoverflow.com
3. Tutorialspoint.com/python
4. https://web.stanford.edu/~jurafsky/slp3/ed3book.pdf
5.Professor Lu Wang
6.Scikit documentation
7.keras documentation




	
