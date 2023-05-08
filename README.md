# MINE vs Rock Prediction using sonar data

## About

Outwardly SONAR technique has
exploited the discovery of rocks and minerals
which would have been very difficult otherwise.
The technique exploits certain parameters which
will aid to detect the surface targets or obstacle
such as a rock or a mine. Machine learning has
drawn the attention of maximum part of today’s
emerging technology, related from banking to
many consumer and product based industries, by
showing the advancements in the predictive
analytics. This prediction can be done using machine learning algorithm such as logistic regression which is implemented in google colab.
 
 
## Model
The model used here is  **Logistic Regression**. Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable. Logistic Regression uses a sigmoid or logit function which will squash the best fit straight line that will map any values including the exceeding values from 0 to 1 range. So it forms an “S” shaped curve. Sigmoid func. removes the effect of outlier and makes the output between 0 to 1.
As it a binary classification model it is perfect to predict if an object is mine or rock based on the sonar data.


## DataSet
The dataset has
been collected from UCI Repository. It has come
across 61 features which define and differentiate
Rocks and Mines and comprises of 208 samples. 
This data is used for training and testing purpose. The Last column in this dataset 
indicates that, whether it's a mine or a rock, which is useful in prediction.
The dataset is included in this repository.
*	Data is collected and is in CSV format.
*	There are all total of 208 data points.
*	If we see the last column of every data point its mentioned R or M.
*	R denotes Rock and M denotes Mine.
*	Since we already know the results from the beginning, we can say it’s a Supervised learning algorithm.
 
