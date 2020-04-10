# Twitter Sentiment Analysis
Sentiment analysis of raw text data can prove to be useful for businesses wishing to gain a general understanding of their customer opinions, especially with the large amount of text produced by social media platforms. 

In this project I perform exploratory analysis on US airline twitter data to determine what public opinion on Twitter tells us about different airline companies. I also train a classifier using generic twitter text, capable of distinguishing positive sentiment tweets from those of negative sentiment. A number of natural language processing techniques and machine learning models are evaluated for their predictive performance.

### Results
- Many people had a negative opinion of US airlines in 2015
- United was both tweeted about the most and received the most complaints
- Customer service issues, and late/cancelled flights formed the majority of complaints
- A ConvNet using 200d GloVe word embeddings was the best performing classifier, achieving a test accuracy of ~78.5% and a ROC AUC of 0.81 on the set of airline tweets

### Libraries used
- keras
- sklearn
- xgboost
- nltk
- gensim
- pandas
- numpy
- matplotlib
- seaborn
- wordcloud