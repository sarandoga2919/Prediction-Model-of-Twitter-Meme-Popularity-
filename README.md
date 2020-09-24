# Prediction-Model-of-Twitter-Meme-Popularity-
Prediction Model of Twitter Meme Popularity (Camargo, S., 2020) 

##### Abstract

Over time, social networks have transcended and changed (among many things) the way we
communicate, perceive and shared information. The same process has been followed by the
concept of ‘Meme’. From 1976, the Meme concept has adapted, until reaching the meaning we
know it for today.
The virus-styled way Memes replicate through social networks is what makes them such an
appealing matter of study. This paper aims to predict the virality of Memes in one of the principal
and most spread social media platforms of information diffusion and mass communication,
Twitter.
One of the objectives of this paper is to perform a comparative analysis of three classification
algorithms, namely, Random Forest, Decision Tree and K-Nearest neighbour. In this paper, a
dataset was developed upon an existing dataset in ‘Kaggle’, and data crawling was done through
Twitter API. Also, a comprehensive set of specific features for defining Meme popularity was
added.
These features were taken from a 2014 research focused on viral Memes (“Predicting successful
Memes using network and community structure”). Furthermore, new features were included, like
popular tags to identify each Meme and type of Meme.
The final dataset contains 505 instances, 36 features and 4 classes. In the methodology section,
this paper shows the tables for the comparison of the accuracy of the machine learning algorithms
mentioned before using both cross-validation and 66% split before and after applying the feature
selection algorithm technique.
Finally, the paper concludes with the recommendation of new features, not previously considered,
such as popular tags and the type of the Meme to improve the accuracy of the prediction model.


##### Codes:  

The python files included in this repository are: 

Collecting_memes: This code used to collect part of the network and growth features information such as early adopter, early tweets, avg_time_duraction and  cv_time_duration.

Distance_feature: This will provide Distance features such as Average step distance, Coefficient of variation of step distances and Diameter. 

Community_feature: This will provide Community features such as Number of infected communities, usage and adopter entropy 

##### Dataset: 

meme_final_dataset: this was created by merging the dataset from kaggle:https://www.kaggle.com/podsyp/a-lot-of-memes-info-stats and  the retrieved data from Twitter API using ‘collecting_memes’ codes

Dataset_Weka: This is dataset was use to build the model, with 505 instances, 36 attributes named from X1 to X36 which corresponded, respectively, as follows: origin year, num_early_adopters, num_early_tweets, avg_time_duraction, cv_time_duration, type, popular tags from X7 to X36. 

