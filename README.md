# Text Mining
Sentiment analysis is the interpretation and classification of emotions (positive, negative and neutral) within text data using text analysis techniques. Sentiment analysis allows businesses to identify customer sentiment toward products, brands or services in online conversations and feedback. One such company which practically works based on it's reviews is Yelp where people go to the app/website to check out the reviews of people for say; a restaurant, a service offering or a place. Yelp keeps a well formed database of their reviews which is the database that we have used here to perform our sentiment analysis project. Instead of having to read complete(and long!) reviews we used NLP to come to a conclusion if the review is positive or negative which can then provide a basis to target the negative reviews for the said companies and target what they can improve based on customer feedback.

### About the project
We checked three models in order to check the best suited one for the analysis of text. The three models that we worked on are: MultinomialNB, Logestic regression and Decision Tree classifier. The accuracy were 45%, 46% and 87% respectivel. This proves that the decision tree was the most suited model for this analysis.

## Getting Started
These instructions will get you the necessary packages to deploy this project in your local machine.

### Prerequisites
In the terminal:

```
pip install matplotlib
pip install pandas
```

In the Jupyter notebooks:

```
import nltk
nltk.download()

pip install -U scikit-learn
nltk.download('wordnet')
```

## Licence
<a href="https://github.com/kushagrjolly15/Text_Mining/blob/master/LICENSE">Please click this link for more information on the licence. </a>


## Authors
- Akriti Marwaha
- Kushagr Jolly

