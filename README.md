# Text-Mining

This project regards a analysis over airbnb assets and reviews in order to detect if assets should or not be unlisted of the site.


## Introduction
Your solution should present the following points:

__1. Data Exploration:__

Here you should analyze the corpora and provide some conclusions and visual information (bar charts, word clouds, etc.) that contextualize the data.

__2. Data Preprocessing:__

You must apply a method to split your training corpus into train/validation sets to evaluate the performance of your model (you can also resort to KFold cross validation, or other methods). Moreover, you must correctly implement and experiment at least four (4) of the data preprocessing techniques shown in class (stop words, regular expressions, lemmatization, stemming, etc.).

__3. Feature Engineering:__

You must correctly implement and experiment with two (2) of the feature engineering techniques seen in class (TF-IDF, GloVe embeddings, etc.).

__4. Classification Models:__

You must correctly implement and test three (3) of the classification algorithms seen in class (KNN, LR, MLP, LSTM, etc.).

__5. Evaluation:__

You must evaluate your models resorting, at least, to Recall, Precision, Accuracy and F1-Score. Moreover, the development of extra work (more techniques than the minimum required in the previous points and/or techniques not shown in class) is highly recommended and will account for a maximum of 4.5 points divided as follows:

1. Data Preprocessing – 0.25 points for each extra method (unseen in class) used (maximum of 2 extra methods).

2. Feature Engineering – 1 point for each extra method using Transformed-based embeddings (maximum of 2 extra methods)

3. Classification Models – 1 point for each extra

___

## 📖 Data
The data is divided in following sets:

__Train (train.xlsx) (12,496 lines):__
Contains the Airbnb and host descriptions (“description” and “host_about” columns), as well as the information regarding the property listing status (“unlisted” column). A property is considered unlisted (1) if it got removed from the quarterly Airbnb list and it is considered listed (1) if it remains on that same list.

__Train Reviews (train_reviews.xlsx) (72,1402):__
This file has all the guests’ comments made to each Airbnb property. Note that there can be more than one comment per property, not all properties have comments, and comments can appear in many languages!

__Test (test.xlsx) (1,389 lines):__
The structure of this dataset is the same as the train set, except that it does not contain the “unlisted” column. The teaching team is keeping this information secret! You are expected to provide the predicted status (0 or 1) for each Airbnb in this set. Once the projects are delivered, we will compare your predictions with the actual (true) labels.

__Test Reviews (test_reviews.xlsx) (80,877):__
The structure of this dataset is the same as the train reviews set, but the comments correspond to the properties present on the test set

___

## Results

<img src="https://github.com/joaomalho/Text-Mining/blob/main/cm_NLP.png?raw=true" width="400"/>

<img src="https://github.com/joaomalho/Text-Mining/blob/main/rf_NLP.png?raw=true" width="400"/>
