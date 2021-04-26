# _How's 2021 going? Twitter Sentiment Analysis (NLP)_

#### An NLP Data Science project to find out how people feel about 2021. Click [here](https://sandra-maria-machon.medium.com/hows-2021-going-twitter-sentiment-analysis-nlp-e62e4e8f3767) for the article
This project used Natural Language Processing (NLP) techniques to analyse users' sentiment towards 2021. After 2020 turned out to be a disaster, we've all been looking forward to 2021 with hope. I decided to perform a Twitter Sentiment Analysis to find out if the new year is treating us well! I scraped 37,621 tweets using the following search queries:
- "2021 is"
- "2021 will"
- "This year"

The tools used include ***Tweepy*** (for mining tweets), ***Pandas*** (for data cleaning/wrangling), ***Tweet Preprocessor*** (for rapid tweet cleaning), ***NLTK*** (for tokenization, stopwords removal and POS tagging), ***Plotly***, ***Matplotlib*** and ***Word Cloud*** (for visualization).

With this project I wanted to get familiar with the Natural Language Processing (NLP) techniques and answer the following questions:

- ***What are the most common words people use to describe 2021?***
- ***What is the number of tweets with positive, negative and neutral sentiment?***
- ***What are the most common words used in positive, neutral and negative tweets?***
- ***What are the most liked and retweeted posts?***

## Contents

In this repository you'll find:
- A notebook with a source code for the Twitter Sentiment Analysis
- A notebook with a source code for the Tweepy Twitter API scraper
- "Neon.ttf" font file which can be used to customise your Word Cloud visualisation
- "twitter.png" file which can be used as a mask for the Word Cloud to create a shape of Twitter logo

## Main Findings

With this project we learnt the following insights:
### 1) "Good", "Best, "Happy", "Great" and "Bad" are the top 5 words used to describe 2021 ###
<p align="center">
<img src="https://user-images.githubusercontent.com/55002027/114279849-86763900-9a2e-11eb-8dd2-796c3d327afe.png" />
</p>

#### The Word Cloud below presents the most frequently used adjectives accross all tweets: ###
<p align="center">
<img src="https://user-images.githubusercontent.com/55002027/114281049-14a0ee00-9a34-11eb-8992-68fe771b3e76.png" />
</p>

### 2) The majority of tweets had a positive sentiment (19,107), followed by neutral (9,484) and negative (8,436) sentiment ###
<p align="center">
<img src="https://user-images.githubusercontent.com/55002027/114280849-2635c600-9a33-11eb-8610-128449948d19.PNG" />
</p>

Click [here](https://datapane.com/u/machonsm/reports/my-plot/embed/) for an interactive version of this graph!

### 3)The most common word in positive tweets was "good", word "last" in negative tweets and "new" in neutral
<p align="center">
  <img src="https://user-images.githubusercontent.com/55002027/114280902-58dfbe80-9a33-11eb-90fc-2bd322151395.PNG" />
</p>

Click [here](https://datapane.com/u/machonsm/reports/sun-burst/embed/) for an interactive version of this graph!


### 4) The most popular tweet was retweeted 9199 times and the most liked tweet received 25683 likes!
<p align="center">
  
  <img src="https://user-images.githubusercontent.com/55002027/115115780-3519fc80-9f8e-11eb-98ae-3377dc5043da.PNG" />
</p>

Click [here](https://datapane.com/u/machonsm/reports/my-plot4/embed/) for an interactive version of this graph!
<p align="center">
  
  <img src="https://user-images.githubusercontent.com/55002027/115115784-36e3c000-9f8e-11eb-932a-f0389102bd34.PNG" />
</p>

Click [here](https://datapane.com/u/machonsm/reports/my-plot2/embed/) for an interactive version of this graph!

## Links

- [Medium Article](https://sandra-maria-machon.medium.com/hows-2021-going-twitter-sentiment-analysis-nlp-e62e4e8f3767)
- [LinkedIn](https://www.linkedin.com/in/sandra-machon/)
- [Portfolio](https://www.sandramachon.com/)


