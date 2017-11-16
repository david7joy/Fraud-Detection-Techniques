# Fraud-Detection-Techniques

Techniques used for fraud detection fall into two primary classes: statistical techniques and artificial intelligence.[3] Examples of statistical data analysis techniques are:

1) Data preprocessing techniques for detection, validation, error correction, and filling up of missing or incorrect data.
2) Calculation of various statistical parameters such as averages, quantiles, performance metrics, probability distributions, 
   and so on. For example, the averages may include average length of call, average number of calls per month and average 
   delays in bill payment.
3) Models and probability distributions of various business activities either in terms of various parameters or 
   probability distributions.
4) Computing user profiles.
5) Time-series analysis of time-dependent data.
6) Clustering and classification to find patterns and associations among groups of data.
7) Matching algorithms to detect anomalies in the behavior of transactions or users as compared to previously known models 
   and profiles. Techniques are also needed to eliminate false alarms, estimate risks, and predict future of current 
   transactions or users.
   
Fraud detection ( Anomaly detection in Machine learning ) 

This is due to the following characteristics:
The number of positive cases (fraudulent attempts) are small
The application involves deviation from the normal pattern
   

Supervised learning
1) In supervised learning, a random sub-sample of all records is taken and manually classified as 
   either 'fraudulent' or 'non-fraudulent'
2) These manually classified records are then used to train a supervised machine learning algorithm.
3) After building a model using this training data, the algorithm should be able to classify new records as 
   either fraudulent or non-fraudulent.
4) Bayesian learning neural network is implemented for credit card fraud detection

Here’s an example of unsupervised and supervised models in action. For two financial services clients,
we developed unsupervised (Markov) models that estimate the likelihood of a sequence of actions being fraudulent. 
A typical sequence for an online banking customer might be “login, check account balance, transfer money to a 
known beneficiary, logout.” Since that sequence would appear frequently, it would have a low likelihood of being 
fraudulent and would receive a low score. But what if the sequence was instead, “log in, password change, email change, 
add a new beneficiary, transfer money, delete beneficiary, logout”?That is an atypical sequence and would result in a 
high score indicating fraud.

Micro-models, as the name implies, break down the fraud-detection problem into small areas for analysis.
For instance, we’ll build a binary classification (supervised) model that’s just for identifying whether an email address 
is bad or not, or whether an IP address is a botnet. Then we build an ensemble model comprising many such micro-models.
The micro-models are easy to build, train, and update, and together, the ensemble is highly effective.
