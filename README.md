# Yelp_Reviews_Usefulness_Predictor
Predict the usefulness of a Yelp review left by a user. Features used: number of exclamations, number of punctuations, rating difference between actual and overall, positive sentiment words, negative sentiment words  Accuracy: 61.61%

## Authors: Lisa Huang, Huihan Li, Mara-Steiu Florina

## CS 232: Artificial Intelligence

## Wellesley College

### raw files (in data.zip):
* useful650000.json: 650,000 English reviews of restaurants with "useful" votes, with length of 100-599 characters
* useless650000.json: 650,000 English reviews of restaurants without "useful" votes, with length of 100-599 characters
* businessJSON.json: all businesses collected from Yelp Dataset Challenge
* positive-words.txt: a list of POSITIVE opinion words
* negative-words.txt: a list of NEGATIVE opinion words

### data processing files:
* dataProcessor.py: a Python script that cleans the original 5 million review data based on certain conditions
* open_business.py: a Python script that loads businessJSON.json
* open_useful_reviews.py: a Python script that loads useful650000.json
* open_useless_reviews.py: a Python script that loads useless650000.json
* positive.py: a Python script that stores positive opinion words from positive-words.txt in a dictionary
* negative.py: a Python script that stores negative opinion words from negative-words.txt in a dictionary

### main file:
* play_with_model.py: a pilot model that has an accuracy of prediction of 54.5%; abandoned
* Yelp_review_Predictor.ipynb : the main file that deals with data analysis and cleaning, finding language features, training and testing on the model, and predicting new reviews

### other file(s):
* frequency.txt: the distribution of review lengths
