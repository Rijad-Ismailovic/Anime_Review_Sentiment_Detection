# Anime_Review_Sentiment_Detection
A model made upredicts whether a anime review is positive or negative, based on a anime review dataset I scraped.

Scraping was done using Selenium.
Each reviw was preprocessed (lemmatization, stopword removal, punctiation removal).
Labeled data based on scraped review rating (1 or 0 - pos or negative).
Made some graphs:
  - Count chart of review ratings.
  - Count chart of positive and negative reviews.
  - Most common unique words in positive and negative words.
  - Sentiment by demographic.
Made my model by using LogisticRegression. 70% of the data for training, 30% for testing (From the dataset). **Accuracy: 0.88%**
Compared model with other popular models on the test data:
Tested our model on different AI generated reviews:
  - Long reviews (As they are in the dataset): 100%
  - Short reviews: 70%
  - Neutral reviews: 50%


