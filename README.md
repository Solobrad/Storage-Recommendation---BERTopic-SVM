Web Scrapping to garner reviews from a product.

Sentiment models
1.Word2Vec Models (CBOW and Skip-gram) are used to generate word embedding, BiLSTM Models are used for sentiment classification, trained on embeddings from both CBOW and Skip-gram models.
2.Support Vector Machine (SVM) with a linear kernel, trained on text data features extracted using either CountVectorizer or TF-IDF Vectorizer for sentiment classification.

Review topic extraction
1.BERTopic is employed for topic modeling and visualization of text data
2.Anchored CorEx model is used for advanced topic modeling with guidance from predefined keywords
3.The LDA model in the code is used to identify and describe topics present in a collection of computer storage reviews
