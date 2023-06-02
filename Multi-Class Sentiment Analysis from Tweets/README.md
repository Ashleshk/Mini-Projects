# Multi-Class Sentiment Analysis from Tweets 

* **Background:** In this project I learnt the mechanism by which we can aggregate Tweets based on sentiment. The aggregation process is based on the association of tweets with the same feelings, as well as the degree and proportion of the feeling.

[Project code](https://github.com/Ashleshk/Mini-Projects/tree/main/Multi-Class%20Sentiment%20Analysis%20from%20Tweets)

* **My methodology**
    * By building a recurrent neural network capable of analyzing sentiment, using a data set that includes a number of emotions. 
    * The next stage involves using the trained model to sort tweets based on sentiment with a rating ratio. 
    * The final hierarchical schemas (for each one of the feelings in dataset) will show the correlation of the tweeters in terms of the degree of affiliation with that feeling. The Euclidean distance was used to calculate the degree of convergence for a single feeling (depending on the percentage of tweeting classification and belonging to a specific feeling).

![Accuracy](https://github.com/Ashleshk/Mini-Projects/blob/main/Multi-Class%20Sentiment%20Analysis%20from%20Tweets/Test%20Accuracy.png)

![confusion matrix](https://github.com/Ashleshk/Mini-Projects/blob/main/Multi-Class%20Sentiment%20Analysis%20from%20Tweets/Confusion%20matrix.png)

