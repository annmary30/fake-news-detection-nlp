# fake-news-detection-nlp
Fake News Detection using NLP (TF-IDF + Logistic Regression)

This project uses the LIAR dataset to classify news statements as Real or Fake.  
The pipeline applies NLP preprocessing, TF-IDF vectorization, and Logistic Regression classifier.  
Experiments were also done with lemmatization and SVM.

## Final Model

- Vectorizer: TfidfVectorizer(max_features=20000, ngram_range=(1,2))
- Classifier: Logistic Regression (C=2.0)
- Validation Accuracy: ~62.4%
- Test Accuracy: ~62.3%

## Dataset

[LIAR dataset](https://www.cs.ucsb.edu/~william/data/liar_dataset.zip)
