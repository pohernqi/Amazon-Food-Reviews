# Project Overview
The project utilizes a subset of 5,000 reviews from the Amazon Fine Food Reviews dataset to classify customer sentiments into positive, negative, or neutral categories. A comprehensive preprocessing pipeline is implemented, including tokenization, stop-word removal, and lemmatization. Multiple models are then trained and evaluated, including lexicon-based approaches (TextBlob, VADER, Afinn), traditional machine learning models (Naive Bayes, Logistic Regression, Decision Tree), deep learning models (CNN, BiLSTM), and transformer-based models (BERT, RoBERTa, DistilBERT). Performance is assessed using metrics such as accuracy, precision, recall, and F1-score.
To address class imbalance in the dataset, the Synthetic Minority Over-sampling Technique (SMOTE) is applied. The project also compares the impact of different feature extraction methods, such as TF-IDF and Word2Vec, on model performance.

# Future Work
Expanding the dataset beyond 5,000 samples could allow for better utilization of embedding techniques like Word2Vec and might improve the generalization of the models.  Additionally, incorporating other Transformer variants such as XLNet or ALBERT may offer further insights into performance-efficiency trade-offs and yield even better results. Finally, integrating explainability methods (such as SHAP and LIME) into model evaluation can enhance interpretability, particularly for complex models like BERT, aiding in better understanding and trust in model predictions.



