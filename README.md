# Analysis on Amazon reviews

We are taking into account 2 datasets. The first one contains the reviews of the customer and the second one is all about the model and its price. Our dataset comes from Consumer Reviews of Amazon Products1 . This dataset has 82816 data points in total. Each example includes the asin number, name of the person as well as the text review and the rating of the product. To better utilize the data, first we extract the rating and review column since these two are the essential part of this project. Then, we found that there are some data points which has no ratings when we went through the data. After eliminating those examples, we have 82816 data points in total.

STATISTICS BEHIND THE ANALYSIS-

In simple classifier model, a simple count of positive and negative data points will define overall positive or negative sets. There is a problem with this.Classifier model boundaries can be a simple line to separate “positive” from “negative” outcome to more complex hyperplane to separate multiple groups.


INTRODUCTION: 

I have worked on the Amazon review dataset. The main purpose of this project was to play with the dataset and figure out various analysis using the tools available. I have tried using the basic tools that were available to me and try and make it less complicated. I have used 3 classifiers and Topic Modeling to form my analysis.

EDA: 

I began with print the number of occurrences of certain ratings to begin with. With 1 being the worst rating and 5 being the best and I realized that most Amazon reviews are highly positive which is good for their market standing.I then tried plotting the verified and the not verified ratings just to see if all the ratings were true, turns out that they are not.
It turns out that there are many unverified positive ratings as well as extremely negative ratings, could be the competitors I believe.

Models Used-
1. Logistic Model
2. multinomialNB Classifier
3.


References:

 

https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/

https://towardsdatascience.com/end-to-end-topic-modeling-in-python-latent-dirichlet-allocation-lda-35ce4ed6b3e0

https://stackoverflow.com/questions/23455728/scikit-learn-balanced-subsampling

https://towardsdatascience.com/linear-classifiers-an-overview-e121135bd3bb

http://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html

 

 

Name: Mumtaz Uddin

Major: Data Science

