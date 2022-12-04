# Email-Spam-Classifier

Naive Bayes is a supervised classification method based on the Bayes Theorem with the presumption of predictor independence. This means that a Naive Bayes classifier makes the assumption that the existence of one feature in a class has nothing to do with the presence of any other feature.

It is a common method for text classification that uses word frequencies as characteristics to determine whether documents fall into one category or the other (such as spam or genuine, sports or politics, etc.).

**Goal:** Previously unseen records should be assigned a class as accurately as possible

* We have a several emails determined as ['spam']
and a several emails determined as ['non-spam']

* After being read, the emails are initially saved in a dataframe. 

* This data is used to train the model, and its predictions are then evaluated using a sample input once they have been processed using CountVectorizer.

**Python Libraries used:** pandas, numpy, scikit-learn

### Some Practical Applications:
* Direct Marketing
* Fraud Detection
* Text Classification
* Spam Filtering
