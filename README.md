# email_spam_classifier
This project implements Machine Learning and deep learning based Email Spam Classifier that automatically distinguishes between spam  emails and ham (legitimate) emails.

🔹 Features

**Dataset** (Prepocessed public corpus trec-2007 dataset) with 75k+ emails labeled as spam or ham.
**Applied text cleaning & preprocessing** (removing stopwords, punctuation, spelling correction, email headers etc were done to clean the dataset).
**Converted text into numerical features using**:   CountVectorizer and TF-IDF Vectorizer

🔹 **Trained Multiple ML Models**

**Logistic Regression**.
**Naïve Bayes**.
**Recurrent Neural Network (RNN)**

🔹 **Evaluation Metrics**
Precision,Recall,F1-Score,Accuracy

🔹**Results**

Achieved high precision in detecting spam messages.
Most of the models had around 98% accuracy and precision


🔹 **Applications**

Can be integrated into email clients for filtering spam.
Useful for text classification problems beyond spam detection (e.g., fake news, sentiment analysis).
