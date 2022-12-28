# News Headline generator

As the title explains,  I have build a model which generates headlines for a news, this model is 78% accurate and I aim to improve this in future, now lets look walk through the code.


1. Dataset

We have used the dataset called [news_summary.csv(from kaggle)](https://www.kaggle.com/datasets/sunnysai12345/news-summary)

The dataset consists of 4515 examples and contains Author_name, Headlines, Url of Article, Short text, Complete Article. I gathered the summarized news from Inshorts and only scraped the news articles from Hindu, Indian times and Guardian. Time period ranges from febrauary to august 2017.

Lets Look at the head of the dataset

![alt text]("./images/head.png")

2. Data Cleaning and preprocessing

In the notebook tit