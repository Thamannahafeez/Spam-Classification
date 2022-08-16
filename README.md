# Classification Of Messages -  Classification Problem

## Introduction

The Spam classification projectis done as part of my self learning process intext analysis and NLP.

The dataset used is a set of tagged messages that have been collected for Spam research. It contains one set of 5567 messages in English, tagged acordingly being ham (legitimate) or spam.

## Problem Description

The goal is to predict the binary class ' Class ', which represents whether the message is SPAM or HAM.
-  0 represents HAM
-  1 represents SPAM

## Dataset

There are 2 columns and 5567 entries in the dataset.
The dataset was provided as a tsv file. 

## Plan of Action

* Firstly, The messages are read and feature engineering has to be done on the data and this is an important part of spam detection in general. As from continuosly performing EDA it leads us to start thinking about the features that we are going to use. Here comes the general idea of feature engineering. The better our domain knowledge on the data, the better our ability to engineer more features from it.

* Secondly, Tokenization, Cleansing and Vectorizing of the messages are done.

* Finally, after the data wrangling is done, the machine learning models will be built to predict the spam/ ham. 

Four models were built initially and one among these is finalised based on its higher accuracy. 

The final model gave an accuracy of 99%.
