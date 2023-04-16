# Zomato Restaurant Clustering and Sentiment Analysis
This is a project that uses machine learning techniques to cluster restaurants based on certain features and analyze the sentiment of customer reviews for those restaurants. The project is implemented in a Jupyter Notebook file named : 
"Kumar_Abhinav_Zomato_Restaurant_Clustering_And_Sentiment_Analysis.ipynb".

## Project Overview
The project has the following main objectives:

* Cluster restaurants based on certain features such as location, rating, and cuisine.
* Analyze the sentiment of customer reviews for those restaurants.
* Visualize the results of the clustering and sentiment analysis.

## Dataset
The Zomato-Restaurants dataset comprises of 2 files. "Zomato restaurant reviews" has Name of the Restaurant, Name of the customer, their review, rating, follower details, Time of Review and number of photos uploaded along with the review. This data has been mainly used for Sentiment analysis. "Zomato Restaurant names and Metadata" has the details of Name of the Restaurant, Link to order on their restaurant on zomato, Average cost, Tags for the restaurants, Cuisines and timings. This data has been mainly used for clustering.

## Methodology
The project uses the following methodology:

* Data preprocessing: The data is cleaned, processed, and transformed to prepare it for clustering and sentiment analysis.
* Clustering:The preprocessed data is clustered using the K-Means clustering and agglomerative clustering algorithem. This involves identifying groups of restaurants that have similar attributes, such as cuisine, location, and price range.
* Sentiment analysis:The customer reviews for each restaurant are analyzed using sentiment analysis to determine the overall sentiment of the reviews. This involves using Natural Language Processing (NLP) techniques to extract and analyze the sentiment of the text.
* Visualization: The results of the clustering and sentiment analysis are visualized using various charts and graphs.

## Results
The results of this project include:

* A clustered map of restaurants in Hydrabad, based on their attributes
* A sentiment analysis of customer reviews for each restaurant

## Conclusion

It can be concluded that by using K Means Clustering and Agglomerative Hierarchial Clustering we have come up with 4 clusters of Restaurants based on the features provided in the dataset. For Sentiment Analysis we considered Logistic Regression as the model to predict the sentiments of the reviewers based on their reviews and ratings.
