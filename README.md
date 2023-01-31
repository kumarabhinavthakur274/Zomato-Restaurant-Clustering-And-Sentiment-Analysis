# Zomato-Restaurant-Clustering-And-Sentiment-Analysis

The dataset contains information from 105 Zomato Restaurants in Hyderabad. The project focuses on customers and the company to cluster Zomato restaurants into different segments that can be used to solve some of the business cases that can directly help customers find the Best restaurant in their locality and the analysis can be beneficial for the company to grow up and work on the fields where they are currently lagging. Data could be used for sentiment analysis to acquire knowledge about Zomato Restaurants' customers' experiences. We have made two different models in our project
1. Clustering Model - K Means Clustering , Agglomerative Hierarchial Clustering
2. Sentiment Analysis Model -  Decision tree, Random forest, K- Nearest Neighbours, SVM, Logistic Regression, XGboost, Multinomial Naive Bayes and Light Gradient Boosting Machines.

We were provided with two datasets - Zomato Restaurants Name and Zomato Restaurants Reviews. We used different imputers to deal with the missing values and manipulated necessary columns to make it analysis ready. Then performed EDA and performed required feature engineering for both the models separately. We used Textual Data PreProcessing Using NLP for the Sentiment Analysis Model. 

For Clustering we used K Means and Agglomerative Hierarchial Clustering Algorithms to cluster the Zomato Restaurants and made a separate Sentiment Analysis model to classify the Sentiments as Positives and Negatives. We also used World Cloud to vizualize the most frequent words in both Positive and Negative sentiments reviews and finally built some classification models and chose the best one by comparing the evaluation metrics.
