# Prediction-Model-of-Twitter-Meme-Popularity-
Prediction Model of Twitter Meme Popularity (Camargo, S., 2020) 

##### Abstract

Over time social networks have transcended and changed, among many things, the way we communicate, perceive and spread the information and in the same way it has happened with the concept of the meme from 1976 to what we know today as a meme. The way it is replicated through social networks is what makes it appealing to be a subject of study. This paper aims to predict the virality of memes in one of the principal platform of information diffusion, Twitter. One of the objectives of this paper is to perform a comparative analysis of three classification algorithm namely, Random Forest, Decision Tree and K-Nearest neighbour. In this paper, it was created a dataset based on an existed dataset in Kaggle, crawl data in Twitter API and designing a comprehensive set of specific feature for meme popularity, taking them from the characterisation of viral meme published in previous research in 2014 and also including new features like popular tags to identify the meme and type of the meme. The final dataset contains 505 instances, 37 features and 4 classes. In the methodology section, this paper shows the tables for the comparison of the accuracy of the machine learning algorithms mentioned before using both cross-validation and 66% split before and after applying feature selection algorithm technique. Finally, the paper concludes with the recommendation of news features that were not previously considered such as popular tags and the type of the meme to improve the accuracy of the prediction model.


##### Codes:  

The python files included in this repository are: 

Collecting_memes: This code used to collect part of the network and growth features information such as early adopter, early tweets, avg_time_duraction and  cv_time_duration.

Distance_feature: This will provide Distance features such as Average step distance, Coefficient of variation of step distances and Diameter. 

Community_feature: This will provide Community features such as Number of infected communities, usage and adopter entropy 

##### Dataset: 

meme_final_dataset: this was created by merging the dataset from kaggle:https://www.kaggle.com/podsyp/a-lot-of-memes-info-stats and  the retrieved data from Twitter API using ‘collecting_memes’ codes

Dataset_Weka: This is dataset was use to build the model, with 505 instances, 36 attributes named from X1 to X36 which corresponded, respectively, as follows: origin year, num_early_adopters, num_early_tweets, avg_time_duraction, cv_time_duration, type, popular tags from X7 to X36. 

