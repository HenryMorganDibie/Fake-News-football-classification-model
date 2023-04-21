# Fake-News-football-classification-model
I built a classification model that can accurately detect whether the news is real or fake.

## Here is a summary of everything I have done so far:

* I loaded two datasets of real and fake tweets respectively.
* I merged the two datasets into one dataframe and cleaned it, thereafter I 
did some basic EDA to understand the structure of the data, including checking the data types, missing values, and duplicates.
* I did some further EDA on the combined dataset, including creating word clouds, frequency plots, and distribution of tweet lengths.
* I also performed language analysis and user analysis to extract the most common languages used and the most active users in the dataset.
* I then used the NLTK library to preprocess the text data, including removing stop words, punctuation, and stemming the words.
* I experimented with different machine learning models such as logistic regression, decision tree, and random forest. I also compared their performances using evaluation metrics such as accuracy, precision, recall, and F1-score.
also, I to fine-tuned the models by adjusting hyperparameters, performing feature engineering, and implementing cross-validation. 
* I then selected logistic regression model as it was the best performing model on the preprocessed data, so I evaluated its performance using cross-validation.
* Finally, I did some error analysis on the misclassified samples to gain insights into the weaknesses of the model and potential ways to improve it.
Overall, I have done a comprehensive analysis of the tweet dataset, including data cleaning, exploratory data analysis, text preprocessing, and model training and evaluation. 
