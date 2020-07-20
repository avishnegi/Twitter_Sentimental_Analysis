# Twitter_Sentimental_Analysis
PROBLEM STATEMENT:<br>

In this project , the objective is to analyse the tweets whether they are positive , negative or neutral using Naive Bayes Algorithm.<br>

ABSTRACT:<br>

In the past few years, there has been a huge growth in the use of microblogging platforms such as
Twitter. Spurred by that growth, companies and media organizations are increasingly seeking ways
to mine Twitter for information about what people think and feel about their products and services. 
It is not an exaggeration to say that people tweet about anything and everything. Therefore, to be able to build
systems to mine Twitter sentiment about any given topic, we need a method for quickly identifying
data that can be used for training. We explore one method for building such data:
using Twitter hashtags (e.g., #bestfeeling, #epicfail, #news) to identify positive, negative, and
neutral tweets to use for training threeway sentiment classifiers.<br>

METHODOLOGY:<br>

We will use machine learning techniques like Naive Bayes Algorithm to solve this problem.<br>

DATASET:<br>

For this project , I have used Twitter API . <br>

ALGORITHM USED:<br>
Naive Bayes Classifier is a classification algorithm that relies on Bayes’ Theorem. This theorem provides a way of calculating a type or probability called posterior probability, in which the probability of an event A occurring is reliant on probabilistic known background (e.g. event B evidence). For example, if Person_X only plays tennis when it is not raining outside, then, according to Bayesian statistics, the probability of Person_X playing tennis when it is not raining can be given as:<br>

 TP(X plays | no rain) = P(no rain | X plays)*P(x plays)/P(no rain)<br>
 
 following Bayes’ theorem:<br>
                           
  P(A|B) = P(B|A)*P(A)/P(B)<br>
                                     
 PROCEDURE FOLLOWED:<br>
 
 For this project , firstly I have created Twitter account so as I can use the Twitter API .<br> Then i have created the Test set for the project.<br> After this the Training set is also required . <br>
 When I have created the train and test set then I proceeded to the next step that was Data Preprocessing and have to preprocess the tweets in the dataset .<br> Then I have applied the algorithm Naives Bayes .<br>
 Then I have classifed the tweets whehter the are positive , negative or neutral. <br>
 
 RESULT:<br>
 
 I have searched the keyword CORONA VIRUS over the 1000 tweets and got the percentage of tweets that are positive , negative and neutral.<br>
 
 7.80% - positive<br>
20.20% - positive<br>
 1.60% - strongly positive<br>
 4.20% - negative<br>
 7.90% - weakly negative<br>
 1.70% - strongly negative<br>
56.60% - neutral<br>
                                     
                                     

