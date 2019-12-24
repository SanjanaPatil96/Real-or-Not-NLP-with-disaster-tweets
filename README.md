# Real-or-Not-NLP-with-disaster-tweets
### Predict which tweets are about real disasters and which ones are not.
### The dataset used in this project is from a Kaggle Competition.
### About the dataset: 
There are 2 csv files, viz train.csv and test.csv

#### Columns
id - a unique identifier for each tweet

text - the text of the tweet

location - the location the tweet was sent from (may be blank)

keyword - a particular keyword from the tweet (may be blank)

target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)

### Output
The Output file is submission.csv which contains 2 columns as id and target where the target has the value as 1 if the disaster is predicted to be real or it contains 0 if the disaster is not real.
