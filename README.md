# MeToo Movement Analysis: Sentiment, Themes, and Impact

## Introduction

In today’s world social media plays a crucial role in analyzing the impact of movements such as #MeToo on people and vice versa. Due to the immense reach of social media, there is a need to analyse and understand people’s reactions to determine the impact of the movement.

## Problem Statement

The problem we aim to address is to conduct sentiment analysis on #MeToo movement twitter data to evaluate the reaction of the public towards the movement, and also to monitor the involvement of key individuals.

The project successfully helps to visualise emotions and sentiments attached with the movement on twitter as well as helps people understand the sentiment associated with public figures who are more frequently mentioned in the tweets.

We are working with Python libraries such as pandas, re, ntlk, spacy, sklearn, plotly and matplotlib for data science, analytics and visualisation as well as AI & ML Models such as LDA or Latent Dirichlet Allocation.

VADER is a library of python used for sentiment analysis particularly social media sentiment of social media text like tweets. VADER is a pre-built sentiment analysis tool and it is used to determine the polarity of the tweets(positive,negative or neutral. In this project we are using VADER for analysing the sentiment of the tweets to focus on the reaction of the people towards the movement and also the sentiment of the public towards certain individuals targeted by the movement.

## Plan of Action

Our plan of action involves a well-structured approach to tackle the analysis effectively. Here are the key steps we have followed:

1. **Analyzing Quantity**: To analyze Twitter data, determine the total number of unique tweets, examine the distribution of tweet timestamps, identify original tweets and retweets, count truncated tweets, and ascertain the number of original tweets or replies.

2. **Analyzing the Popularity of Tweets**: Explore tweets with the highest 'favoriteCount' and 'retweetCount,' identify tweets with high counts for both, analyze content and timing of popular tweets, and investigate influential users associated with high engagement.

3. **Sentiment Analysis**: Conduct sentiment analysis to categorize tweets into positive, negative, and neutral sentiments, analyze the sentiment of popular tweets, track sentiment changes over time, and examine sentiment in tweets directed at well-known individuals.

4. **Words and Phrases**: Discover the most popular words, trigrams, bigrams, and phrases associated with the movement, analyze their occurrence within different sentiment categories, identify trending hashtags beyond #MeToo, and investigate word co-occurrence patterns in the tweets.

5. **Understanding the different topics**: Perform topic modeling to uncover hidden themes in the tweets, analyze sentiment distribution within these topics, explore key terms in each topic, and identify influential figures within the topics.

### Solution Description
In this solution we have primarily used Python libraries like , Artificial Intelligence and Machine Learning models such as , to analyse and visualise the emotions attached with the #metoo tweets and prominent public figures. This insight will greatly help in understanding the reach and impact of such movements that happen on social media platforms as well as help in spreading awareness about safety and empowerment of survivors of such crimes.

### Technologies Used

- Python libraries : re, ntlk, spacy, scikit-learn, plotly, matplotlib, seaborn 
- AI and ML models: LDA (LatentDirichletAllocation), Vader
- Data analysis and visualisation tools: plotly, matplotlib, seaborn

### Results: 
- The results we obtained from this analysis can be seen in the attached python files depicted in various graphs.
- We could infer the overall sentiment of the tweets posted with the hashtag #metoo. The majority category was 'negative', followed by 'positive' and then 'neutral'.
- The involvment of public figures and celebrities in the movement was also highlighted in our results and the overall sentiment of the public towsrds them in this movement.
- The top words and phrases brought out various small topics and events that were discussed in the movement.
- Analysing hashtags other than #metoo, gave us insights into relevant hashtags and their impact on the movement.
- The use of topic modelling uncovered the hidden topics and themes in the movement.
