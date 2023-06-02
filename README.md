# Mini-Projects
Small Projects to revise ML, DL Algorithms

# 1. Classification Projects
- **Random Forest, KNN, Log-Regression, ANN**
In summary, the following six machine learning models were developed to classify Autism using 13 selected features from the ABIDE dataset and reducing the subjects to 785. Highest accuracy (84.71 %) and ROC_AUC score (0.74) was achieved by XGBoost algorithm, followed by Random Forest which too was pretty close. The classification report and confusion matrix of the best model is given above.

[Project code](https://github.com/Ashleshk/Mini-Projects/tree/main/Random%20Forest%2C%20KNN%2C%20Log-Regression%2C%20ANN)

![Classification Algo result](https://github.com/Ashleshk/Mini-Projects/blob/main/Random%20Forest%2C%20KNN%2C%20Log-Regression%2C%20ANN/Result.PNG)


# 2. Fake Job Detection
There are around 800 false job descriptions among the 18K job descriptions in the dataset. The information includes both textual and meta-information about the jobs. The dataset has been used to train classification models that can detect spurious job descriptions.

[Project code](https://github.com/Ashleshk/Mini-Projects/tree/main/Fake%20Job%20Detection)

**Problem Statement/Background:**
- Detecting fake job postings and combating fraudulent activities in the job market.

**Work:**
- Developed a machine learning model utilizing natural language processing techniques to analyze job postings.
- Trained the model on a labeled dataset to identify characteristics associated with fake job postings.

**Result:**
- Successfully detected and classified fake job postings with a high degree of accuracy.
- Contributed to creating a safer and more trustworthy job market for job seekers.

![Fake job Matrix](https://github.com/Ashleshk/Mini-Projects/blob/main/Fake%20Job%20Detection/Confusion-Matrix.PNG)


# 3. Donald Trump Trumping

[**Project Title: Donald Trump Tweet Generator using LSTM**](https://github.com/Ashleshk/Mini-Projects/tree/main/Donald%20Trump%20Trumping)

**Problem Statement/Background:**
- Replicating the unique tweeting style of former President Donald J. Trump using artificial intelligence.

**Work:**
- Utilized a Long Short-Term Memory (LSTM) neural network to analyze a dataset of Donald Trump's previous tweets.
- Trained the LSTM model to generate new tweets that closely resemble Trump's distinctive writing style.

**Result:**
- Developed a tweet generator that produces highly realistic tweets emulating Trump's writing patterns, vocabulary, and tone.
- Showcased the potential of deep learning algorithms in capturing and replicating the writing styles of influential individuals.

![Donald trump result](https://github.com/Ashleshk/Mini-Projects/blob/main/Donald%20Trump%20Trumping/Donald%20Trump%20result.png)

# 4. Semantic Segmentation of lungs from X-ray images 

[Project code](https://github.com/Ashleshk/Mini-Projects/tree/main/Semantic-Segmentation-of-lungs-using-Xray-Image)

**Problem Statement/Background:**
- Accurately identifying and segmenting lung regions in X-ray images for medical analysis and diagnosis.
- The model relies on forming a mask through which that region can be cut.

**Work:**
- Using a pre-trained Model, to extract the characteristics and use it to train to X-ray images dataset to find a mathematical formula that links these characteristics to each other and thus the ability to build the mask as required.

**Result:**
- Achieved precise and accurate segmentation of lung regions in X-ray images, overcoming challenges such as image quality variations and anatomical differences.
- Enhanced the efficiency and accuracy of lung diagnosis, aiding radiologists in interpreting X-ray images and detecting pulmonary diseases.


# 5. Multi-Class Sentiment Analysis from Tweets 


* **Background:** In this project I learnt the mechanism by which we can aggregate Tweets based on sentiment. The aggregation process is based on the association of tweets with the same feelings, as well as the degree and proportion of the feeling.

[Project code](https://github.com/Ashleshk/Mini-Projects/tree/main/Multi-Class%20Sentiment%20Analysis%20from%20Tweets)

* **My methodology**
    * By building a recurrent neural network capable of analyzing sentiment, using a data set that includes a number of emotions. 
    * The next stage involves using the trained model to sort tweets based on sentiment with a rating ratio. 
    * The final hierarchical schemas (for each one of the feelings in dataset) will show the correlation of the tweeters in terms of the degree of affiliation with that feeling. The Euclidean distance was used to calculate the degree of convergence for a single feeling (depending on the percentage of tweeting classification and belonging to a specific feeling).

![Accuracy](https://github.com/Ashleshk/Mini-Projects/blob/main/Multi-Class%20Sentiment%20Analysis%20from%20Tweets/Test%20Accuracy.png)

![confusion matrix](https://github.com/Ashleshk/Mini-Projects/blob/main/Multi-Class%20Sentiment%20Analysis%20from%20Tweets/Confusion%20matrix.png)


# 6. US Consumer Finance Complaints Classification- NLP

The Consumer Financial Protection Bureau publish thousands of consumers’ complaints about financial products and services to companies for response on weekly basis. The goal of this NLP project is to build a model that can accurately classify those consumer complaints into the product category they belong to using the content of the complaint. The data is sourced from kaggle.

[code](https://github.com/Ashleshk/Mini-Projects/tree/main/US%20Consumer%20Finance%20Complaints%20Classification%20using%20NLP)
![result](https://github.com/Ashleshk/Mini-Projects/blob/main/US%20Consumer%20Finance%20Complaints%20Classification%20using%20NLP/Finance%20result.png)

# Other Project 
* **Machine Learning Project:** - [Link](https://github.com/Ashleshk/Mini-Projects/tree/main/Machine%20Learning%20Projects)
    * Gaussian Classification
    * Logistic Regression
    * Logistic Regression with k-Fold Cross Validation
    * k-Means Clustering
    * Support Vector Machine
    * Neural Network

* **Kaggle** - [Link](https://github.com/Ashleshk/Mini-Projects/tree/main/Kaggle%20Projects)
   * Credit-Card Fraud Detection
   * House Prices Prediction
   * Titanic - Fun Project