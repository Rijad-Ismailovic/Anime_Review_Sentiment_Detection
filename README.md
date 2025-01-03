# Anime_Review_Sentiment_Detection
A model made to predict whether an anime review is positive or negative, based on an anime review dataset I scraped.

### Overview
- Scraping was done using Selenium.
- Each review was preprocessed (lemmatization, stopword removal, punctuation removal).
- Labeled data based on scraped review rating (1 or 0 - positive or negative).

### Visualizations:
- Count chart of review ratings.
- Count chart of positive and negative reviews.
- Most common unique words in positive and negative reviews.
- Sentiment by demographic.

### Model:
- Model used: **LogisticRegression**.
- Training/testing split: 70% training, 30% testing.
- **Accuracy: 88%.**

### Comparisons:
- Compared the model with other popular models on the test data.

### Testing on AI-generated reviews:
- Long reviews (as in the dataset): **100% accuracy.**
- Short reviews: **70% accuracy.**
- Neutral reviews: **50% accuracy.**
