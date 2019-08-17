# NaturalLanguageProcessing
Data preprocessing with Natural Language Processing methods such as tokenizer, stopwords, PorterStemmer, bag of words etc. to clean and make data clear. Then, Some Machine Learning Algorithm were applied. 

.csv data file was simplified some rows were deleted by hand. Others were done at pre-processing part.

1. In order to feed the applied machine learning algorithms with our textual data as input, it is needed to change the form of representation of the text data. You are expected to use the Bag-of-Words model to encode text data to a list of vectors of features.

2. After having the text data with the proper form of representation, you are expected to apply Linear Regression, Naive Bayes, SVM and kNN algorithms.

3. For each applied algorithm, you are expected to list Accuracy, Precision, Recall and F1 score points.

4. As the last step, you are required to create a function which takes two parameters that are randomly selected reviews from your dataset and compares the similarity of the sentences semantically. You are expected to use WordNet to compute the similarity of the sentences, since it is well-known and extensively used in the community.


For some help, following resources that explain the above mentioned techniques for practical purposes.

https://scikit-learn.org/stable/modules/feature_extraction.html
https://medium.freecodecamp.org/an-introduction-to-bag-of-words-and-how-to-code-it-in-python-for-nlp-282e87a9da04
http://zacstewart.com/2015/04/28/document-classification-with-scikit-learn.html
https://scikit-learn.org/stable/modules/naive_bayes.html
https://blog.exsilio.com/all/accuracy-precision-recall-f1-score-interpretation-of-performance-measures/
https://scikit-learn.org/stable/modules/svm.html
https://scikit-learn.org/stable/modules/neighbors.html
http://www.nltk.org/howto/wordnet.html
