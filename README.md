# Fake News Detection

Fake News Detection in Python

In this project, we have used various natural language processing techniques and machine learning algorithms to classify fake news articles using sci-kit libraries from python. 

### Data Pre-Processing

In this project, we used various NLP cleaning techniques to properly understand the data
1. Tokenization of file
2. Stemming and lemmetization of Tokens
3. Stopword Filtering to remove repeating words
4. N-graming to give weights to different key words


### Feature Selection

1. Used bag of words technique to find frequency of each word
2. Used Tfidf vectorization technique on (1 to 4) n-grams to find frequency and importance of words
3. Used POS and word-embedding to relate words using glove.3b.50d
