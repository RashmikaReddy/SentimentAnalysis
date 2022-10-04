# SentimentAnalysis
Performed Sentiment Analysis on IMDB movie reviews dataset
Dataset location : https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

Steps Followed 
1. Imported the Dataset
2. EDA - Created a graph for the positive and negative sentiments
3. Used CountVectorizer to create BOW, Used RegexpTokenizer, stop_words, ngram_range and created a model of CountVectorizer, fit the model with the review column of input data
4. Perform train test split, create a Multinomial Naive Bayes Classifier
5. Fit the training data, predict for test data, calculate accuracy
6. In the text preprocessing step of creating BOW using CountVectorizer, ngram_range is changed to (1,2) which resulted in accuracy increase by 3%
7. Instead of BOW - CountVectorizer, created the data using TF-IDF, passed the same hyper parameters for it, the accuracy is almost the same
Naive Bayes,  is the baseline model for text classification, because of its conditional independence of features which results in greater accuracy. 
We can also use other classification algorithms like Logistic Regression

TO DO
1. Implement using Support Vector Machine, SGD Classifier
2. Explore different types of Naive Bayes Classifiers like Gaussian, Bernouli...
