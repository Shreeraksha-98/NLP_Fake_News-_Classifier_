# Fake News Classifier 

- The data set has the features
    - Id
    -Title (title of the news)
    -Author (the author for the news)
    -Text (text in the news)
    -Lable (1 for fake news and 0 for actual news)
 - The tilte column is considered for the classification of fake news
 - The data is cleaned using stopwords and stemmed using PorterStemmer using nltk library
 - The words are then converted to word of bags using CountVectorizer from Sklearn library
 - The data is split for training and testing
 - The model is trained for MultinomialNB based on naive bayes therom.
 - Different alpha values are applied for the same model to check for different accuracy
 - The model is also trained for Passive aggresive classifier from sklearn and has obtained an accuracy of 91.0%