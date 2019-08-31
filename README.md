# Spark

Ihis project we use word2vec model to create word and title embedding and calculate the sentiment analysis scores of the article titles, 
visualize the relationship between title sentiment and article popularity, and then attempt to predict the article popularity 
from the embeddings and other available features.

In order to analyze text Apache Spark is used because it provides a platform for scalable, distributed computing and is faster when dealing with JSON objects and provides fast computing using intermediate caching. We collect the data from News API and NY Times API
