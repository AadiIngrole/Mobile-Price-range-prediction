
<h1 align='center'> Mobile Price Range Prediction</h1>
<img align='right' height ='300' src='https://media.giphy.com/media/63I6FXZTXks2A/giphy.gif'>
<h2>Problem Statement</h2>
<h2>📱 Problem Statement</h2>
In the competitive mobile phone market
companies want to understand sales data of
mobile phones and factors which drive the
range indicating how high the price is. <br>
<br>
The main objective of this project is to build a model which will classify the price range of mobile phones based on the specifications of
mobile phones.
<h2>Data Description</h2>
<h2>📱 Data Description</h2>
Total Rows= 2000<br>
Total features=21<br>

not.
variable with value of 0(low
cost),1(medium cost),2(high cost)
and3(very high cost)
<h2>Algorithms Used</h2>

<h2>📱 Algorithms Used</h2>

We experimented with various models
such as

* Gradient Boosting Classifier
* XGBoost Classifier
* KNN
<h2>Conclusion</h2>
Implemented various classification algorithms,out of which the SVM (Support vector machine) algorithm gave the best performance after hyper-parameter tuning with 98.3% train accuracy and 97 % test accuracy.

In all of these models our accuracy revolves in the range of 70 to 74%.

KNN gave very worst model performance. We checked for the feature importances of each model. RAM, Battery Power, Px_height and px_widthcontributed the most while predicting the price range.
