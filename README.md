# Sentiment-Analysis-of-Movie-Reviews
In this project I built a logistic regression classifier using scikit-learn to classify movie reviews as negative or positive. The project was divided into the following steps:

Step 1: Transforming Documents into Feature Vectors
Represented text data using the bag-of-words model.
Constructed the vocabulary of the bag-of-words model and transformed sample sentences into sparse feature vectors.

Step 2: Term Frequency-Inverse Document Frequency

Step 3: Calculate TF-IDF of the Term 'Is'
Applied scikit-learn’s Tfidf Transformer to convert sample text into a vector of tf-idf values and applied the L2-normalization to it.

Step 4: Data Preparation 
Removed HTML tags, punctuation, and emojis using regular expressions.

Step 5: Tokenization of Documents

Step 6: Document Classification Using Logistic Regression
Split the data into training and test sets of equal size and employed cross-validated grid-search over a parameter grid

Step 7: Model Accuracy
Checked for accuracy of the results from the test set

Step 8: Recall and precision values 

Step 9: Plotting of ROC curve



