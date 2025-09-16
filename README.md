# Movie-sentiment-analysis-using-Multinomial-Naive-Bayes
Movie sentiment analysis using Multinomial Naive Bayes

## Features

* Load and preprocess IMDB reviews (tokenization, stopword removal, lemmatization/stemming).
  
* Feature extraction with:
  * Bag of Words (CountVectorizer)
  * TF-IDF Vectorizer
  * Word2Vec Embeddings
    
* Model training and evaluation using:
  * Multinomial Naive Bayes
  * Linear SVM
    
## Dataset Setup

This project uses the **IMDB Movie Reviews Dataset** for sentiment analysis.

1. Download the dataset:
   👉 [IMDB Dataset (aclImdb\_v1.tar.gz)](https://ai.stanford.edu/~amaas/data/sentiment/)

2. Extract it inside the project folder.
   After extraction, you should have the following structure:

   ```
   NLP_Assignment/
   ├── code.ipynb
   ├── requirements.txt
   ├── aclImdb/
   │   ├── train/
   │   │   ├── pos/
   │   │   ├── neg/
   │   └── test/
   │       ├── pos/
   │       ├── neg/
   ```

3. Run the notebook.
   The code is already set to read reviews from the `aclImdb` folder in the project directory.
