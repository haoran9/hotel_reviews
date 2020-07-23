# Hotel_reviews_sentiment analysis by NLP
Hotel_reviews_sentiment analysis by NLP

Hotel reviews can be used to automatically understand if some users are positive or negative and why. This project collectd hundreds of reviews from 10 hotels. 
Each review consists of a free-form text review and a report of "happy" or "not happy". 

# Data clearning 
I clean the text by removing unncessary characters, numbers and white space by define a fuction called 'decontract_text(text)'.
You can find more details from 'Hotel_reviews_TF-IDF-_Logistic regression.ipynb'

# Model training 
I use a tfid vectorizer for extracting the features by converting the cleaned text to a matrix of TF-IDF features. For the classification,  logistic regression is applied here. 

![Most frequent Description words](/Images/TEST.png)
