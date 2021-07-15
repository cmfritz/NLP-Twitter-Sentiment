# Phase 4 Project - NLP - Twitter Sentiment Dataset

## Final Project Submission

* Student name: Catherine Fritz
* Student pace: part time
* Scheduled project review date: July 15, 2021
* Instructor name: Josh Johnson

### Business Understanding
Businesses often wish to get feedback on their products, however getting direct feedback usually requires that someone takes time to write something like a product review. People informally talk about their lives in social media like Twitter, and could be a source of informal product feedback. Being able to automatically capture product sentiment, like if a product was being received positively or negatively, could gain companies insight into how their product is being perceived. 

### Data Understanding
The data used for this project is a collection of tweets that have been classified by a human as to whether they are positive, negative, neutral, or if the sentiment is unknown. Further, the subject of the tweets center aroud Apple or Android products. 

Looking at the data, we see that we do have a bit of an imbalance, with a large majority of the classes in the neutral and positive categories. I left the data as it is, but the affect that has the models will be shown later. Also, I decided that the unknown class could be removed, since it does not provide useful information for identifying a sentiment. 

![pic1](./images/class_imbalance.png)

### Data Preparation
TO make the data suitable for modeling, the following steps were taken:

- Remove undesirable characters
- Remove Twitter specific text like @ tags
- Tokenize the text
- Remove common stop words for the English language and also specific to Twitter (like "RT" or "link").
- Lemmatize the stop words to consolidate similar words 

### Modeling


### Evaluation

