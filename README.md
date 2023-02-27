# IdentifyTheSentiments
The problem statement for this sentiment analysis project is described here in https://datahack.analyticsvidhya.com/contest/linguipedia-codefest-natural-language-processing-1/. To solve the problem, I have implemented various NLP methods, which can be found in the .ipynb file. I have extracted different new features like total number of words, characters, stop words for each tweet. I have also removed URLs from those tweets, removed ten most occurring words, ten least occurring words and stop words from each tweet. Later, I converted all the words in their base forms. After these pre processing and features extraction steps, I converted the tweets in to tfidf features with constraint of max number of features set to 10000. I concatenated previous extracted features with these tfidf features and fed them to a multinomial Naive Bayes algorithm to predict the output for the test cases, which gave an accuracy score of .8857 for this binary classification problem. Finally, I created a .csv file with the predicted 0 or 1 result from the model. Here, 0 is considered as positive and 1 as negative review.  
