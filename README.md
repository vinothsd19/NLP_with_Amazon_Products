# NLP with Amazon Products

**Aim:**

The main purpose of this paper is to perform sentiment analysis on Amazon product reviews and classify each review into positive , negative or neutral sentiment. 

**Research Questions:**

-Which pre-processing methods give better results when passing pre-processed data to ML Model?

-What are the suitable Machine Learning models?

**Application of Data mining techniques to predict sentiment of Amazon product reviews:**

-Implementation of CRISP-DM method

-Business Understanding , Data Understanding

-Pre-processing techniques: Text-Blob , NLTK -Natural Language Toolkit , SpaCy


**Building Statistical Models and its Evaluation:**

-Vectorizing methods: Count-Vectorizer and TfidfVectorizer

-Models – Logistic Regression(Multinomial) , Multinomial Naïve Bayes, Random Forest ,XGBoost

-Evaluation – Accuracy Train , Accuracy Test , Precision , Recall and F1 Score

**Results and Findings**

-F1 Score is the used to determine the best performing model because the score provides the Harmonic mean of Accuracy and Precision of a given model

-The best performing model is XG-Boost with Text-Blob  and coming to Vectorizers both gives the same F1 score of 95% and detects neutral labels better than other models

-For some reviews users give 3 star which is assigned as neutral label but has positive review and the user rating is 4 but has neutral review

-Words like  good , better , great followed by could , will , would, makes the model to predict the review as Positive instead of Neutral or Negative

-Long sentences need to be split into short sentences to detect the sentiment properly

