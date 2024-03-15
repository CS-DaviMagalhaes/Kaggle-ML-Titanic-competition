This was my **first ML project**, part of a introduction competition on kaggle titled *Titanic - Machine Learning from Disaster*. I've done this just after reading the second chapter of the book *Hands-On Machine Learning with Scikit-Learn,
Keras, and TensorFlow* by Aurélien Géron. I still have a lot to learn.

Clearly there is some overfitting for the training data since my accuracy on the training test was 100% but my actual (best) submission accuracy had 77% accuracy. 
I've submitted other versions trying to improve my score with the following strategies:

* Cleaning more outliers (age, fare, Parch)
* Not cleaning outliers
* Feature engineering (created a family_size attribute, Parch+SibSp+1)
* Using different models (RandomTreeRegressor, LinearRegression)
* No scaling (After a few submissions I realized that I wasn't scaling variables lol)
* Handling categorical attributes differently or excluding them

I also tried combinations between those versions. All of them got me a worse score. 

Investigating further on kaggle's discord I've found that this is a good score using only this dataset and a single model.
Higher scores on the competition were generally obtained by merging the training set with another external dataset, ensembling ML models or just straight up submitting the answer to get 100% accuracy. 
Since it's my first ML project I'm pretty happy.

**The paths and directories for the training, test, and output files are the ones I had on Kaggle's code editor, I just downloaded the files that I submitted on Kaggle's platform.**
If you want to run this code make sure to change the directories to where you have the training and test datasets.

[Competition Link](https://www.kaggle.com/competitions/titanic/overview)
