![image](https://github.com/anwesapal/Sentiment-Analysis/assets/125749544/6ebfacbe-8956-41e6-bfbf-aff972c48e53)

# **Sentiment Analysis Project**

This sentiment analysis project aims to classify text data into positive or negative sentiment using machine learning techniques.

**Description**

The sentiment analysis project is designed to analyze the sentiment of text data and classify it as positive or negative. It utilizes natural language processing (NLP) techniques and machine learning algorithms to perform the sentiment analysis task. The project includes data preprocessing, feature extraction, model training, and evaluation.

**Features**

1. Preprocess text data by removing noise, cleaning, and tokenization.
2. Perform feature extraction.
3. Train and evaluate sentiment analysis models using machine learning algorithms.
4. Visualize evaluation metrics and results using graphs.

**Dataset**

The sentiment analysis model is trained and tested on the sentiment_tweets3 dataset. The dataset contains a collection of labeled text data with corresponding sentiment labels (positive or negative). The dataset is available at [https://www.kaggle.com/datasets/gargmanas/sentimental-analysis-for-tweets] 

**Model Training**

The sentiment analysis model is trained using the Multinomial Naive Bayes classifier. The training process includes data preprocessing, feature extraction, model training, and evaluation. 


**Results**

The sentiment analysis model achieved the following performance on the test dataset:

                  precision    recall  f1-score   support

           0       1.00      0.95      0.97      1620
           1       0.84      0.99      0.91       443

    accuracy                           0.96      2063
   

**Future Work**

In future iterations, the sentiment analysis project can be expanded by:

* Including sentiment analysis for different languages.
* Implementing advanced deep learning models for improved performance.
* Developing a web-based user interface for easier interaction.

**Conclusion**

This sentiment analysis project successfully developed a machine learning model to classify the sentiment of text data. The model achieved high accuracy and performed well in predicting both positive and negative sentiments. The project highlights the importance of NLP techniques such as data preprocessing and feature extraction. It serves as a foundation for further research in sentiment analysis and has potential applications in social media analysis, customer feedback analysis, and market research.
