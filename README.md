ud120-projects  
==============  
  
Starter project code for students taking Udacity ud120  
  
  
Note on Machine Learning:  
  
Lesson 2: Naive Bayes  
1. 2 parts: Data & Labels  
  
2. Classifier:  
> train/fit  
> predict  
Using sklearn library  
from sklearn.naive_bayes import MultinomialNB  
from sklearn.naive_bayes import GaussianNB  
from sklearn.metrics import accuracy_score  
clf = GaussianNB()  
clf.fit(X_train, y_train)  
pre = clf.predict(X_test)  
accuracy = accuracy_score(pre, y_test)  
or: accuracy = clf.score(X_test, y_test) #this one no need predict
  
Naive Bayes: Naive means ignore word order
