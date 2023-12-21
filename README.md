# CodeClauseInternship_Speech_Emotion_Recognition

This project focuses on building models to recognize emotions from speech data based on textual transcripts.

### Dataset (taken from kaggle)

The dataset used contains utterances spoken by people across gender, age groups and countries along with a unique ID. Since no explicit emotion labels are present, rule-based inference is used to deduce possible emotions like happy, sad, fearful, angry and neutral from semantic clues in the texts.

### Preprocessing

Basic text preprocessing like lowercasing, punctuation removal etc. are applied before feature extraction. Word level TF-IDF vectors are extracted from the utterances to encode texts for the models. The dataset is split into train and test sets for modeling.

### Models

* Naive Bayes Classifier: Works well for text data and provides a simple baseline  
* SVM Classifier: Performs well for small and medium-sized datasets

Both models are evaluated using accuracy on the test set. 

### Scope for Improvement

* Expand emotion dictionaries for richer signal
* Experiment with neural networks like RNNs, CNNs for text classification
* Incorporate additional metadata like gender, age and accent features 
* Collect more labeled data from diverse demographics

