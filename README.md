# TFM-Sentiment-analysis-with-tweets

In this repository you will find notebooks about Sentiment analysis with tweets 

To work on it, it is needed Python 3 and also to install all libraries contained at 0_Requirements.txt

It is recommended to execute each notebook attending to the following order:

0_Tweets_Extractor

1_Preprocessing_Tweets

2_Data_Cleansing

3_Data_Exploration

4_Training_models

At the data folder, there are csv files with all data needed to execute the notebooks. The original data are a total of 33.130 registers and 20 columns with information about tweets that were collected from Twitter.


- Tweets: text.
- Tweet_long: length.
- Id: tweet identification number.
- Created_date: post date.
- Source: origin source.
- Likes: .
- RTs: total number of retweets.
- Language: tweet language.
- Place: location where the tweet have been published.
- User_id: user identification.
- User_name: user name.
- User_description: information about user.
- Followers: number of followers.
- Followings: number of users who follow the user author.
- User_lists_member: 
- User_total_favourites_count:
- User_statuses_count:
- User_created_account: creation date of the account.
- User_location: user original location.
- User_lang: user original language.


Some notes about notebooks:

0_Tweets_Extractor: process to collect tweets from Twitter using Tweepy API.

1_Preprocessing_Tweets: some data processing and transformations.

2_Data_Cleansing: normalization and removing data to get the final dataset.

3_Data_Exploration: analisys about information observed in the dataset.

4_Training_models: contains vectorization process, train and test sets split, training models, evaluation of best models and some final conclusions of this work.



