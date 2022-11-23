# myCapstoneProject
Capstone Project from Brainstation Bootcamp
Problem Statement:
FIFA should aim to constantly improve the fan experience of the FIFA World Cup. 
Fans throughout the world express their opinions of aspects of the World Cup through Twitter and thus there is a large amount of data that can be analyzed to 
gain insights into the opinions of fans and be used to paint a picture of the overall fan experience. 
This data analysis should be used to help FIFA improve the organization and promotion of the World Cup. 
I have conducted an in-depth analysis of a data set of tweets from the last World Cup in 2018 in order to help FIFA improve on their core responsibilities 
and create suggestions for the upcoming World Cup in Qatar in November 2022.  


Introduction:
The FIFA World Cup is one of the most watched sporting events in the world, 
and millions of fans worldwide chime in on Twitter to voice their opinions on the proceedings. 
With the next world cup approaching this November 2022 in Qatar, 
I will be looking into what fans on Twitter had to say about the last installment of the World Cup in 2018. 
The goal of this analysis is to gain insights about the likes and dislikes fans expressed on Twitter to create suggestions that FIFA can use to further improve 
the fan experience. 
I used a variety of natural language techniques such as sentiment analysis and topic modelling and key data exploration/visualization techniques
along with my knowledge of the subject matter to investigate the problem statement. 


Dataset:
I found and downloaded my FIFA World Cup Tweet dataset from this Kaggle upload: https://www.kaggle.com/datasets/rgupta09/world-cup-2018-tweets. 
The data is a collection of 530K tweets about the competition starting from the Round of 16 until the Final, 6/29/22 until 7/15/22. 
The dataset uploader used Tweepy API to collect tweets using various key hashtags to filter for world cup specific tweets. 
This dataset is a sample of all tweets made during this period and does not have every single tweet made about the world cup during this time period. 
The dataset had been pre-processed to only include English language tweets and had been cleaned of all non-language elements, 
such as website names, special characters, retweets, user mentions and hashtags. 
The data was downloaded as a .csv file. 
The original file contained 16 columns with key columns being a string of the tweet itself, the datetime of tweet, the location of tweet as a string,
the hashtags and mentions as strings, and the number of followers, friends, likes, characters, and retweets as ints.
The dataset had 530,000 rows with null values in only a select few columns, most importantly the cleaned tweet column had 551 missing tweets and these rows were dropped.
Therefore, the initial shape of the schema was 16 columns and 529499 rows. 
