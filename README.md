# Customer Sentiment Analysis
Predicting the sentiment of customers from restaurant reviews using NLP.

Methodology:
1. In this problem, we use the Natural Language Toolkit to get a list of stopwords.
2. We then stem each review to its most simple form by removing stopwords and retaining only the words that will help determine if its a good or bad review.
3. We convert the reviews into a matrix of token counts (Bag of words) using CountVectorizer.
4. The data is split into training and test sets.
5. We use the decision tree classifier to train the model.
6. The accuracy score comes to 0.81.
