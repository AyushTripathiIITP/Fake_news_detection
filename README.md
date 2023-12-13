# Fake News Detection

Fake News Detection in Python

This project utilizes various natural language processing techniques such as lemmatization, tokenization, and vectorization, along with machine learning algorithms, to classify fake news articles using Python's scikit-learn libraries.

### Data Pre-Processing

In this project, we used various NLP cleaning techniques to properly understand the data
1. Removing non alphabetical words and converting text to lower case. 
2. Tokenization of file
3. Stemming and lemmetization of Tokens
4. Stopword Filtering to remove repeating words
5. N-graming using TF-IDF vectorisation to give weights to different key words


### Feature Selection

1. Utilized the bag of words technique to find the frequency of each word.
2. Used Tfidf vectorization technique on (1 to 4) n-grams to find frequency and importance of words.
3. Used POS and word-embedding to relate words using glove.3b.50d.

### Model

1. Employed the PassiveAggressiveClassifier for classification.
2. Plotted the confusion matrix and achieved accuracy of 55%

### Steps to Contribute

### 1. Fork the Repository

Start by forking our repository to your GitHub account. This will create a copy of the project that you can freely experiment with.

### 2. Clone the Repository

Clone the forked repository to your local machine using the following command:

```bash
git clone https://github.com/YashSachan2/Fake_news_detection.git
```

### 3. Create a new branch for your feature or bug fix:
    ```bash
    git checkout -b feature-name
    ```
### 4. Make your changes and commit them with a clear and concise message:
    ```bash
    git add .
    git commit -m "Your clear and concise message"
    ```
### 5. Push your changes to your fork:
    ```bash
    git push origin feature-name
    ```
### 6. Open a pull request, referencing any relevant issues.

### 9. Wait for Review and Merge

Once you've submitted a pull request, I will review your changes. Be patient during this process, and be ready to address any feedback or questions. Once your changes are approved, they will be merged into the main project.


# HAPPY CONTRIBUTING!!
