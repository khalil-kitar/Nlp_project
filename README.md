# Sentiment-Analysis
Sentiment Analysis Classifier with Machine Learning Models

### Topics and Contents
Dataset 

1- Our dataset contains many features about user reviews on musical instruments. But, we rarely need those features as our model variables because those features are not really important for sentiment analysis. 

2- We might need to omit our part of removing stopwords in our preprocessing phase, because there might be some important words in determining user sentiments in our model. 

3- From our text analysis, we know that most of the transactions made are related to guitars or other string-based instruments. We can say that guitar got a really high attention from the customers' pool and the sellers can emphasize their products on this instruments. 

Model 

1- We tried almost all classification models available. By using 10-Fold Cross Validation, we get that Logistic Regression Model got the best accuracy and we decided to use this model and tune it. 

2- On our attempt on making prediction to our test set, we also received a nice accuracy and high F1 Score. This means that our model works well on sentiment analysis. 

3- ShapeWe need to consider more Cross Validation Method, such as Stratified K-Fold so that we do not really need to do resampling on our dataset. Also, we are fine without data scaling, but it is highly suggested to do it. 

### Environment
I did all of this project on Google Colaboratory.check the notebook 

### Source of learning
These articles and notebooks are great and really useful for sentiment analysis and NLP. Check it out! 

       Text Preprocessing in Python: Steps, Tools, and Examples 

       Sentiment Analysis — ML project from Scratch to Production (Web Application) 

       Updated Text Preprocessing techniques for Sentiment Analysis 

       Amazon Instrument: Sentimental Analysis 

       Sentiment Analysis | Amazon reviews 

       SMOTE for Imbalanced Classification with Python 

Other Documentations: 

1- Pandas 

2- Matplotlib 

3- Scikit-Learn 

4- ShapeNatural Language Toolkit 
