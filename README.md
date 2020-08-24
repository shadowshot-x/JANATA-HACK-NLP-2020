## HOW TO INSTALL ON YOUR LOCAL MACHINE


# JANATA-HACK INDEPENDENCE DAY ML HACKATHON

Rank on Leaderboard - 36/400

Kaggle Link to the winning approach( Please upvote if helpful) :- [83.92 - LinearSVC with hinged loss](https://www.kaggle.com/ujjwalsharma26/janata-hack-ml-83-92-rank-36) 

Models Applied :-
----------

1.  Deep Learning  
    
    -   One Layer CNN Model with GloVe ( 0.8029 ) and without GloVe ( 0.7973 ) 
    -   [One Layer BiLSTM Model with GloVe ( 0.8083 ) without GloVe ( 0.7974 ) ](https://github.com/shadowshot-x/JANATA-HACK-NLP-2020/blob/master/deep-learning-approach-janata-hack-80-8.ipynb)
    -   One Layer BiGRU Model with GloVe ( 0.7924 )
    
I could not get past this accuracy with Multiple trials and different hyperparameters. Saw an immense jump of models from around 75% to 80% with text cleaning (Helped convergence of loss of the training set and prevent overfitting)
    

----------

2.  Machine Learning
    -   Naive Bayes with CountVectorization ( 0.8028 )
    -   Logistic Regression with TFIDF( Word Level ) ( 0.7989 )
    -   Linear SVC with TFIDF and fit_intercept_False ( 0.808 )
    -   Linear SVC with TFIDF and fit_intercept_False with hinge loss! ( 0.8190 )
    -   [Linear SVC with TFIDF and fit_intercept_False with hinge loss word level n gram with Separate Predictions. ( 0.8360 )](https://github.com/shadowshot-x/JANATA-HACK-NLP-2020/blob/master/JANATA_HACK_without_multout_LinearSVC.ipynb)
    -   [Linear SVC with TFIDF and fit_intercept_False with hinge loss word level n gram with MultiOutput Classifier! ( 0.8392 )](https://github.com/shadowshot-x/JANATA-HACK-NLP-2020/blob/master/janata-hack-ml-83-92-rank-36.ipynb)

Got results with hyperParametric tuning of CountVectorizer, TFIDFTransformer and LinearSVC

-------
Winner of the Whole competition was BERT and I look forward at exploring that area soon!

### Problem Statement :-
## Topic Modeling for Research Articles

Researchers have access to large online archives of scientific articles. As a consequence, finding relevant articles has become more difficult. Tagging or topic modelling provides a way to give token of identification to research articles which facilitates recommendation and search process.

Given the abstract and title for a set of research articles, predict the topics for each article included in the test set.

Note that a research article can possibly have more than 1 topic. The research article abstracts and titles are sourced from the following 6 topics:

1. Computer Science

2. Physics

3. Mathematics

4. Statistics

5. Quantitative Biology

6.  Quantitative Finance
