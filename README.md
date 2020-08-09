# Winning Solution for the Basic Needs Basic Rights NLP Challenge hosted in [Zindi](https://zindi.africa/competitions/basic-needs-basic-rights-kenya-tech4mentalhealth/leaderboard)

## Competition Goal
The objective of this challenge is to develop a machine learning model that classifies statements and questions expressed by university students in Kenya when speaking about the mental health challenges they struggle with. The four categories are depression, suicide, alchoholism, and drug abuse. 

This solution will be used for a prototype of a mental health chatbot designed specifically for university students. This initiative is a first step in leveraging technology to make mental health services more accessible and more user-friendly for young people in Kenya and around the world.

## Competition metric
The evaluation metric for this challenge is Log Loss.

## Data

The data consists of statements and questions expressed by students from multiple universities across Kenya who reported suffering from these different mental health challenges.

The wording of the statements is intended to respond to the prompting question, “What is on your mind?”

Note that the written statements may include some spelling or grammatical errors, as well as slang. Also note that labels were not assigned to the statements, but rather students provided statements and questions about their particular experience.

The labels for the training set are contained in Train.csv, corresponding to one of the four categories of mental health problems (depression, suicide, alchoholism, and drug abuse). Your task is to develop a machine learning model to predict the labels for the test set, following the format in sample_submission.csv.

### Files available for download

* **Train.csv** - has the unique ID of each statement along with the label. You will use this file to train your model on.
* **Test.csv** - has the unique IDs you will be testing your model on.
* **SampleSubmission.csv** - is an example of what your submission file should look like. The order of the rows does not matter, but the order of the columns (Depression, Alcohol, Suicide, Drugs) must be the same as the sample submission. Your submission should contain probabilities that the ID is of each category (with values between 0 and 1 inclusive). The values across the columns do not have to add up to 1.


## Prerequisites
You can run it on Google Colab or using Kaggle Notebooks.

## How to run it ?
* Download the data files from [here](https://zindi.africa/competitions/basic-needs-basic-rights-kenya-tech4mentalhealth/data).
* Upload all files on your Google Drive.
* Upload the notebook on your Google Drive.
* Fill "comp " variable with your data path on your Google Drive.
* Run it !
