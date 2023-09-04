# Personal-Projects
This repository contains the scripts of my personal projects and practise scripts.

BeH - Questoin Clasifier
The train data consists of 3 columns. The second column is a question. The first column is class. The third column is Ans_Type.
Class column classifies the question based on the answer to the corresponding question. For example an answer to a question can be Entity, Description, Location etc.
The Ans_type further divides each class into different types. For example Entity can be animal, person, thing etc.
The model classifies unseen questions into these categories.
Corresponding code - BeH-Question Classifier

Computer Vision - Rice Grains
The train data consisted to twelve different images. Some imanges only had unbroken grains, some only had broken grains and some had both broken and unbroken grains.
I trained a yolov7 model on train images. Then classified rice grains in unseen images into broken and full grains. Also detected the number of grains of each class in these unseen images.
Corresponding code - Instance Segmentation, cv_rice grains

Entity extraction and sentiment Analysis of tweets on leukemia
The given data set consists of set of tweets on leukemia in different languages. Objective is to do entity extraction and sentiment analysis of the tweets.
I downloaded a dataset consisting of statements from different languages and used it to identify the language. Performed entity extraction on english tweets.
Then I performed sentiment analysis using two different methods.
Corresponding code - objective - 1 -NLP - entity extraction - english text, language identifier_dataframe, language recognition model - Akaike NLP assignment

