We can suggest engineering + machine learning Jargon in the proposal. However, I suggest we stick to the below for the 1 page proposal. 

1) Why there is a need to Move to Machine learning and AI based Fraud Detection Techniques in todays age.  ( Covered in some of Abhisheks Documents ) 
2) Why has it become easier now than before ? ( we can paraphrase this ) 
3) Why old methods are obsolete ? ( We can put some comparitive study ) 
4) Advantages of moving to Data Science based Fraud Detection Techniques ( We can put few points ) 
5) What we should do - > What can be done !! what Methods we can use ? ( Suggest machine learning techniques ) 

Also, it will be great if we can put some Positive numbers of improvement that can be affected using Machine learning. 

6) Not sure, if we should put what we will need ? such as system requirements , data requirements and Business insights.

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

https://www.marutitech.com/machine-learning-fraud-detection/

1. Logistic Regression (supervised)

Regression analysis is a popular, longstanding statistical technique that measures the strength of cause-and-effect relationships in structured data sets. Regression analysis tends to become more sophisticated when applied to fraud detection due to the number of variables and size of the data sets. It can provide value by assessing the predictive power of individual variables or combinations of variables as part of a larger fraud strategy. In this techniques, the authentic transactions are compared with the fraud ones to create an algorithm. This model (algorithm) will predict whether a new transaction is fraudulent or not. For very large merchants these models are specific to their customer base, but usually, general models will apply.

2. Decision Tree (unsupervised) 

This is a mature machine learning algorithm family used to automate the creation of rules for classification tasks. Decision Tree algorithms can use for classification or regression predictive modeling problems. They are essentially a set of rules which are trained using examples of fraud that clients are facing. The creation of a tree ignores irrelevant features and does not require extensive normalization of the data. A tree can be inspected and we can understand why a decision was made by following the list of rules triggered by a certain customer. The output of the machine learning algorithm might be a model like the following decision tree. This gives a probability score of fraud based on earlier scenarios.

3. Random Forest

Random Forest technique uses a combination of multiple decision trees to improve the performance of the classification or regression. It allows us to smooth the error which might exist in a single tree. It increases the overall performance and accuracy of the model while maintaining our ability to interpret the results and provide explainable scores to our users. Random forest runtimes are quite fast, and they are able to deal with unbalanced and missing data. Random Forest weaknesses are that when used for regression they cannot predict beyond the range in the training data and that they may over-fit data sets that are particularly noisy. Of course, the best test of any algorithm is how well it works upon your own data set.

4. Neural Networks

It is an excellent complement to other techniques and improves with exposure to data. The neural network is a part of cognitive computing technology where the machine mimics how the human brain works and how it observes patterns. The neural networks are completely adaptive; able to learn from patterns of legitimate behavior. These can adapt to the change in the behavior of normal transactions and identify patterns of fraud transactions. The process of the neural networks is extremely fast and can make decisions in real time.

